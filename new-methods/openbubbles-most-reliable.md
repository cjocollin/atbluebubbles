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
    visible: false
---

# 💭 OpenBubbles (Most Reliable)

{% hint style="warning" %}
While using the Beepserv, it is recommended that you use a spare Apple ID.

* Apple has been cracking down on _\[their own]_ users for using Beeper/Beeper Mini. It even caused Beeper to remove iMessage **completely** from their platform.
{% endhint %}

{% hint style="info" %}
**OpenBubbles is a fork of the popular app, BlueBubbles! It offers in-app iMessage registration with the help of a Mac or a Relay server on an iPhone!**

It also supports emoji reactions, text styles, effects, Facetime, FindMy, Photo Album sharing, etc!

This is the safest method I've seen and have been using and I know others would enjoy this as much as I do!
{% endhint %}

***

{% hint style="warning" %}
**Requirements for OpenBubbles:**

* iPhone 6S and above _**(TrollStore compatible)**_
* Android Device
* TrollStore
  * [Check out the full guide for TrollStore here](https://ios.cfw.guide/installing-trollstore/)
* Sideloading application
  * [Check out Sideloadly](https://sideloadly.io/)
  * [Check out AltStore](https://altstore.io/)
* Beepserv Installer IPA
  * [Download the IPA here](https://cdn.discordapp.com/attachments/1130641573244317736/1230994423958077450/beepserv_installer_v0.1.ipa?ex=6628d1a5\&is=66278025\&hm=0cf79fea9ed75f645f2a37a2317c3ee31ba573aa475d6ab831d0dce3c2566546&)
* ValidationRelay TIPA
  * [Download the TIPA here](https://github.com/JJTech0130/ValidationRelay/releases)
    * _**This is only for people who are already jailbroken and want to use TrollStore for installation**_
* Beeper Mini _**(for iMessage)**_
  * [Download the APK here (Beeper)](https://mini.beeper.com/Beeper_Mini_v1.2.58.apk)
    * _**This file download link may go down at anytime since the Beeper Mini page has been deleted from their website**_
  * [Download the APK here (Web Archive)](https://web.archive.org/web/20240329133435/https://mini.beeper.com/Beeper_Mini_v1.2.58.apk)
  * [Download the APK here (Media Fire)](https://www.mediafire.com/file/u1r73jp6z9vjshx/Beeper_Mini_v1.2.58.apk/file)
* A spare/throw-away Apple ID
  * [Make a new Apple ID here](https://appleid.apple.com/account)
{% endhint %}

## Installing TrollStore:

Your device needs to be compatible for this method.

For full guides on specific iPhones and iOS, please check [Installing TrollStore Guide](https://ios.cfw.guide/installing-trollstore/) and continue with this guide.

## Install Beepserv without a Jailbreak:

<details>

<summary>Installing Beepserv Installer and registering your numberO</summary>

1. Install Sideloadly or AltStore _(The link is posted above with the requirements)_&#x20;
2. After setting up Sideloadly or AltStore, you'll need to sideload the Beepserv Installer IPA onto your iPhone _**(An Apple ID is required to sideload)**_
3. Turn off **iMessage**
4. Open the Beepserv Installer app to install and enable Beepserv
5. Once you have your **Registration Code**, download the Beeper Mini _**(for iMessage)**_ app on your Android device _(The link is posted above with the requirements)_&#x20;
6. Open Beeper Mini and it should prompt you to enter your **Registration Code**
7. Once you entered your Registration Code, it will proceed to ask you to enter your Apple ID info
   * Please use your spare/throw-away Apple ID for safety of your Apple account
8. You should be able to use iMessage with Beeper Mini and start texting your friends or family!

</details>

## Install with TrollStore if already Jailbroken:&#x20;

<details>

<summary>Installing with TrollStore if already Jailbroken</summary>

1. Install TrollStore on your own
2. Turn off iMessage
3. Sideload the ValidationRelay TIPA _(The link is posted above with the requirements)_
4. Once you have your **Registration Code**, download the Beeper Mini _**(for iMessage)**_ app on your Android device _(The link is posted above with the requirements)_&#x20;
5. Open Beeper Mini and it should prompt you to enter your **Registration Code**
6. Once you entered your Registration Code, it will proceed to ask you to enter your Apple ID info
   * Please use your spare/throw-away Apple ID for safety of your Apple account
7. You should be able to use iMessage with Beeper Mini and start texting your friends or family!

</details>

### Using your Spare/Throw-Away Apple ID with BlueBubbles/AirMessage:

<details>

<summary>Using BlueBubbles/AirMessage with your spare/throw-away Apple ID</summary>

1. Add your spare/throw-away Apple ID to your Mac
2. Set up iMessage for this Apple ID and accept the **"new number"** being added to your spare/throw-away Apple ID
3. Test it by sending iMessage texts to your number or to your friends or family
4. If successful, you should be able to use your BlueBubbles/AirMessage server to send iMessage texts on your Android or Web
   * _Please don't delete Beeper Mini from your Android device, as it could mess up this process. You can disable notifications from Beeper Mini on your Android device._

</details>

***

## Troubleshooting Options

{% hint style="info" %}
These troubleshooting options came from the [Beepserv Installer GitHub](https://github.com/alfiecg24/beepserv-installer) page.
{% endhint %}

<details>

<summary>Why am I stuck at "Exploiting kernel"?</summary>

This is a common issue with the kfd exploit. Simply reboot your device and try again.

</details>

<details>

<summary>Why can I not open/see TrollStore after a successful installation?</summary>

During installation, you will have installed a persistence helper. Open your persistence helper and press "refresh app registrations" to fix TrollStore not being able to be opened.

</details>

<details>

<summary>Why am I getting an error about not being able to patchfind?</summary>

Either:

* You're on a non-MacDirtyCow supported version, and are not connected to the internet, or;
* You're using a Yellow iPhone 14 or Yellow iPhone 14 Plus on iOS 16.3 (20D50), in which case, [open a GitHub Issue](https://github.com/alfiecg24/beepserv-installer/issues/new/choose).

Additionally, if a file exists at `/beepserv-installer.app/kernelcache`, the installer will use that file instead of downloading the kernelcache. This can be useful if you have a slow or unreliable internet connection, or happen to have a device and version combination that has no public kernelcache available.

</details>

<details>

<summary>Why does the installer say "failed to install persistence helper" using the indirect method?</summary>

The indirect method is not perfect, and sometimes it will fail to install the persistence helper. If this happens, simply shut down your device, turn it back on, and try again. If you repeatedly have issues with the same app, try using a different app.

</details>

***

## Additional Links and Guides:

[Thanks to the pypush Discord server!](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139) :smile:

* Relay app (for TrollStore users): [https://github.com/JJTech0130/ValidationRelay](https://github.com/JJTech0130/ValidationRelay)&#x20;
* Installer source code: [https://github.com/alfiecg24/beepserv-installer](https://github.com/alfiecg24/beepserv-installer)&#x20;
* Combined repo with build script: [https://github.com/alfiecg24/Beeper](https://github.com/alfiecg24/Beeper)
* TrollStore Guide: [https://github.com/iOSGuide/installing-trollstore](https://github.com/iOSGuide/installing-trollstore)

***

### Credits: [pypush, jjtech and Alfie](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139)
