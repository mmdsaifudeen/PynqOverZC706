# PynqOverZC706
This project developes Pynq software system for ZC706

Prerequisites:=   Ubuntu 16.04,Vivado 2018.2 ,Xilinx SDK 2018.2 , Petalinux 2018.2

1. check out "v2.3" at Pynq directory

2. move "ZC706" folder into "pynq/boards/" location

3. Source vivado,xsdk and petalinux.

4. go into "sdbuild"

5. do " sh scripts/setup_host.sh "

6. do make "make BOARDS=ZC706"
