---
layout: page
title: Cookies
permalink: /Cookies/
---

<h2>What is Cookie?</h2>
Generally, Cookie is a pieve of data that stored in your web browser, and will send along, encrypted, with any request to the server.<br>
Originally, cookie is the way for users to record items they want to purchase, now, a typical use is to allow the website identify the client without asking for authorization each time with an unique session identifier.
In the same way, it could also store personal information, like the web setting, preference.

<h2>Different Type of cookies</h2>
- Session cookie: the cookies expired when you close the tag.

- Persistent cookie: the cookie that will expired in specfic day, usually specfied by the creator, to maintain the same cookie until that day.

- Secure cookie: the cookie that could only sent by https, preventing intersect if the user is not under securit website.

- Http-only cookie: the cookie usually used for scripting, prohibited the client side to access, can preventing malicious process to read scripting and prevent cross-site scripting (XSS). 

- Third-party cookie: this is the cookie that is not from the current pages, it will allow other website to read your web record, generally, this is used for advertisement and now it is abused, where most of the website will read your third-party cookie to get your browse history.

<br>Here is a cookie example<br>
<strong>Set-Cookie: LSID=DQAASD…EaCN_Ye; Path=/accounts; Expires=Wed, 13 Jan 2021 22:23:01 GMT; Secure; HttpOnly</strong>

<h2>Cookie theft</h2>

Since cookie is so important and contains private information, hackers are trying to get the cookies. <br>
* Where network traffic is not encrypted, attackers can read the communications of other users on the network, intersect and use the cookies, see <a href="https://everydaysecurity.github.io/everydaysecurity/publicwifi/">unsafe public WIFI</a><br>
* Fake sub-domain, when the attacker create a fake sub-domain to the real page, like https://123.www.amazon.com/, the browser will be fooled and send your amazon cookie to the attacker.
* Cross-site scripting: When the site is not careful enough, allowing the users to post unfiltered scripte, the attacker could alter the content of the page, and re-direct the original purpose of the page, like fake a new submit buttom. When the user click on it, it will send the user's cookie to the attacker instead of the orignal use.

<h2>Other options?</h2>
<h3>For developer:</h3>
* Embedding information in URLs
* Using hidden fields in forms
* Using localStorage
<h3>For users:</h3>
* Use anonymit mode for accessing website that you didn't wish to store your information.
* Less use of "remember me", logout toinvalidate your authentication cookie when you finish. It could also prevent <a href="https://everydaysecurity.github.io/livingpeacefully/intimatepartnervoilence/">Intimate Partner Voilence</a>
* Switch broswer if you are working on sensitive work.
<br>
<br>
check  <a href="https://www.slideshare.net/everydaysecurit/cookie-201791329">cookie ppt</a>
and the <a href="https://www.slideshare.net/everydaysecurit/cookie-note">cookie ppt note</a>
