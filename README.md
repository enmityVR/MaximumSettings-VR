Hello! This is the updated tutorial on how to install vr on maximumsettings.

-REQUIREMENTS-

You will need:
A Meta Quest headsset (i dont believe any other headsets are supported)
Access to your router settings
A subscription to maximumsettings (i hope this was obvious)

-ALVR INSTALLATION-

First of all, install ALVR from their github at https://github.com/alvr-org/ALVR/releases/
Currently, only ALVR v20.12.0 has been tested, but other versions should work.

-ALVR SETUP IN VR-

Now on your headset, open the Meta Quest Store and download ALVR, its free.
Go ahead and open ALVR on mxs, and your headset. in your headset, you should see XXXX.client, remember those numbers. The ip address is not important

-PORT FORWARDING-

Now its the (not so) fun part! Go to your router settings (normally found at 192.168.1.1, just type that in on your browser)
Now login to it if you need to (your login is normally on the router somewhere)
After you login, look for port forwarding. And find your headset. Once you do, Specify the ports 9943 to 9944 for both UDP and TCP, and save it.

-ALVR MXS SETUP-

Go to moonlight, and open ALVR, press on "add device manually" and enter the XXXX.client (fill in XXXX with the numbers you see in vr)
Now go to your headset and find your ip address (you can use a website like https://whatsmyip.com/)
After you have your ip, go back to moonlight, and enter the ip where ALVR asks for it. Then click save!

-STEAM SETUP-

First of all, download SteamVR. Once it installs, go to options, and then set the launch options "~/.steam/debian-installation/steamapps/common/SteamVR/bin/vrmonitor.sh %command%" (without the ")
Now you can go to alvr and press open SteamVR (it may not open properlly the first time, and you may need to restart mxs)
When you connect, you will notice the audio is coming out of moonlight (or no audio at all) please read the next section if this happens to you.

-FIX AUDIO-

If the audio isnt coming out of your headset, open your sofware manager, and download Pwvucontrol.
Now open it, and look for the game that doesnt have any audio (it must be open!)
Once youve found it, click on where it says default (or some other audio source) click it, and change it to the ALVR source.
Sadly, it seems you have to do this every time you open the game.

-FIX MIC-

You will need Pwvucontrol from the last section for this.
With your game open, go to the recording tab, and find your game.
where it says 'Default" (or any other audio source) click it, and change it to the ALVR Microphone
Sadly, it seems you have to do this every time you open the game

-KNOWN ISSUES-

Random SteamVR restarts - No idea why this happens, but it is rare. There is no fix
Random black windows - This is a SteamVR bug. Press Ctrl + ALT + Esc to clear them.
Stutters/Latency - This is an issue regarding your connection to the MaximumSettings datacenter, and probably cant be fixed, but possibly improved.


Please dm @enmityvr on Discord if this tutorial doesn't work for you. Have fun!
