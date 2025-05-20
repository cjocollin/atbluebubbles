---
hidden: true
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 💭 Installing relayserver (Jailbroken)

Relayserver is a jailbreak tweak that enables your iPhone to act as a validation data provider for OpenBubbles.

{% hint style="warning" %}
Requirements:

* 64-bit iOS device _**(Needs to be jailbroken)**_&#x20;
  * Visit [ios.cfw.guide](https://ios.cfw.guide) for instructions to jailbreak your device.
  * iOS 10 or newer
  * iPhone 5s or newer
    * iPad 5th gen or newer
    * iPad Mini 2nd gen or newer
    * iPad Air or Pro
    * iPod Touch 6th gen or newer
{% endhint %}

1. Log out entirely of
   1. iCloud:
      1. Open Settings
      2. Select your name at the top (If it instead says `Sign in` you are already signed out)
      3. Scroll down to and select `Sign Out`
      4. Follow the prompts
   2. iMessage:
      1. Open Settings
      2. Scroll down to and select `Messages`&#x20;
      3. Flip the `iMessage`  switch to off
   3. FaceTime:
      1. Open Settings
      2. Scroll down to and select `FaceTime`&#x20;
      3. Flip the `FaceTime` switch to off
   4. App Store:
      1. Open the App Store
      2. Select the profile image in the upper right
      3. Scroll down to and select `Sign Out`&#x20;
2. Installing Filza File Manager
   1. Open your package manager of choice (Cydia, Sileo, etc.)
   2. Search for `Filza File Manager`&#x20;
   3. If you can't find it, ensure the BigBoss repository is in sources
      * If not add `http://apt.thebigboss.org/repofiles/cydia/`&#x20;
   4. Install `Filza File Manager` (For Cydia: on the page for the app, select Install and then Confirm)
3. Installing relayserver
   1. Visit one of the following links in Safari on the iPhone based on rootful vs rootless jailbreak:
      * (iOS 10 - 14 rootful): [https://github.com/OpenBubbles/relayserver/releases/download/0.0.2/dev.copper.relayserver\_0.0.1-6+debug\_iphoneos-arm.deb](https://github.com/OpenBubbles/relayserver/releases/download/0.0.2/dev.copper.relayserver_0.0.1-6+debug_iphoneos-arm.deb)
      * (iOS 15+ rootless): [https://github.com/OpenBubbles/relayserver/releases/download/0.0.2/dev.copper.relayserver\_0.0.1-8+debug\_iphoneos-arm64.deb](https://github.com/OpenBubbles/relayserver/releases/download/0.0.2/dev.copper.relayserver_0.0.1-8+debug_iphoneos-arm64.deb)
   2. Select to `Open with Filza`
   3. Click `Install`&#x20;
4. Retrieving your device code
   1. Open Filza (from the home screen)
   2. Browse to `/var/mobile/config.json`&#x20;
      1. Press the back button in the upper left until it disappears
      2. Select `var` (May have to scroll down)
      3. Select `mobile` ^^
      4. Select `config.json` ^^
   3. Your device code will be enclosed in double quotes (") following `"code":` \
      Example: `"code":"ABCD-EFGH-IJKL-12BZ"` would be `ABCD-EFGH-IJKL-12BZ`
5. Your device code can now be used to activate OpenBubbles (include dashes)
6. Your device must remain powered on and connected to the wifi

{% hint style="info" %}
**Keeping the device connected**

Apple is very conservative with when the wifi adapter is able to run, and will often put it to sleep as a result of inactivity.  This is bad as our iOS device needs to be acceptable when Apple decides that our registration has expired.  Here are some methods for keeping the device online:

1.
{% endhint %}

