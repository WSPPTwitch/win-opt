<div align="center">

# <text text-anchor="middle" dominant-baseline="middle" x="50%" y="50%" class="text" style="fill:#000000;" stroke="#none" stroke-width="1" >⊹ win-opt // Windows Performance & Privacy Manual ⊹</text>

</div>

<p align="center">
<p align="center">A Ground-Up Windows Performance Manual; less latency, higher fps, better privacy, less bloatware/spyware from Microsoft.</p>
<p align="center"> ⋆⊱༻𖥸༺⊰⋆ Will appreciate a star! ⋆⊱༻𖥸༺⊰⋆ </p>

## 𖤐 **READ FIRST** 𖤐
### If you had a system breaking/ransomware/deep root virus on your previous install, I ***HIGHLY*** recommend you install [TronScript](https://old.reddit.com/r/TronScript) as it will optimize and disinfect your old Windows Install.

## 01. // ⟢ Privacy & Telemetry ⟢

### [Privacy.sexy](https://privacy.sexy/)
Most stuff will be done through here, ofc you can always use Chris Titus' Winutil to do this kind of stuff (might be not possible - I do not have personal experience in it).
Download via the Windows/Linus/macOS button in bottom left of the website.

**I WILL NOT GO OVER ALL OPTIONS TO KEEP CONSISTENCY, IF YOU FEEL LIKE SOMETHING DISABLES WHAT YOU USE, OR YOU'RE LOOKING FORWARD TO DISABLING SOMETHING SPECIFIC AND I DON'T COUNT IT IN, YOU MUST DO IT YOURSELF.**

### 1.1. ᛝ Disable OS Data Collection ᛝ
Speaks for itself. Here's a list of options to disable:
- **(unfold)** Disable app access to personal info
  * **Dependant on use**
  - Disable app access to phone
  - Disable app access to Bluetooth devices
  - Disable app voice activation
  - Disable app access to location
  - Disable app access to motion activity
  - Disable app access to radios
- Disable Customer Experience Improvement Program
- Disable Application Experience data collection
- Disable Windows telemetry and data collection
- Disable connectivity checks
- Disable Windows search data collection
- Disable targeted advertisements and marketing
- Disable biometrics
- Disable Windows Insider Program
- Disable Recall
- Disable cloud-based speech recognition
- Opt out of Windows privacy consent
- Disable Windows feedback collection
- Disable typing feedback
- Disable text and handwriting data collection
- Disable app launch tracking
- Disable automatic map downloads
- Disable game screen recording

### 1.2. ᛝ Configure Programs ᛝ
Check all options.

### 1.3. ᛝ Remove Bloatware ᛝ
Removes unwanted programs that boot up in the background, take up minimal space or continuously run as background tasks.
**!! DO ONLY AFTER INSTALLING A SELECTED BROWSER SINCE IT WILL INCLUDE DELETING THE BUILT-IN ONE !!**
- **(unfold)** Remove Windows Apps
  * **Dependant on use**
  - Remove 3D modeling apps
  - Remove MSN apps
  - Remove Phone apps
  - Remove "App Connector" app
  - Remove "Get Help" app*
  - Remove "Microsoft Tips" app
  - Remove "Microsoft Messaging" app
  - Remove "Mixed Reality Program" app
  - Remove "Feedback Hub" app
  - Remove "Windows Maps" app
  - Remove "Microsoft People" app
  - Remove "Mobile Plans" app
  - Remove "Microsoft Solitaire Collection" app
  - Remove "Microsoft Sticky Notes" app
  - Remove "Mail and Calendar" app
  - Remove "Movies & TV" app
  - Remove "Skype" app
  - Remove "GroupMe" app
  - Remove "Microsoft To Do: Lists, Tasks & Reminders" app
