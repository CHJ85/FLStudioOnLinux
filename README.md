# FLStudioOnLinux
An FL Studio installer for Linux that'll work on most distros without any extra hassle or tech knowledge.<br>
# Installation
1: Have your FL Studio installation (.exe) file ready.<br>
2: Run this command in the terminal: 
   <pre>bash -c &quot;$(curl -fsSL https://raw.githubusercontent.com/CHJ85/FLStudioOnLinux/refs/heads/main/FLStudioOnLinux)&quot;</pre>
   This will install all necessary dependencies including FL Studio itself.
# Recommendations
I recommand using the Wine version from WineHQ.org's repository, as it's the most up-to-date. If winehq-stable is not already installed on your system, the script will default to your distro's Wine package.<br>
The most stable version of FL Studio on Linux is 2024 (v24). Version 26 works great too, however it is still in beta. If you got tons of VST plugins and such, v24 is the way to go.
