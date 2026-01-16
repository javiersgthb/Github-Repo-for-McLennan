# SSH Configuration

en
sh ip ssh
!
!
!
!
conf t
ip domain-name cisco.com
crypto key generate rsa
username *username* secret *password*
line vty 0 15
transport input ssh
login local
exit
ip ssh version 2
exit
wr mem
