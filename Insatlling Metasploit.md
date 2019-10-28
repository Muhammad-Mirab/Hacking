# Peneterator-Panter
virtual hacking learning

so, we're going to learn HOW TO HACK ANDROID DEVICES WITH METASPLOIT

First of all you need to install Metasploit_Framework and the tutorial is here!

first open the terminal.

![Open the Terminal](https://cdn1.imggmi.com/uploads/2019/10/28/0cbf3216fe1180e733c894d30518b697-full.png)

execute `sudo -s` and then type your Password.then execute `apt-get update && apt-get upgrade`.

![sudo -s](https://cdn1.imggmi.com/uploads/2019/10/28/00d525c347919f1463d6de338f9a9f11-full.png)

and

![apt-get update && apt-get upgrade](https://cdn1.imggmi.com/uploads/2019/10/28/9fbe6ac6da88f4b617032b92d848a8fa-full.png)

then `curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall` run this command and wait to be done.
then `chmod 755 msfinstall` and `./msfinstall` then you have to get output like this:
> Adding metasploit-framework to your repository list..OK
> Updating package cache..OK
> Checking for and installing update..
> Reading package lists… Done
> Building dependency tree       
> Reading state information… Done
> The following NEW packages will be installed:
>   metasploit-framework
> 0 upgraded, 1 newly installed, 0 to remove and 122 not upgraded.
> Need to get 169 MB of archives.
> After this operation, 397 MB of additional disk space will be used.
> Get:1 http://downloads.metasploit.com/data/releases/metasploit-framework/apt lucid/main amd64 metasploit-framework amd64
4.17.35+20190105104028~1rapid7-1 [169 MB]
> Fetched 169 MB in 4s (42.3 MB/s)               
> debconf: delaying package configuration, since apt-utils is not installed
> Selecting previously unselected package metasploit-framework.
> (Reading database … 34892 files and directories currently installed.)
> Preparing to unpack …/metasploit-framework_4.17.35+20190105104028~1rapid7-1_amd64.deb …
> Unpacking metasploit-framework (4.17.35+20190105104028~1rapid7-1) …
> Setting up metasploit-framework (4.17.35+20190105104028~1rapid7-1) …
> update-alternatives: using /opt/metasploit-framework/bin/msfbinscan to provide /usr/bin/msfbinscan (msfbinscan) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfconsole to provide /usr/bin/msfconsole (msfconsole) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfd to provide /usr/bin/msfd (msfd) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfdb to provide /usr/bin/msfdb (msfdb) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfelfscan to provide /usr/bin/msfelfscan (msfelfscan) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfmachscan to provide /usr/bin/msfmachscan (msfmachscan) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfpescan to provide /usr/bin/msfpescan (msfpescan) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfrop to provide /usr/bin/msfrop (msfrop) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfrpc to provide /usr/bin/msfrpc (msfrpc) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfrpcd to provide /usr/bin/msfrpcd (msfrpcd) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfupdate to provide /usr/bin/msfupdate (msfupdate) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/msfvenom to provide /usr/bin/msfvenom (msfvenom) in auto mode
> update-alternatives: using /opt/metasploit-framework/bin/metasploit-aggregator to provide /usr/bin/metasploit-aggregator >(metasploit-aggregator) in auto mode
> Run msfconsole to get started
and now by executing `msfconsole` command you have to see sth like this:

![Msfconsole](https://cdn1.imggmi.com/uploads/2019/10/28/f65c76f156b3e0c9281ee8ce31fe5404-full.png)

And now it's mostly done!
