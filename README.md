
# Setup (www.centerfree.cf)                                                                                   

> Note : uninstall and update Applications can use APT or synaptic package manager

![](setup.gif) 



Step by step Create Repository Portable (ONLY for linux Beefree OS)
* Clone setup repository
> git clone https://github.com/macrolinux/setup
* Entering directory
>cd setup
* Change file mode bits
>sudo chmod 777 *
* Download app with dependencies (If your application is not in the repository, this step is not necessary)
>packin package
* clean clears out the local repository of retrieved package files.
> apt clean
* Create app.iso MUST with aptoncd (telolet version)
>https://github.com/macrolinux/setup/blob/master/aptoncd_0.1.98%2Btelolet_all.deb
* Customize free.xml (change vendor,product, version, location, etc )
* Change wesnoth with app your name in setup.sh
> in line DEBIAN_FRONTEND=gnome apt install -y wesnoth
* Create installer (.run) with Cross Platform BitRock InstallBuilder
>https://installbuilder.bitrock.com/download-step-2.html
* Get a Free License installbuilder for your Open Source Project (optional)
>https://installbuilder.bitrock.com/open-source-licenses.html

![](installersby_tiny.png)
