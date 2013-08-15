1) Login to Console.amazon.com
2) Launch instance
3) Micro-instance, free version
4) download .pem file
5) note dns ip of instance
6) chmod 600 <abcd>.pem
7) ssh -i demo.pem  <ec2-user>@<ec2-54-226-122-128.compute-1.amazonaws.com>



8) Node installer
9) MySQL installer
10) Tomcat installer


11) Puttygen.exe to create .ppk file (private key)
12) WinSCP uses ppk file
13) MySQL client uses pem file





Virtual machine setup
1) download virtual oracle box : https://www.virtualbox.org/wiki/Downloads
2) get bootable iso file for centOS
3) launch oracle VM virtual box
4) Start new instance
5) ram >=2gb
6) create virtual hard-drive now
7) VMDK
8) size dynamic
9) "File location and size tab" "disk size 20GB"
10) "VM location non C folder"
11) point to iso file
 
