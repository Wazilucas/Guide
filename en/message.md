# Setting Up A Message

!!! tip
    Before we start, Zira will need the `Send Messages` permission if you want Zira to send the message for you, rather than using your own message.

!!! example "Command Usage"
    z/message [Message ID]

if you would like to use your own message. 

!!! question
    You can learn how to get a message ID [here](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)
 
***Or***
 
!!! example "Command Usage"
     z/message Message You Want Here
     
if you would like Zira to send the message.

### Description

Set or send the message(s) that users will be able to react on.

!!! abstract "ID Example"
    ![ID Example](https://i.imjake.me/files/gzckj.png)

!!! abstract "Message Example"
    ![Message Example](https://i.imjake.me/files/6o10y.png)

!!! note
    The message will be sent in the channel you specified earlier in the "Setting Up A Message" step, you don't have to run this command in the channel you want the message to send.

!!! success "Congratulations!"
    You've successfully setup or sent a message with Zira. The next step is adding roles to the message we just set or made! You have 3 choices on how you want your reaction roles to work:

1. [z/add - *Allows users to pick multiple roles from a message, such as PS4, PC, XBox; allowing users to pick and choose as many as they want, etc.*](/add)

2. [z/toggle - *Allows only one role from a/ each message, such as if you bind reactions to colors, and you want the user to only have one color role at a time, etc.*](/toggle)

3. [z/once - *Allows a role to be claimed only once, such as accepting the server rules, accepting terms to join a new channel, etc.*](/once)
