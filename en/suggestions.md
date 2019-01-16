# Setting Up Server Suggestions

## Setting the Channel

### Command Usage

```z/suggestion channel <new | approved | denied | invalid | potential> <#channel or Channel ID>```

Or if you are a [premium server](http://zira.pw/premium) and only want your suggestions posted in a specific channel, do: 

```z/suggestion submit <#channel or Channel ID>```

### Description

Set the channels that suggestions will be sent to, according to their status. You can set your channel based on the suggestion status. 

If you set the channel to be the "new" channel, each time a user posts a suggestion, it will be sent to said channel for review / voting.

If you set the channel to be the "approved" channel, when a suggestion is approved, it will be sent to said channel. This is the same behavior for denied and potential.

If you set the channel to be the "invalid" channel, when a suggestion is marked as invalid it will be sent to said channel, we personally think you should set this to a moderator only spam channel, since it's meant for either abuse or bad suggestions.

#### Example

>![Example](http://i.imjake.me/files/402x0.png)

#### Premium Suggestion Examples

>![Example](http://i.imjake.me/files/lz4uk.png)

## Submit

### Command Usage

```z/submit Suggestion / Message```

### Description

Submit a suggestion to the server.

#### Example

>![Example](http://i.imjake.me/files/1u99y.png)
No command is displayed as it is deleted upon send, and immediately resent by the bot, as shown in the photo.

## Approve

### Command Usage

```z/approve MessageID```

***Or***

```z/approve MessageID Reason```

*Note*: You can see how to get a Message ID [here](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

### Description

Approve a suggestion and (if set up) send to the approved suggestion channel.

## Deny

### Command Usage

```z/deny MessageID```

***Or***

```z/deny MessageID Reason```

*Note*: You can see how to get a Message ID [here](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

### Description

Deny a suggestion and (if set up) send to the denied suggestion channel.

## Maybe

### Command Usage

```z/maybe MessageID```

***Or***

```z/maybe MessageID Reason```

*Note*: You can see how to get a Message ID [here](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

### Description

Potentially approve a suggestion (maybe) and (if set up) send to the maybe suggestion channel.

## Invalid / Spam

### Command Usage

```z/invalid MessageID```

***Or***

```z/invalid MessageID Reason```

*Note*: You can see how to get a Message ID [here](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

### Description

Mark a suggestion as invalid and (if set up) send to the invalid suggestion channel. We recommend you set this to a mod-only spam channel, as mentioned at the top of this page.

## Premium Only: DM

### Command Usage

```z/suggestion dm```

### Description

A toggle to allow users to be updated about their suggestion, when it updates any of the status updates listed above.

## Premium Only: Reaction

### Command Usage

```z/suggestion reaction```

###Description

Set whether or not emoji's should be added on new suggestions.

## Premium Only: Emoji

### Command Usage

```z/suggestion emojis <first emoji> <second emoji>```

###Description

Set the 2 emojis that will be added upon a new suggestion submission, they will appear in order.

## Role

### Command Usage

```z/suggestion role Role```

***Or***

```z/suggestion role @Role```

###Description

Limit approving, denying, etc. of suggestions to a certain role.

Congratulations! You've successfully set up a fully functioning suggestions system in your server with Zira!