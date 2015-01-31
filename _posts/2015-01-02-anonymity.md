---
title: "Anonymity"
bg: blue     #defined in _config.yml, can use html color like '#010101'
color: black  #text color
style: left
fa-icon: user
---

Believe it or not, your internet browsing yields as much personal information about you as your online accounts do, if not more! Websites often track your activity across the internet so they can collect marketing data: what your interests are, where you spend your time, and so on. As you can imagine, if this data is valuable to companies, it’s valuable to hackers and trolls too; it’s very easy to capture sensitive information like credit card data, physical location, or account data just by being able to monitor someone’s web browsing. So what should you do?

If your internet activity is not encrypted, it is NOT private and you should assume that someone or something could see it.

As you browse the web, think of it as constantly sending a multitude of open letters: anyone that positions themselves correctly can simply read them before passing them on to their intended destination. They can know where it came from, where it’s going, and everything contained within. This is where encryption is handy: encryption is like sealing the letters in envelopes, it guarantees that only the desired recipient can read the letters’ contents. And thanks to a lot of ingenious technologies, we can obscure the information about the sender and recipient as well.


The goal of the section is to make your internet activity on your desktop and laptop as secure as you’d like (we’ll cover cell phones later, though most of this advice is applicable there as well). The amount of protection you adopt is totally up to you; usually the trade-off is the more protection you want, the slower and more inconvenient browsing on the web can be. Fortunately, much of the basic technologies outlined require zero effort on your part and still offer a ton of protection.

Zero-Effort Privacy and Security: Browser Plugins


Browser plug-ins are free software you can install in your browser to customize your browsing experience. Listed below are plug-ins that help make your internet browsing safer from governments, corporations, or hackers snooping on your activity. If you don’t feel like reading, just follow the download links and install the plug-ins; your browser will end-up very secure! However, we recommend at least reading about each plug-in before you install.

It’s also worth pointing out that of the popular internet browsers (Chrome, Firefox, Safari, Internet Explorer), the only browser not developed by a for-profit corporation is Firefox. The developers of Firefox, Mozilla, have a long history of protecting users rights and are very active in fighting for a free and open internet. With the other browsers, your activity is frequently tracked by the company that owns the browser, so this guide strongly recommends using Firefox as your main computer browser.

Privacy Badger
Install for Firefox:
https://addons.mozilla.org/en-US/firefox/addon/privacy-badger-firefox/

Install for Chrome:
https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp?hl=en-US

What does it do?
“Privacy Badger is a browser add-on that stops advertisers and other third-party trackers from secretly tracking where you go and what pages you look at on the web.  If an advertiser seems to be tracking you across multiple websites without your permission, Privacy Badger automatically blocks that advertiser from loading any more content in your browser.  To the advertiser, it's like you suddenly disappeared.” - Electronic Frontier Foundation

Set-up?
None!

Official page:
https://www.eff.org/privacybadger

AdBlock
Install for Firefox:
https://addons.mozilla.org/en-US/firefox/addon/adblock-edge/

Install for Chrome: https://chrome.google.com/webstore/detail/adblock-plus/cfhdojbkjhnklbpkdaibdccddilifddb?hl=en-US

