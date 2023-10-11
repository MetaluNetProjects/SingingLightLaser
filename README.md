# SingingLightLaser

GroupeLAPS - 8 microphone triggered synths

### Download latest version of the app:

Goto https://github.com/MetaluNetProjects/SingingLightLaser

Click the "Code" button, click "Download ZIP".

Extract the ZIP to Documents/, remove "-main" at the end of the folder name, so it is now: /Users/groupelaps/Documents/SingingLightLaser.

### Pd externals to install:

- moonlib
- zexy
- ggee
- motex
- iemlib

Start Pd by opening 0_SingingLightLaser.pd, or start Pd and use menu File/Open.

### open stage control

- download and install latest version at https://openstagecontrol.ammd.net/download/  
(version used at writing time: 1.25.5)
- start open-stage-control
- configure "send" setting: localhost:18080
- choose session file in the "load" setting:  
/Users/groupelaps/Documents/SingingLightLaser/OSCremote/teleco-OSC.json
- start the session ('play' button)
- now you can access the session from any web client by entering URL http://YOUR_HOST_IP:8080 (replace YOUR_HOST_IP with the ip of the computer running open-stage-control). Open-stage-control also offers a QR code that links to the URL.  
If your client's screen is too small or too large, you can specify the zoom factor in the URL, e.g: http://192.168.0.98:8080?zoom=0.7 


(c) Antoine metalu.net 2023 