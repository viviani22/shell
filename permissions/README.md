# Shell, permissions

#### Scripts for executing various shell permissions

- [0-iam_betty](https://github.com/viviani22/shell/blob/main/permissions/0-iam_betty) Switches the current user to the user betty.
- [1-who_am_i](https://github.com/viviani22/shell/blob/main/permissions/1-who_am_i) Prints the effective username of the current user.
- [2-groups](https://github.com/viviani22/shell/blob/main/permissions/2-groups) Prints all the groups the current user is part of.
- [3-new_owner](https://github.com/viviani22/shell/blob/main/permissions/3-new_owner) Changes the owner of the file hello to the user betty.
- [4-empty](https://github.com/viviani22/shell/blob/main/permissions/4-empty) Creates an empty file called hello.
- [5-execute](https://github.com/viviani22/shell/blob/main/permissions/5-execute) Adds execute permission to the owner of the file hello.
- [6-multiple_permissions](https://github.com/viviani22/shell/blob/main/permissions/6-multiple_permissions) Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- [7-everybody](https://github.com/viviani22/shell/blob/main/permissions/7-everybody) Adds execution permission to the owner, the group owner and the other users, to the file hello
- [8-James_Bond](https://github.com/viviani22/shell/blob/main/permissions/8-James_Bond) Sets the mode to 007 for the file hello.
- [9-John_Doe](https://github.com/viviani22/shell/blob/main/permissions/9-John_Doe) sets the mode of the file hello to -rwxr-x-wx
- [10-mirror_permissions](https://github.com/viviani22/shell/blob/main/permissions/10-mirror_permissions) Sets the mode of the file hello the same as olleh’s mode.
- [11-directories_permissions](https://github.com/viviani22/shell/blob/main/permissions/11-directories_permissions) Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users without changing regular files. 
- [12-directory_permissions](https://github.com/viviani22/shell/blob/main/permissions/12-directory_permissions) Creates a directory called my_dir with permissions 751 in the working directory.
- [13-change_group](https://github.com/viviani22/shell/blob/main/permissions/13-change_group) Changes the group owner to school for the file hello
- [14-change_owner_and_group](https://github.com/viviani22/shell/blob/main/permissions/14-change_owner_and_group) Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
- [15-symbolic_link_permissions](https://github.com/viviani22/shell/blob/main/permissions/15-symbolic_link_permissions) Changes the owner and the group owner of _hello to vincent and staff respectively.
- [16-if_only](https://github.com/viviani22/shell/blob/main/permissions/16-if_only) Changes the owner of the file hello to vincent only if it is owned by the user guillaume.

