---
title: "Hacking"
bg: green     #defined in _config.yml, can use html color like '#010101'
color: black  #text color
style: left
fa-icon: crosshairs
---

<h2 class="text-white">Protect your digital accounts.</h2>

Your online accounts are points of access to your life both online and off. From email to social media to shopping, your accounts are crucial for pretty much everything you do through the internet. Spread out across these accounts is a treasure trove of personal data, credit card information, and even the ability to be “you” in online spaces. Unfortunately, hackers and abusers see the value in being able access these accounts: they’re one of the most popular targets for cyber harassment and crime. This section offers a number of ways to make hacking into your online accounts much more difficult. <strong>As with any electronic service, there is no foolproof way to protect against a dedicated hacker (and you should never trust anyone who claims otherwise)</strong>, but adding layers of security gives you much more control over your online identity and information that can deter and prevent many common forms of hacking.

As we outline best practices, useful technologies, and recommended services, the most crucial thing to remember is to be conscious of the risks of any given context. One of the best things to ask yourself is “If this was hacked, how would it impact my life?” Thinking along these lines mean that YOU can dictate the security and privacy of your digital life. You can choose to add more security measures, or fewer. You can choose to use a safer service, or stay with what you have. It's your call!
<hr>
<p>
	<h3 class="text-white">Do you <em>really</em> need to give your personal info? (...no)</h3>
</p>
Quite frequently a website or service will want more than just an email address and a password: they may want your name, your location, and other juicy marketable data. Well, fuck ‘em! Who says you have to tell them the truth? <strong>A good rule of thumb is to only give personal information that is absolutely necessary. Don’t be afraid to make things up! </strong>You can always give a fake name, a fake address, and all sorts of other made-up information. Unless you’re buying something, rarely is this personal information ever really crucial. By providing fake data, you lower the risk of a compromised account being linked to other accounts by shared data, as well reducing the possibility of a malicious person finding out more about you in real life.

<ul>
	<li><em>By the way, email addresses don’t need to be real either. If you’re just registering quickly to use a site once or twice, use a disposable email address! This is especially handy if you need to do something online anonymously. We like using <a href="https://www.sharklasers.com/">Sharklasers.com</a> because sharks are neato, but there are many similar services out there.</em></li>
</ul>

<h3 class="text-white">Strong Passwords: <strong>“Ugh”</strong></h3>
To quote xkcd, “Through 20 years of effort, we've successfully trained everyone to use passwords that are hard for humans to remember, but easy for computers to guess.”

The vast majority of online accounts can be accessed through a password and email address/username. As we all know, a good password is essential in ensuring that hackers can’t get into our shit. However, the way we create and remember passwords tends to be very easy to hack: common words and phrases can be programmatically exploited when trying to access an account. As the first and frequently only line of defense to accessing your account, strong passwords are key!

Here are a few general rules to follow for creating good, strong passwords:
<ol>
	<li>A mixture of random letters, numbers, and special characters is best.</li>
	<li>The longer, the better. 12 characters or more!</li>
	<li>If you have real words in your password, try to use obscure and/or weirdly misspelled references. Dictionary or pop culture words are bad.</li>
	<li>DON’T RE-USE PASSWORDS ACROSS MULTIPLE SITES.</li>
	<li>DON’T RE-USE PASSWORDS ACROSS MULTIPLE SITES.</li>
</ol>

<h3 class="text-white">Password Managers: <strong>“Cool!”</strong></h3>
As you can guess, making strong passwords sucks. When you have dozens of accounts across many sites, it’s practically impossible to be perfect about creating and remembering all these unique passwords. Not to mention that sometimes sites are terrible about storing passwords: they get hacked, but -you- have to change your password. There are tools to help you though! A password manager is an online service that can generate and store all your passwords for you so that you don’t have to know them by heart.

<code><a href="http://lifehacker.com/5529133/five-best-password-managers">Here</a> is a guide detailing some of the most popular password managers out there.

You’re probably suspicious: isn’t it dangerous to have all your passwords in one place? And you’d be right to think so, because it is! That’s why it’s important to evaluate how a given password manager actually manages the passwords and what protections are in place. Ultimately, you have to decide for yourself how you balance the risk of bad passwords, spread out across your accounts, against the risk of good passwords centralized in one location.

