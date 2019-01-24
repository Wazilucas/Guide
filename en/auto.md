# Setting Up Autorole

!!! tip
    Before we start, Zira will need the permission `Manage Roles` to be able to give roles.

## User Role

!!! example "Command Usage"
    z/autorole user @Role

***Or***

!!! example "Command Usage"
    z/autorole user Role

### Description

Sets the role that will be given when a user joins the guild, no need to react.


!!! abstract "Mention Example"
    ![Mention Example](http://i.imjake.me/files/cy7j6.png)

!!! abstract "Name Example"
    ![Name Example](http://i.imjake.me/files/tu064.png)

You can remove a role from being given by doing the command again.

!!! abstract "Remove Example"
    ![Remove](http://i.imjake.me/files/3mej5.png)

## Bot Role

!!! example "Command Usage"
    z/autorole bot @Role

***Or***

!!! example "Command Usage"
    z/autorole bot Role

### Description

Sets the role that will be given when a bot joins the guild. This role must also be below Zira's role to be given. It will not be given if it's on the same tier.

!!! abstract "Mention Example"
    ![Mention Example](http://i.imjake.me/files/3d524.png)

!!! abstract "Name Example"
    ![Name Example](http://i.imjake.me/files/6jdj4.png)

You can remove a role from being given to bots by doing the command again.

!!! abstract "Remove Example"
    ![Remove](http://i.imjake.me/files/bqewg.png)

## Show

!!! example "Command Usage"
    z/autorole show

### Description

Shows the roles you've previous set to be automatically given to users and bots.

!!! success "Congratulations!"
    You've successfully setup auto roles with Zira.
