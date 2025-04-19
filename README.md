# cloud-prgram-5<br />
go to windows+r and type //cse<br />
copy files of ubuntu20.iso and winscp.exe to localdisk<br />
now open virtual box and delete the existing the instance<br />
click new and choose the ubuntu20.iso , create username and password<br />
ok<br />

now go to settings <br />
-> general-> advanced-> shared documents - bidirectional<br />
                      -> Drag n drop - bidirectional<br />
->network -> atttached to -> bridge adaptor (if u r using lan)<br />
          ->promiscous mode -> allow all<br />
storage -> controller ide -> add ubunto20.iso and choose that<br />
click ok<br />
now launch the insatnce and install ubuntu and create the same username and the password<br />

now go to terminal and  run<br />
apt install openssh-server<br />
apt install net-tools<br />
ifconfig<br />
u get the ip address of the machine copy that <br />
open the winscp app and click on new tab and add the ip adress and the username and password<br />
now conect and u will have both the windows and vmachines file explorer and now u can easily share the file between the host and the virtual machine<br />