<div class="recommend">
<h5 class="text-white"><strong>LastPass</strong></h5>
<br>
Given how hard it it is to remember safe, unique passwords, we still recommend a password manager, specifically the service <strong>LastPass</strong>.<br>
<br>
LastPass uses a combination of browser plug-ins, phone apps, encryption, two-factor authentication, and a multitude of other technologies to ensure your passwords are stored safely and accessibly (for only you!). It can also randomly generate -extremely- strong passwords for you to use. We especially like LastPass because all of your passwords are encrypted when saved in LastPass’ cloud: even if they were hacked, a hacker could not use them unless they knew your LastPass password (which is never stored by LastPass). Needless to say, if you decide to use LastPass, make sure your password to access LastPass is the strongest password you’ve ever had! You won’t have to remember your passwords anymore, so this should be a bit easier to do.<br>
<br>
As we keep our minds on risk mitigation, we recommend that you do not use LastPass for your email, bank, or healthcare accounts. Although LastPass is a very secure service, it’s still a company subject to mistakes and vulnerabilities. By separating out your most crucial passwords, you have a bit of protection by not having ALL your eggs in one basket. The important eggs are worth storing in their own basket!<br>
<br>
A few good rules of thumb for using LastPass:<br>
<br>
<ul>
	<li>Use password generation for lengthy, complicated passwords. At least 16 characters with letters, numbers, and symbols is good</li>
	<li>Make sure to enable Two-Factor Authentication for LastPass</li>
	<li>Always require your master password for entering passwords for important accounts</li>
	<li>Once you have logged-in to LastPass from your phone and/or tablet, from your vault page on the LastPass website, go to Settings, and under the “Mobile Devices” tab, make sure to check “Restrict mobile devices to the specific UUIDs listed as enabled below”. This way only these specific devices can be used to log-in to your LastPass.</li>
</ul>
</div>

<h3 class="text-white">Two-Factor Authentication: <strong>“Yay!”</strong></h3>
One of the absolute best things you can do for your online accounts is enable two-factor authentication (2FA) whenever it’s available. Essentially, rather than only needing a password to log-in, you need to enter a second piece of data as well. This is typically a short code sent to you in an email, a text, or generated by an app on your phone. 2FA is a wonderful piece of security because it means that even if your password(s) were hacked, a hacker would still need access to your email, phone, or app in order to get into your account.

You should definitely enable 2FA for any of your crucial accounts that offer it. Most big tech services like Google, Facebook, Dropbox, and Twitter have this option available, as do popular password managers like LastPass. Typically you just need to dig around in your account settings on a given site to find the instructions on how to enable it. <a href="https://www.google.com/landing/2step/">Here</a> is a useful guide from Google if you would like to know more about how Two-Factor Authentication works.

<div class="recommend">
<h5 class="text-white"><strong>Authy</strong></h5>
<br>
When you use a site or service that offers Two-Factor Authentication (2FA), you often have the option to generate a QR code or numeric code that you enter into a 2FA app on your phone. From then on, when you log into a site and service and are prompted for a 2FA code, you just have to look in the app for a generated code to use with that account. This is more secure than receiving a code via text or email, as it is much more difficult for a hacker or surveillance to get access to. While there are many 2FA apps that offer this functionality, we recommend an app called Authy.<br>
<br>
Authy is a neat app that will automatically generate your two-factor authentication codes offline anywhere you have the Authy app installed. Authy can be installed on any phone or desktop, with all your 2FA code-generating accounts backed-up on a single Authy account. This means that if you were to lose a phone, or get a new laptop, all you have to do is install Authy and log-in with your Authy account info (have a very strong password!!) and your 2FA codes are still being generated seamlessly. Your 2FA accounts are encrypted in the cloud too, meaning that if Authy’s servers were ever hacked, your Authy data would be unusable! And because these codes can be generated offline, you do not need internet or cell service to access them.<br>
<br>
Available for free in the iTunes and Google Play stores, also as a chrome plug-in<br>
Guides for installing can be found <a href="https://www.authy.com/users">here</a>
</div>