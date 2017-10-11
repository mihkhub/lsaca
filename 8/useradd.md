# Options
## --gid, -g GROUP
The group name or number of the user's initial login group. The group name must exist.

## --no-user-group, -N
Do not create a group with the same name as the user, but add the user to the group specified by the -g option.

# Example
Create an user with administration permission.
```
# useradd -N changfengc -g wheel
```
