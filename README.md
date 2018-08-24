# Slack for Conferences

## License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

## Contributions
This guide is available on [Github](https://github.com/phildini/slack-for-conferences). Please open issues or Pull Requests there if you have corrections or additions!

## Intro
So you're running a conference, and you want to have a place for your attendees to chat. Hooray! Adding these channels can help attendees mingle and meet and plan out-of-conference activities.

Slack is a popular choice for conference chat, and this guide is a checklist of suggestions to make your life as an organizer as painless as possible, and give your attendees the best experience. Let's begin!

## Pre-conference, before you invite attendees
1. Decide if slack _is_ the right choice for you. Yes, it's popular, but there are lots of open source tools that perform a similar function, and slack/chat fatigue is real. Make sure that your team is ready to take on the commitment of an online community when you open up your conference slack.
1. Make sure your Code of Conduct (which you have, because you're a cool conference organizer) has language that includes online spaces.
1. In your new slack, create some channels you want available for all attendees. #intro, #slack-tips, and #codeofconduct are good starting points!
1. Rename your #general channel to #announcements. [https://get.slack.help/hc/en-us/articles/201654073-Rename-a-channel](https://get.slack.help/hc/en-us/articles/201654073-Rename-a-channel)
1. Create a new channel called #general or #commons to give your attendees space to talk.
1. In your workspace settings (https://{your workspace url}.slack.com/admin/settings)
    1. Under "Default Channels", add your newly-created channels
    1. Under "Email Display" turn "Display email addresses" off.
    1. Under "Messaging" change "People who can use @channel and @here:" to "Workspace Owners and Admins Only"
1. In your workspace permissions (https://{your workspace url}.slack.com/admin/settings#permissions):
    1. Under "Messaging" change "People who can post to #general:" to "Workspace Owners and Admins Only"
    1. Under "Messaging" change "People who can use @everyone:" to "Workspace Owners and Admins Only"
1. In your workspace app permissions (https://{your workspace url}.slack.com/apps/manage/permissions), turn "Approved Apps" to "On"
1. Add the twitter integration (https://{your workspace url}.slack.com/apps/A0F7XDW93-twitter) for your conference's twitter account to your #announcements channel. Now you only need to post announcements in one place! Note: the account you authenticate the integration with does not need to be the account you want to mirror.

## During the conference
1. If possible, have someone or multiple someones from the organizing team join all channels to monitor. This can be a volunteer, or a set of volunteers, who are willing to make sure the discussion is following the CoC. Importantly, this person should know how escalate issues to the organizers.

## After the conference
1. Decide if you want this to be a permanent community that carries over year-to-year, of if you want to shut it down between conferences. Either approach is totally great! Your attendees might enjoy the constant community, but now you have the burden of year-round community management.
    1. If you do decide to shut it down, give your attendees a heads-up, and time to capture links or other people's contact information.

## Contact
Feel free to contact me (phildini@phildini.net) if you would like to chat about how to make the best possible online experience for your attendees, and how to improve your conference overall.