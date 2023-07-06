# Windows 10/11 Gaming Optimization Batch Script
## **This script should be safe to run since it can revert everything it changed, however still <ins>_use it at your own risk_<ins/>**

Simple Batch that does optimizations like disabling Tasks, Services and much more while Gaming.<br/>
All changes will only be temporary you also have the option to revert everything.

While this works on both Windows 10/11 it's mostly tweaked for 10 since that is the version i'm using. 

There are currently 2 Versions available:<br/>
Gaming Optimization.bat - Needs to be personalized by the User since it's meant to have way more features.<br/>
Gaming Optimization Universal.bat (Recommended for most People) - Version that doesn't need any changes from the User just download & run.

Main Focus will probably go to the Universal Version since it's the one i personally use myself.

Here is a list of things that the optimization can/will do:<br/>

- You can change the Priority from Games to whatever you like
- Killing unessesary tasks
- Disabling useless Services (to free up ram and maybe cpu usage)
- Lower the Priority of some Processes (to give other processes more room)
- Clears the Recycle Bin, Temp, Prefetch and SoftwareDistribution Download Folders (to free up space)
- Disables HPET (High Precision Event Timer)
- Changes Powerplan
- Overclocks GPU (if MSI Afterburner is Installed and Profiles are set!)
- Flushes DNS (because it can)
- Disable DWM (Desktop Window Manager, currently Windows 10 only!)
- and more...

Programs/Tools recommended to be implemented (if needed):

- Intelligent standby list cleaner ([Recommended Settings](https://i.imgur.com/VzWXyA7.png))
- devcon.exe (only nessesary if you want to disable HPET, can be installed with [this](https://github.com/Drawbackz/DevCon-Installer))<br/>
- MSI Afterburner

It also has a Launcher integrated so you can launch your Games quick and optimize afterwards.<br/>
Also it has small Menus like the Tool and App Menu where you can add Programs by editing the Script.

This is just a Template so more Features like disabling more Task / Services, auto Overclocking with MSI Afterburner or Programs named above could be implemented.<br/>
Obviously you need to add games if you wanna use the Game Launcher.<br/>
There is a Test Menu you can enter from every select screen when you type test to test things when editing the Script.

In some Games like Left 4 Dead, Raft, Dead by Daylight and even Cemu Emulator it helped reducing input lag and improved fps a little.
This isn't a Game Changer just simple optimization so the System will have less work.

Here are my Old System Specs i made the tests on:<br/>

- AMD A8 5600k (OC on 4.5 GHz)
- 4x4 GB DDR3 1600MHz
- Nvidia GeForce GTX 960 2GB (Core Clock +200, Memory Clock +600)
- Asus A88XM-A Mainboard
- Windows 10 x64 Pro

Here is an 3DMark Advanced Time Spy Test (you won't see much of a difference exept for the OC):

Before:

- Time Spy Score: 2101 - Good
- Graphics score: 2165
- CPU Score: 1801

After (Highest Score made with A8 5600k & GTX 960 2GB):

- Time Spy Score: 2404 - Legendary
- Graphics Score: 2555 (overclocked)
- CPU Score: 1803
