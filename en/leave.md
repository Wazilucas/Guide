# Setting Up Leave Messages

!!! tip
    Before we start, Zira will need the `Send Messages` permission for the channel you want to send messages to.

## Channel

!!! example "Command Usage"
    z/leave channel #channel or Channel ID

### Description

Setup the channel to send the leave messages to.

!!! abstract "Example"
    ![Example](https://i.imjake.me/files/a4omo.png)

To stop the leave messages, do:

!!! example "Command Usage"
    z/leave channel disable

!!! abstract "Stop"
    ![Stop](https://i.imjake.me/files/kckog.png)

## Message

!!! example "Command Usage"
    z/leave add Message

Placeholders that you can use in the message:
* $user - username
* $guild - guild name
* $membercount - new member count

### Description

This will add a new message to the list of messages when someone leaves. If you only add one, it will be that one every time. If you add more than one it will randomly pick from the list you create. Just run the command more than once to add more.

#### Example

!!! abstract "Example"
    ![Message](https://i.imjake.me/files/ceh2s.png)

## Remove Message

!!! example "Command Usage"
    z/leave remove

***Then Do***

!!! example "Command Usage"
    z/leave remove ID

### Description

The first command will list all of your current leave messages, and then use the second command to delete specific leave messages.

!!! abstract "Example"
    ![Message](https://i.imjake.me/files/ceh2s.png)

!!! success "Congratulations!"
    You've setup leave messages with Zira!
