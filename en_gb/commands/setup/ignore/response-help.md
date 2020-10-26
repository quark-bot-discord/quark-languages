```
Ignore Options


Executors

Executors are the people who carry out an action on another user.\ni.e. The user who deletes another user's message.\n\nIgnore executors with `{prefix}serverlog ignore executor @user` \n(You can mention as many people at once as you like.)

No executors ignored yet!


Targets

Targets are the people who are doing the action.\ni.e. The user who sent the message that was deleted.\n\nIgnore targets with `{prefix}serverlog ignore target @user` \n(To remove a user from the ignore list, just run this command again.)

No targets ignored yet!


Messages

Messages with this exact content are not recorded to the serverlog when deleted.\ni.e. Certain bots may be constantly deleting users' messages for a game, but this can clog up the serverlog very quickly.\n\nIgnore specific messages with `{prefix}serverlog ignore message [exact message content to ignore, but with no brackets]` \n(To remove a message from the ignore list, just run this command again.)

No messages ignored yet!


Channels

Messages in this channel are not recorded to the serverlog.\ni.e. You may have a private channel which you do not want messages there to be logged to the serverlog.\n\nIgnore messages in a certain channel with `{prefix}serverlog ignore channel [#channel to ignore, but with no brackets]` \n(To remove a channel from the ignore list, just run this command again.)

No channels ignored yet!


WARNING!

DO NOT IGNORE USERS THAT YOU DO NOT FULLY TRUST OR IGNORE PUBLIC CHANNELS

This feature can easily lead to abuse, since there is no way to see what ignored users have done or what has happened in an ignored channel. Even then, it is still not recommended that you ignore users or channels unless **absolutely necessary**.
```