---
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

# ☁️ iCloud Contacts on Android

Ever want your iCloud Contacts on Android?  Well, it's possible!

{% hint style="warning" %}
Requirements:

* DAVx⁵
  * Available via Google Play for $6.49 - [Link](https://play.google.com/store/apps/details?id=at.bitfire.davdroid)
  * Available via F-Droid for free - [Link](https://f-droid.org/packages/at.bitfire.davdroid/)
* App-Specific Password generated at [account.apple.com](https://account.apple.com)
{% endhint %}

1. Open DAVx⁵
2. Press next (the right arrow in the bottom right)
3. Select "I don't need tasks support." and press next
4. Select "All of the below"
5. Press allow on the popups
6. Press next&#x20;
7. Turn on the switch next to "Regular sync intervals"
8. Press allow on the popup
9. Press next
10. Select an option about donating and press the check mark
11. Press add account
12. Choose "Advanced login"
13. Press "Continue"
14. Fill in the boxes
    1. Base URL: https://contacts.icloud.com/
    2. User name: Your Apple Account email
    3. Password: The App-Specific Password you generated (Your normal password WILL NOT WORK)
15. Press login
16. Assuming you've done everything correctly you should be at the screen to confirm the account name
    1. Change the name to whatever you'd like (mandatory if it causes a conflict)
17. Press "Finish"
18. Turn on the switch next to "card"
19. Press "Synchronize now"
20. You're done!

{% hint style="info" %}
If you want to prevent modification to your iCloud Contacts from this device you can change the account to read-only

1. Open DAVx⁵
2. Pick the account
3. Click where it says "card"
4. Turn on the switch next to "Read-only"
{% endhint %}

{% hint style="info" %}
For calendar sync it's the same process except for 2 differences

1. Step 14a will be https://caldav.icloud.com/
2. Step 18 will show an entry for multiple calendars found on your Apple ID, enable the ones you are interested in seeing on your Android device
{% endhint %}
