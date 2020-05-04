---
layout: page
title: Two Factor Authentication
permalink: /2FA/
---
![Two factor authentication](/pic/2FA.jpg)
<h2>Why we need two factor authentication?</h2>
When we creating any account, using a strong password is our first step to secure our information not so easily get stolen. However, it is not the only way to protect yourself. There is an extra layer of security --- Two Factor Authentication (2FA)

<h2>What is two factor authentication?</h2>
When users are trying to log in to an account, after entering their username and a password, instead of immediately gaining access, they will be required to provide another piece of information. The second factor could come from one of the following categories:

* Something you know, such as a personal identification number (PIN), or a pattern
* Something you have, such as a phone
* Something you are, such as a biometric like a fingerprint or voice print

<h2>Different types of 2FA</h2>
**SMS text message and Voice-based**
This is a direct way of interaction with a user’s phone. After getting a username and password, the site sends the user a unique one-time passcode (OTP) via text message. User must enter the OTP into the application in order to get access.
 
However, this method is considered the least secure way for 2FA. If you are using a low-risk online activity, this method can be all you need. On the other hand, for account that store your personal information like utility companies, banks, or email accounts, this is not secure enough.

There are ways to intercept SMS messages in transit. This can lead to reset password of an account, which causes hackers get into your account. There was a [Bitcoin Wallet attack](https://www.youtube.com/watch?v=R9rDQU7eGAs) using this method, and it is mind-blowing. 

**Example** --- TicketMaster
![SMS-based 2FA](/pic/smsCode.jpg)
	
**Software tokens for 2FA**
This is the most popular form of 2FA and is better than SMS-based method. Users need to download and install a 2FA app on their phone or tablet. At sign-in process, after enter username and password, the app should prompt a time-based, one-time passcode (TOTP). Normally, this code is valid for one minute. The user can then enter the code into the site and get access. This will reduce the chance for hacker interception. 

**Example** --- NCSU Duo System
![Software-based 2FA](/pic/Duo_push.jpg)
![Software-based 2FA, token](/pic/token.jpg)

**Push Notification 2FA**
For the convenience of use, push notification method is getting more popular. It’s non-password authentication with no codes to enter, and no additional interaction required. Website will just send user a push notification that an authentication attempt is taking place. User can simply view the details and approve or deny access with a single touch. 

**Example** --- NCSU Duo System
![Push-Notification-based 2FA](/pic/Duo_push.jpg)
![Push-Notification-based 2FA, notification](/pic/notification.jpg)

**Example** --- Google Confirm System
![Push-Notification-based 2FA](/pic/Google_push.jpg)
![Push-Notification-based 2FA, notification](/pic/confirmGoogle.jpg)

**Biometric 2FA**
This method is treating user as the token. It requires something that only the user has, for example, fingerprints, retina patterns, and facial recognition, etc. Because of the skip use of 2FA when dealing with account recovery, which leads to less security. If we can find a smart with to use biometric recovery method, it provides a more secure and usable way to protect ourselves. 

[![2FA](http://img.youtube.com/vi/Xyw7Zqd1-UM/0.jpg)](http://www.youtube.com/watch?v=Xyw7Zqd1-UM "2FA")

<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>
<div class="responsive-wrap">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSAZJYZt9mNAfzOIZ2G3s0M0_PyqZPR5iZBO8dEnO0HeaPTph1mysvFyzPPfOwUhA/embed?start=false&loop=false&delayms=15000" frameborder="0" width="1280" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>