What does it do?
AdBlock+ blocks ads on 99% of the sites you visit. Ads can be the source of a virus, activity tracking, or just plain annoyingness, so this plug-in will pre-emptively block these nasty things with no effort from you. Note that the recommended adblock for firefox is not developed by a marketing company, while the chrome version is. The latter will sometimes give you ads that their company has sold :(

Set-up?
None!

Official page:
Firefox: https://bitbucket.org/adstomper/adblockedge/
Chrome: https://adblockplus.org/en/about

Ghostery
Install for Firefox:
https://addons.mozilla.org/en-US/firefox/addon/ghostery/

Install for Chrome: https://chrome.google.com/webstore/detail/ghostery/mlomiejdfkolichcflejclcbmpeaniij?hl=en

What does it do?
Ghostery identifies the “invisible” web, which is all the trackers, beacons, cookies, and other tools that websites and marketers use to track your activity across the internet. It then gives you options to shut-off these trackers depending on your preferences.

Set-up?
A little bit once you install it (you get a pop-up asking you a few set-up questions). Once in a while you may have part of a site you want to see blocked by Ghostery, but it’s very infrequent (and you can just click the ghost icon to continue to the desired page).

Official page:
https://www.ghostery.com/en/how-it-works

HTTPS Everywhere!
Install for Firefox:
https://www.eff.org/https-everywhere

Install for Chrome:
https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en

What does it do?
Many sites are set-up to encrypt (i.e. make private) your activity when you visit: it can be limited to sensitive things like making a purchase or can be used for the whole site. This plug-in makes it so your browser automatically uses this encryption whenever possible.

Set-up?
None!

Official page:
https://www.eff.org/https-everywhere/faq

Better Privacy
Install for Firefox:
https://addons.mozilla.org/en-US/firefox/addon/betterprivacy/

Install for Chrome:
Unavailable

What does it do?
This plug-in blocks “super cookies”, another way that websites (like Youtube or Ebay) can track your activity on the web.

Set-up?
None!

Official page:
https://addons.mozilla.org/en-US/firefox/addon/betterprivacy/

Zero-Effort Privacy and Security: Private Browsing
In both Firefox and Chrome, you have an option to browse privately, where no history or cookies from your browser are stored. This is a “Private Window” in Firefox and “Incognito Mode” in Chrome. If you are visiting a site that you would not be comfortable storing data for, use a private window instead!

HEADS-UP: BEWARE PUBLIC WI-FI
As we delve into more security options, it’s important to point out that public wi-fi is one of the most easily hacked sources of internet activity. Generally speaking, unless you’re using a combination of HTTPS, Tor, or VPN (all detailed below), be very wary of any activity done on the wi-fi. Someone can sniff your browsing with pretty minimal effort!

Zero-Effort Ultra-Maximum Anonymous Browsing: Tor Browser
(QUICK VERSION: IF YOU NEED TO BE ABSOLUTELY ANONYMOUS, USE THIS!)

The drawbacks of a browser like Firefox or Chrome is that a website, hacker, or government can still figure out your physical location and which sites you visit based on what’s being sent to your computer from where (even if they can’t read the contents of what’s being sent). In the case of the government or an internet service provider, they can even block access to a website entirely. Whenever using a normal browser, you are always open to this threat, regardless of what plug-ins you use. If you are ever in a position where you absolutely NEED to be anonymous, be it for safety or political reasons, then you need to use the Tor network.

The Tor network is an internet protocol that basically hides your identity by bouncing your web requests across the world in multiple layers of encryption before it is received by the website. Although you may visit a website from Boston, the website will see the request come from England or Kenya or Japan or any other country that the Tor network spits your request from; there is no way to track a web request to its origin. The network also hosts websites (called “onion sites”) that are not accessible through regular internet: this can range from political dissident websites to forums for abuse survivors to drug markets to plain ole’ boring websites. However, you can access the rest of the “normal” internet as well.

To funnel your internet activity through the Tor network, all you need to do is download the Tor Browser and you use it exactly the same as you would a regular browser. You don’t even need to install plug-ins! The most significant drawback is that the network is fairly slow: it takes a few seconds to bounce your requests around the world.

A big disclaimer for the Tor browser is that it makes you anonymous, but not private. Although your web requests are encrypted and anonymous, if you are posting on Facebook or sending an email through Gmail, that activity is still identifiable as “you”. So a good rule of thumb is that when using the Tor browser, do not visit sites or services associated with your private information. If you absolutely need to use a site that requires that kind of information, just make it up and make sure not to use it outside of Tor. Also, try not to download anything: because tor nodes (the servers that bounce around your web requests) can be run by regular people, they could attach a nasty virus to a downloaded file if they wanted.

A great interactive guide for how Tor (as well as HTTPS) protects your browsing can be found here:
https://www.eff.org/pages/tor-and-https

Download Tor Browser here:
https://www.torproject.org/download/download-easy.html.en

More information here:
https://www.torproject.org/about/overview.html.en

Some Effort + Potential Cost for Improved Security: VPN

Tor is slow, so it tends not to be the most fun thing to use for daily internet browsing. However, there are other ways to encrypt your web activity through a Virtual Private Network (VPN).

A VPN creates a private connection between you and a VPN provider: all of your internet activity gets “tunneled” through this private network before going out into the real world. As an example, say you’re downloading a file. When using a VPN, someone trying to watch the data being downloaded to your computer can’t see what that data is: it’s encrypted. And if the website you’re downloading from wants to know who’s downloading, they see a VPN provider company doing the activity, not you. Think of it as a private tunnel between your computer and your provider: your provider lets whatever you want into or out of the tunnel, but no-one but you can see what’s inside. Some VPN providers can take this a step further and even make your activity even more anonymous once it leaves their hands by bouncing it through proxies (other servers).

Unfortunately, VPN services are typically not free. You either have to set up your own server somewhere or, more commonly, pay for a monthly service from a VPN provider.

To set-up a VPN, you need to install a VPN client on your computer. The paid options tend to be easier, but the free options work fine too (maybe with a bit more effort on your part). Once you’re set-up, all you have to do is connect to the VPN and your activity will be much safer with minimal impact on browsing speeds. Set-up instructions for each client would be too lengthy for this guide (We’re only human!) so follow the instructions on the respective sites to get yourself going.

Mac & Windows Paid Client: https://www.sparklabs.com/viscosity/
Mac Free Client: https://code.google.com/p/tunnelblick/
Windows Free Client: http://openvpn.net/index.php/open-source/downloads.html

There are many VPN providers out there and it can be tough choosing: generally you want someone that does not store logs of its users while implementing OpenVPN as its VPN technology (some VPN tech has been hacked by the NSA; as far as we know, OpenVPN has not). If you want to pay, https://airvpn.org/ allows you to choose which countries to route your connections through, ability to pay anonymously via bitcoin, and the benefit of being a non-US based company (they’re less obliged to the NSA, so to speak). If you do not want to pay, you can try https://www.cyberghostvpn.com/en_us . Note, however, that the VPN connection will only last 3 hours for the free version; you would need to pay for 24/7 access.

ULTIMATE-SECURITY FOR EXTREME SITUATIONS: Tails

Should you ever need to use the internet with absolutely zero trace, to the point where you cannot even risk using your normal computer, you should consider installing the Tails operating system on a thumb drive. This is fairly advanced for the purposes of this guide, but should you ever need it, you can download the OS with set-up instructions here: https://tails.boum.org/about/index.en.html