- Remove OneDrive
- Remove Edge
- **(unfold)** Disable built-in Windows Features
  * **Dependant on use**
  - Disable Hyper-V virtualization features
  - Disable "Direct Play" feature
  - Disable "Internet Explorer" feature
  - Disable "Scan Management" feature
  - Disable "Windows Fax and Scan" feature
- Remove Windows Copilot
- **(unfold)** Disable non-essential services
  - Disable Downloaded Maps Manager
  - Disable Microsoft Retail Demo
  - Disable Messaging Service
  - Disable Windows Push Notifications
- Remove "Meet Now" icon from taskbar

### 2.1. ☆ Disable Text & Image generation ☆
In the search bar/settings search bar, search up: ***Text and image generation features and apps privacy settings***. Click on the result matching the phrase, and disable **Text and image generation**.

### 2.2. ☆ Disable App Diagnostics ☆
In the search bar/settings search bar, search up: ***App Diagnostics***. Click on the result matching the phrase, and disable **App diagnostic access**.

### 2.3. ☆ Disable Inking & typing personalization ☆
Go to settings, ***Privacy & Security***, and navigate to Inking & typing personalization. There, turn Custom inking and typing dictionary **off**.


## 02. // ⟢ Gaming & Latency settings ⟢
These settings are focused mainly on boosting your game performance, getting less stutters and lowering your latency

### 1.1. ₊⊹ Turn on Game Mode ₊⊹
In the search bar/settings search bar, search up: ***Game Mode***. Click on the result matching the phrase, and turn **Game Mode** on.

### 1.2. ₊⊹ Turn on HAGS (Hardware-Accelerated GPU Scheduling) ₊⊹
In the search bar/settings search bar, search up: ***Graphics Settings***. Click on the result matching the phrase, Unfold **Advanced graphics settings** and turn ***Hardware-Accelerated GPU Scheduling*** on.

### 1.3. ₊⊹ Turn Off Mem. Integrity ₊⊹
In the search bar/settings search bar, search up: ***Device Security***. Click on the result matching the phrase, click **Core isolation details**, and turn **Memory integrity** off.

### 1.4. ₊⊹ Turn On High Perf. Plan ₊⊹
In the search bar/settings search bar, search up: ***Control Panel***. Click on the result matching the phrase, and once opened navigate to **Hardware and Sound -> Power Options**, there click Show Additional Plans and select **High Performance**

### 1.5. ₊⊹ Update Your GPU Drivers ₊⊹

