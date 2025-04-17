# cloud-prgram-5
go to windows+r and type //cse
copy files of ubuntu20.iso and winscp.exe to localdisk
now open virtual box and delete the existing the instance
click new and choose the ubuntu20.iso , create username and password
ok
now go to settings 
-> general-> advanced-> shared documents - bidirectional
                      -> Drag n drop - bidirectional
->network -> atttached to -> bridge adaptor (if u r using lan)
          ->promiscous mode -> allow all
storage -> controller ide -> add ubunto20.iso and choose that
click ok
now launch the insatnce and install ubuntu and create the same username and the password

now go to terminal and  run
apt install openssh-server
apt install net-tools
ifconfig
u get the ip address of the machine copy that 
open the winscp app and click on new tab and add the ip adress and the username and password
now conect and u will have both the windows and vmachines file explorer and now u can easily share the file between the host and the virtual machine
