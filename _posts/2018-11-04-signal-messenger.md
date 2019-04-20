---
layout: post
title: "Friends don't let friends chat unencrypted - A look at Signal messenger"
author: "Josh Unwin"
categories: journal
tags: [tech,privacy,signal]
image: /signal/signal-header.gif
---

Have your heard of [Signal](https://signal.org/)? Depending on who you ask, there's a very good chance the answer to that question is, unfortunately, no. To get to the point, Signal is a free messaging platform much like WhatsApp, Facebook Messenger, Google Hangouts or Telegram, but it has a focus on security and privacy.

Speaking of, for this post I'm going to assume you agree that privacy is important, whether you have something to hide or not. In a context where one can reasonably assume to be in private, an individual should not need to feel concern, be it in inside your own home, or sending a direct message to a friend as is this case. If you somehow disagree with the above, well, I guess you may as well continue on with your day, this one isn't for you - though I strongly suggest having a careful think about the topic!

So what makes Signal stand out from the rest from a security standpoint? And what pitfalls might you experience if you did decide to try the service? In this post I cover why I think Signal should be your messenger of choice (trust me, I've tried a lot..).

## Signal - The Fort Knox of messengers
To make this as digestible as possible, below are the three key things that make Signal different to the rest.
* **The Signal Foundation is non-profit. Built by OpenWhisper Systems** - a project under the non-profit organisation titled 'The Signal Foundation', Signal is funded entirely by donations and grants. This is key. It's not trying to make a profit with your data and unlike anyone else, it has no interest in your personal information. It exists to try to make privacy simple and freely available to all. Unlike other messaging apps using a traditional business model, it doesn't face the pressure of needing to find ways of making a profit and crucially never will. This was the predicament faced by WhatsApp, an initially very consumer and security focused app. As it matured, it had to begin to make money somehow, and eventually got sold to Facebook in 2014 for an unprecedented $19 billion.
* **Signal is open-source.** It's code is readily available for anyone to view and scrutinise. This includes both the app code and the server code. There's no propriety software hidden behind a shadowy veil. Not only does this give you the assurance that there is nothing out the ordinary going on behind the scenes, it also allows for security potential flaws to be spotted and patched fast.
* **Signal's encryption is industry standard.** While its user base is frustratingly modest, its impact on the messaging industry certainly isn't. Being open source and therefore freely available for integration in other platforms, Signal's rock solid encryption (known as the Signal Protocol) has been adopted by a number of major players including WhatsApp (default, see below for a quick summary of the differences), Google Allo (in 'Incognito' mode), Facebook Messenger (in 'Secret Conversations' mode) and Skype (in 'Private Conversations' mode). Not bad for a team of three (as of 2016)!


## What's up with WhatsApp?
As you may have spotted above, WhatsApp uses Signal's open source encryption protocol, just like other popular messengers. But unlike the rest, WhatsApp is the only one to fully adopt it, enabling it for all users by default. Doesn't that make WhatsApp just as secure as Signal, you may ask? Well, sort of.
Other than the simple fact that WhatsApp is owned by Facebook, a huge corporation that profits primarily from users data, WhatsApp remains a solid choice for consumers from a privacy perspective, for now.
Here's a summary of the caveats of WhatsApp:
* **WhatsApp can collect and analyse message metadata.** It is true that WhatsApp is end-to-end encrypted on both Android and iOS and in both individual and group chats. Being end-to-end, only the users devices have the appropriate keys to decrypt the data, so WhatsApp/Facebook couldn't read the message contents even if they, or a government body wanted to. That said, unlike Signal, WhatsApp can record and store metadata related to the messages. This primarily includes when a user was last online and for how long, who sent a message and to whom, when a message was sent, when it was read, and the size of the message. This may not sound like a huge issue, but most of the NSA's data analysis is based on metadata such as this, and when metadata from multiple sources can be gathered and inspected, a surprising amount of information can be inferred.
* **Facebook is bringing ads to WhatsApp.** Since acquiring WhatsApp in 2014, Facebook has been surprisingly hands-off with WhatsApp but that is about to change in 2019 [when it introduces ads to the platform](https://www.forbes.com/sites/parmyolson/2018/09/27/facebook-is-committed-to-whatsapp-encryption-but-could-bypass-it-too/#2303f84f3efe), starting with the 'Status' section (who uses that anyway!?).
* **WhatsApp is for-profit, and ultimately closed source.** While it may use Signal's encryption, there is no way for the general public to know exactly how this encryption is being used. [As the Forbes article points out](https://www.forbes.com/sites/parmyolson/2018/09/27/facebook-is-committed-to-whatsapp-encryption-but-could-bypass-it-too/#2303f84f3efe), Facebook could opt to find ways of extracting personal information from your messages for the purpose of profit while maintaining the encryption. One suggested way they might achieve this is for the app to locally scan the message contents for keywords prior to it being sent. Being closed source, it is simply impossible for us to know.
* **WhatsApp's local and backup copies of messages are insecure.** With WhatsApp, a message is encrypted at the point it is sent from the device. The copy stored locally, and the copy you may opt to backup to the cloud (such as it's built in Google Drive backup option) is not encrypted by the app.
* **Things could change a moments notice.** Facebook is under no obligation to maintain WhatsApp's encryption. Truth is, WhatsApp's privacy focus goes against everything else that Facebook does. It's a surprise the messaging service has remained as true to its roots as long as it has, likely due to the resilience of original founder Brian Acton, who, despite selling out to Facebook, has always been a strong advocate of privacy. See more about Brian below. Anyway, at any time, Facebook could flick the switch and disable the encryption all together. This more than anything else, is why I'd love to move away from WhatsApp as much as possible. It's a relatively good option for now, but we should avoid being at the mercy of Facebook when it decides it wants to exploit WhatsApp further. Signal provides the only truly long-term solution for privacy by being open source, non-profit and donation funded - it doesn't face the risk of being exploited later down the line.


## Brian Acton - Privacy reborn?
I wanted to write a quick section on Brian Acton - WhatsApp's founder, simply because his story helps bolster Signal's reputation.
In 2009, former Yahoo! employees [Brian Acton](https://en.wikipedia.org/wiki/Brian_Acton) and [Jan Koum](https://en.wikipedia.org/wiki/Jan_Koum), founded WhatsApp, a messaging app that Acton was keen to make secure and ad-free. Although things started slow, the app picked up popularity before being brought by Facebook for a record $19 billion in 2014. The sale came as somewhat a surprise to some, given Acton's strong views on privacy and and providing an ad-free experience, the two things Facebook exploit for profit. Both Acton and Koum continued their roles at WhatsApp under the Facebook umbrella, but not without reports of frequent disputes between Acton and board regarding WhatsApp's future. After continued internal conflict, Acton left Facebook/WhatsApp in 2018, and perhaps in an attempt of self-redemption, provided the initial $50 million donation that kickstarted The Signal Foundation, a step that solidifies Signal's efforts to provide free expression and privacy for all.

## "Okay, but Telegram's my jam"
For those of you Telegram users out there reading this who are probably thinking "yeah, but Telegram is secure too", this bit is for you. Firstly, it's certainly a reasonable statement to make. Telegram screams to the hills about it's pro-privacy and highly secure nature, and it's probably a pretty safe bet, but there are a few key differences that makes Signal the better choice from a privacy standpoint.

Here's the key ways in which they differ (a little repetition here..).
* **Telegram does NOT use end-to-end encryption by default.** You'd be forgiven to think otherwise based on the advertising, but as per Telegram's FAQ, the messenger does NOT end-to-end encrypt messages by default. The only way to make use of end-to-end encryption in Telegram is via the 'Secret Chats' feature. Telegram's justification for this is that the regular, non-secret messages and their accompanying encryption keys are split up into multiple pieces, and each piece is stored on a different server, in various countries. In order for Telegram to pull the data together in the case of a data request from a government, multiple entities must agree to the request which makes it much more challenging. While that may sound reasonable, anything not end-to-end encrypted cannot truly be considered secure. Your default messages can still be intercepted, and it is still theoretically possible for your messages to be maliciously compromised from Telegram's servers.
* **Telegram uses proprietary encryption.** The encryption of both Telegram's servers and the 'Secret Chats' mode is proprietary. While this does not necessarily mean it's insecure, it is generally considered a no-no by cybersecurity experts. The best encryption is that which is widely accepted as robust, one which can be and has been highly tested and is openly available for inspection by third parties. By creating their own encryption technique and not making it openly inspectable, Telegram takes an unconventional approach to encryption.
* **Telegram is closed source.** As touched on above, Telegrams source code isn't available to be viewed by the public, making it impossible to be scrutinised.
* **Telegram stores your messages on their servers.** One of Telegram's big selling points over WhatsApp (and Signal) is that it stores and syncs messages with it's servers. The benefit of this is that you can use Telegram natively on any device instead of having to connect via your primary mobile device (this is why you must scan a QR code and have a network connection on the primary device to use WhatsApp Web). While the added convenience is nice, you are entrusting Telegram with your data, both that their servers are robust enough against malicious attacks, and that they won't misuse your data. This simply isn't a factor with Signal or in fact WhatsApp - throwing [Telegram's claims of being "way more secure"](https://telegram.org/faq#q-how-is-telegram-different-from-whatsapp) than WhatsApp into question.


## So, you want give Signal a shot?
Maybe you've read this far (wow, thanks!) and you feel like Signal is something you should try, but you want to know what the experience will be like. After all, surely such a secure platform is going to mean less convenience? Well, actually, no. Okay fine, sort of.

From a usability and feature standpoint, Signal is most comparable to WhatsApp. It too uses your phone number to find your friends and offers the follows functionality:

* Private and group chats
* Encrypted phone conversations
* Multimedia messages (include images, GIFs, video, audio, documents/files, locations and contact information)
* Voice messages
* Read receipts
* 'Disappearing messages' (the same default Signal encryption, but in this mode, messages disappear for all users after a user configurable amount of time)
* SMS/MMS support (note in SMS/MMS mode, you will not be using Signal's protocol, I recommend avoiding this feature to avoid confusion).
* Custom theme support
* Desktop client support (requires phone connection akin to WhatsApp, apps available for Windows, MacOS and Linux)

As you can see, the list is pretty comprehensive. While you maybe missing some gimmicky features some other services provide (stuff like custom font sizes and sticker packs), there's really nothing essential you'll long for after a move to Signal, with the exception of one, very fundamental thing.. Your contacts.

A lack of adoption of Signal by the majority is its single biggest pain point for people who want to enjoy the assurance of a secure and reliable messaging service.

So my recommendation? Just install Signal and get it setup. Give people the option to contact you on it, even if you have no plans to use it for now, or in fact, have no one in your contact list who uses it. When it comes to gaining new users, the biggest downfall of any messenger is when a user downloads it and finds an empty list of friends, and that can only change with installs!



## You can download Signal from the links below:

[Signal - Official Site](https://signal.org/)

[Signal - Google Play Store](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)

[Signal - Apple App Store](https://itunes.apple.com/us/app/signal-private-messenger/id874139669)

I also highly recommend taking a read of [this article from Micah Lee](https://theintercept.com/2016/06/22/battle-of-the-secure-messaging-apps-how-signal-beats-whatsapp/) at The Intercept which takes a dive into Signal vs other apps, with information directly from Signal's founder, Moxie Marlinspike.

To close this out, [Signal announced just this week](https://www.wired.com/story/signal-sealed-sender-encrypted-messaging/) that it is testing and rolling out a new privacy measure that enables the encryption of the sender information of each message.
