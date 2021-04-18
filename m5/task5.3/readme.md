**Task 5.3**
**Part 1**
<br>

**Process states in Linux**: Running & Runable, Stopped, Uninterraptable sleep, Interruptable sleep, Zombie.
<br>

**pstree -h** outputs running processes and their ancestors.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/pstree%20-h.png">
<br>

**procfs** is a file system that allows to receive access to info about sys processes from core.
<br>

**lscpu** command outputs processor info.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/processor.png">
<br>

**ps -gua** outputs process info with group, user and arguments.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/gua.png">
<br>

**ps -e**
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/ps%20-e.png">
<br>

**ps -u username**
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/ps%20-u.png">
<br>

**ps -el**
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/ps%20-el.png">
<br>

**top** command outputs processes in real time.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/processes.png">
<br>

**top -u username** outputs processes in real time with username parameter.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/more%20processes.png">
<br>

Command **nice** and **renice** sets and resets process priority.
<br>

Command **kill parameters**: -91 kills all available processes, -l 11 sends 11 to signal, -L. Sends signals to processes.
<br>

**jobs**, **bg** and **fg** are commands to option background processes.
<br>

**nohup** runs a command immune to hangups, with output to a non-tty.
<br>

**Part 2**
<br>

**sudo apt-get install openssh-server** installs openssh server.
<br>
**sudo ufw allow ssh** allows ssh connection. 
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/allow.png">
<br>
Connected from host
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/ssh_win.png">
<br>

The most simple **ssh security** upgrade is to change default **port 22** to any other.
<br>
**nano /etc/ssh/sshd_config** runs text editor where one should change port 22 > port 22000 (for instance 22000).
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m5/task5.3/images/ch_port.png">
<br>

**Port forwarding** implements: ssh -L 22000:192.168.0.106:22 10.0.2.15
	