⁠♡ **NVIDIA Drivers** ⁠♡
1. Go to the [official NVIDIA website for drivers](https://www.nvidia.com/en-us/drivers/) (or use the NVIDIA app). Select your product category, series (e.g., a 1660 is 16 Series, a 4070 is 40 Series), product, and operating system.
2. Download the LATEST Game Ready Driver (GRD is recommended for gaming; Studio Drivers prioritize stability for video editing).
3. Open the .exe file (it will have a name like 551.86-win-xxxxx...).
4. Keep the default extraction path and click OK.
5. Once the extraction finishes, the actual driver installer will open. Choose whether you want the driver only or the driver + NVIDIA app.
6. Proceed with the Express installation.
Your display and audio may flicker or turn off for a few seconds during installation as display drivers restart. This is completely normal.
7. Restart your system once finished.

⁠♡ **AMD Drivers** ⁠♡
1. Go to the [official AMD website for drivers](https://www.amd.com/en/support/download/drivers.html). You can download the AMD Auto-Detect tool (Adrenalin software) or manually select your GPU series.
2. Download the LATEST driver for your GPU.
3. Open the downloaded .exe file.
4. Follow the installation prompts and choose Express/Standard install.
Your display and audio may flicker or turn off for a few seconds during installation as display drivers restart. This is completely normal.
5. Restart your system once finished.

### 1.6. ₊⊹ GPU Control Panel Tweaks ₊⊹

♡ **NVIDIA Control Panel** ♡
Manage 3D Settings → Global Settings:
- Low Latency Mode: Ultra (or On if game doesn't support Reflex) [OFF usually gives higher fps at the cost of latency]
- Max Frame Rate: Set to your monitor refresh -3 (e.g., 165Hz → 162 FPS cap)
- Power Management: Prefer maximum performance
- Texture Filtering - Quality: Performance
- Threaded Optimization: On
- Vertical Sync: Off

♡ **AMD Adrenalin** ♡
Gaming → Graphics:
- Radeon Anti-Lag: Enabled on lower fps than hz
- Radeon Boost: Disabled (unless you really don't care about quality and have no fps)
- Radeon Chill: Disabled (or set min=max for cap)
- Wait for Vertical Refresh: Off


## 03. // ࣪ ִֶָ☾. Tips & Recommendations ࣪ ִֶָ☾.

### 𑁍 Browser & Extension Recommendations 𑁍

### ***Speed, privacy, anti-tracker & adblock*** - [Brave](https://brave.com/)
### ***Independent, strong privacy & privacy customization, alternative to google*** - [Firefox](https://www.firefox.com/en-US/) ([arkenfox](https://github.com/arkenfox/user.js) - privacy tweak)
### ***Privacy focused, open source, opposing fingerprinting, Tor browser fork (w/o Tor network)*** - [Mullvad browser](https://mullvad.net/en/browser)
-=-=-=-=-=-=-=-
### ***The ultimate adblocker; open-source, professional grade content blocking with being easy on your CPU and RAM*** - [uBlock](https://github.com/gorhill/uBlock) ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)), ([Chrome](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh?hl=en))
### ***Open-source and open API for skipping sponsor segments in YouTube videos*** - [SponsorBlock](https://sponsor.ajay.app/) ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/)), ([Chrome](https://chromewebstore.google.com/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone))


### ⚠︎ Antivirus / Anti-malware programs ⚠︎

### ***Malware & malicious program detector, can detect rootkits and other viruses (need paid premium to serve as an active antivirus, free version is a virus detector)*** - [Malwarebytes](https://www.malwarebytes.com/)
### ***Active anti-virus, users recommend purchasing a yearly subscription key on unofficial sites*** - [ESET](https://www.eset.com/us/)
### ***File inspector with over 70 av scanners and URL/domain blocklisting services*** - [VirusTotal](https://www.virustotal.com/gui/home/upload)


### ᯽ General Privacy ᯽
### ***Encrypted Email / Deleted after 1 Year of inactivity*** - [Proton Mail](https://proton.me/mail)
### ***Encrypted Email / Deleted after 6 mo. of inactivity*** - [Tuta](https://tuta.com/)
### ***Encrypted Messenger for All Platforms*** - [SimpleX](https://simplex.chat/)
### ***Fingerprinting test*** - [CreepJS](https://abrahamjuliot.github.io/creepjs/)
### ***Email breach monitor*** - [haveibeenpwned](https://haveibeenpwned.com/)
### ***Password breach monitor*** - [haveibeenpwnedpasswords](https://haveibeenpwned.com/Passwords)

### 𖤝 VPNs 𖤝
### ***Free, unlimited, Wireguard (kill switch)*** - [1.1.1.1](https://one.one.one.one/) ([Config gen](https://colab.research.google.com/drive/1fomBbh0mRxpVoGAY5gYT5zPBnFKsLV9o?usp=sharing))
### ***Free & Paid, unlimited, No Torrenting w/ free plan*** - [ProtonVPN](https://protonvpn.com/)
### ***Free & Paid, 10GB Monthly for free, No torrenting w/ free plan*** - [Windscribe](https://windscribe.com/)
### ***Paid, unlimited*** - [AirVPN](https://airvpn.org/)
### ***Paid, no-log, no port forwarding*** - [Mullvad VPN](https://mullvad.net/en)
### ***Paid, no-log, no port forwarding*** - [IVPN](https://www.ivpn.net/en/)

