**Task 4.1**
<br>

**First net: four workstations and one hub.**
<br>
Results: ping from PC4 to PC0, hub sends requests to all connected workstations.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Scheme1.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL1.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/PDU1.png">
<br>

**Second net: two subnets with two hubs.**
<br>
Results: ping from PC0 to Server0, similar result as previous net.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Scheme2.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL2.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL21.png">
<br>

**Third net: four worlstations with one switch.**
<br>
Results: ping from PC0 to PC1, request was sent only to receiver.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Scheme3.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL3.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/PDU3.png">
<br>

**Fourth net: two subnets with two switches.**
<br>
Results: ping from PC1 to PC4 through two switches, results is similar as previous net.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Scheme4.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL4.png">
<br>

**Fifth net: two subnets with two swithes, connected by router.**
<br>
Router requests interface option to switch port.
<br>
Results: ping from PC1 to PC4, request passed through router and reached only reciever.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Scheme5.png">
<br>
Router interfaces options.
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/Router_Conf.png">
<br>
<img src="https://github.com/HighLandner/DevOps_online_Kharkiv_2021Q1/blob/master/m4/task4.1/images/EL5.png">
<br>