# Setting Up Join messages

!!! tip
    Before we start, Zira will need the `Send Messages` permission for the channel you want to send messages to.

## Channel

!!! example "Command Usage"
    z/join channel #channel or Channel ID

### Description

Setup the channel to send the join messages to.

!!! abstract "Example"
    ![Example](https://i.imjake.me/files/ifkr6.png)

To stop the join messages, do:

!!! example "Command Usage"
    z/join channel disable

!!! abstract "Disable"
    ![Disable](https://i.imjake.me/files/di4iq.png)

## Message

!!! example "Command Usage"
    z/join add Message

Placeholders that you can use in the message:
* $user - username
* $mention - user mention
* $guild - guild name
* $membercount - new member count

### Description

This will add a new message to the list of messages when someone joins. If you only add one, it will be that one every time. If you add more than one it will randomly pick from the list you create. Just run the command more than once to add more.

!!! abstract "Message"
    ![Message](https://i.imjake.me/files/ceh2s.png)

## Remove Message

!!! example "Command Usage"
    z/join remove

***Then Do***

!!! example "Command Usage"
    z/join remove ID

### Description

The first command will list all of your current join messages, and then use the second command to delete specific join messages.

!!! abstract "Message"
    ![Message](https://i.imjake.me/files/ceh2s.png)

!!! success "Congratulations!"
    You've set up join messages with Zira!