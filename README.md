# ARP_Spoofing
1. input
- Device : current user network environment
- IP address : sender's ip address / target's ip address
2. output
- spoofed & sniffed packets
- Send attack packets to sender & target both : supported to attack 2 times per 1~6 random seconds (asynchronous attack)

# Command
- qmake
- make
- sudo ./ARP_S (device name) (sender's ip address) (target's ip address) (target's ip address) (sender's ip address) ...

# Reference
1. Find my ip & mac address : http://egloos.zum.com/hkpco/v/576721
2. Use header structures : https://github.com/korczis/libnet/tree/master/include/libnet
