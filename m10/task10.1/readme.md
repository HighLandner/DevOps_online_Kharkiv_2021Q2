**Task10.1/Ansible**

Before starting first step is to install python and ansible itself.
All task will be completed on AWS instances.
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
ansible--version
sudo apt install python-pip
```
<br>

Create file hosts.txt and add ansible user:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/host_ping1.png" >
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/host_ping2.png" >
<br>

**Inventory, shell, changes and removement:**
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/inventory_list.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/shell.png" >
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/change_1.png" >
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/change_2.png" >
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/remove.png" >
<br>
 
**Playbooks**
The first one:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/playbook1.png" >
<br>

The second one:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/playbook2.png" >
<br>

The third one:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/playbook3.png" >
<br>

Result:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/res.jpg" >
<br>

The fourth one:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/playbook4.png" >
<br>

The fifth one:
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m10/task10.1/images/playbook5.png" >
<br>