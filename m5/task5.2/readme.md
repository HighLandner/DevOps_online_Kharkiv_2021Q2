**Task 5.2**
<br>

**/etc/passwd** directory contains brief inGIfo about users: their passwords (password pveerviews only in **/etc/shadow** with sudo), **UID** - user unique identifier, **GID** - group unique identifier that user participate, their directory location. 
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.2/images/passwd.png">
<br>

**/etc/group** directory contains only users` group info.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.2/images/group.png">
<br>

-g parameter shows only the effective GID, -G parameter shows all GIDs
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.2/images/id.png">
<br>

**useradd** adds new user. -c parameter leaves UID comment, -d defines user directory, -g defines user group, -e - expire date.
<br>
**userdel** deletes user account.
<br>
**sudo deluser username** with --remove-all-files parameter deletes user with all his data.
<br>
**usermod** changes user options. -l parameter changes user`s name, -g adds user to certain group, -L locks user account, -U unlocks user.
<br>
**skell_dir** is a directory that contains copy files to recently created directory.
<br>

**Extended directory info**. Info contains UGO rights - first three bits relates to user, second three bits relats to group, last - to others (**-** is a regular file, **d** is directory, **b** is block device, **c** is character device, **l** is symbolik link, **p** is pipe, **s** is socket; **rwx** is read, write and executable right; **t** is sticky bit), group that directory belongs, creation date, PID. 
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.2/images/la.png">
<br>





 
