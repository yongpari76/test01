# test01

## root@docker1:~# ls /sys/class/net
docker0  enp0s3  enp0s8  lo

```
root@docker1:~# ip link 
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default qlen 1000 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00 
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP mode DEFAULT group default qlen 1000 
    link/ether 08:00:27:82:47:07 brd ff:ff:ff:ff:ff:ff 
3: enp0s8: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP mode DEFAULT group default qlen 1000 
    link/ether 08:00:27:98:08:c6 brd ff:ff:ff:ff:ff:ff 
4: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default  
    link/ether 02:42:3e:e2:1e:c2 brd ff:ff:ff:ff:ff:ff
    
    
 - Network Interface 목록 확인
```
root@docker1:~# ls /sys/class/net
docker0  enp0s3  enp0s8  lo

root@docker1:~# ip link 
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default qlen 1000 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00 
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP mode DEFAULT group default qlen 1000 
    link/ether 08:00:27:82:47:07 brd ff:ff:ff:ff:ff:ff 
3: enp0s8: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP mode DEFAULT group default qlen 1000 
    link/ether 08:00:27:98:08:c6 brd ff:ff:ff:ff:ff:ff 
4: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default  
    link/ether 02:42:3e:e2:1e:c2 brd ff:ff:ff:ff:ff:ff
```
