**Task 6.2**
<br>

**DHCP** using **ISCDHCP**.
<br>
Configurating **/etc/dhcp/dhcp.conf** at both clients` workstations.
<br>
```
auto enp0s3
iface enp0s3 dhcp
```
<br>

Configurating **/etc/init.d/isc-dhcp-server** at server`s workstation.
<br>
```
default-lease-time 7200;
max-lease-time 43200;

subnet 192.168.0.0 netmask 255.255.255.0 {
 range 192.168.0.100 192.168.0.200;
 option routers 192.168.0.1;
 option domain-name-servers 192.168.0.1;
}
```
<br>
where default-lease-time is sevrer rent time if client didn`t ask for another, range - available address range, option router and option DNS - is server`s address.
<br>
