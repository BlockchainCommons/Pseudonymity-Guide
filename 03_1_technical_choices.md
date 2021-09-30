# 3.1: Technical Choices

Now that you have understood the importance of privacy, taken initial steps to increase yours and sanitize your online environment, as well as crafted your own threat model, you are ready to start making important technical choices. The tools you'll be using to conduct the activities of your pseudonymous identity are central to the level of privacy and security of that identity, so you want to put great thought into it. Hopefully you have done the hard work already in your threat model, and the correct route you should take here will most likely be obvious.

So before you jump into the cool stuff and create a new identity, you should decide what hardware and software you'll be using.

## What Smartphone to Use?

This is a choice that depends on many different aspects. But most importantly, you need to consider your threat model.

A team of researchers of Johns Hopkins University published a [report](https://securephones.io/) that goes in depth into the _security_ of smartphones. The team compared the advertised security efforts of both iPhone and Android phones, mainly seeking to determine what security measures in these phones prevent unauthorized access to user data and how third parties may be able to bypass these measures. A summary of the report's main findings are below. It can help resolve the common arguments about whether iPhone or Android provides better security and privacy.

### iOS

Main findings:

- iCloud is a big vulnerability. When Apple's cloud backup services are enabled for an end-to-end encrypted app, if iCloud is used that encryption is compromised.
- Encryption keys are not evicted from the device's memory when the phone is locked, only when it is turned off, leaving it vulnerable to exploits while locked but on.
- Passcode guessing attacks are often feasible using a tool called GrayKey.

More details:

- iPhones are widely used, so it is highly valuable to seek exploits on iPhones.
- Apple software and technical modifications are centralized, so the user can never be sure their device is not vulnerable.
- iOS 14 introduced some privacy control features, but they focus on ensuring privacy against app developers only. That is a meaningful step, but those features do not protect against the phone itself.
- iCloud _backup_ data is vulnerable, since Apple has the keys. This includes: app data, Apple Watch backups, device settings, home screen and app organization, iMessage, SMS, MMS, photos, videos, purchase history from Apple services, and ringtones.
- iCloud data accessible to Apple includes: Safari history and bookmarks, calendars, contacts, find my iPhone, iCloud Drive, messages in iCloud, Notes, photos, reminders, Siri shortcuts, voice memos, wallet passes.
- iCloud data that is end-to-end encrypted includes: Apple card transactions, home and health data, iCloud Keychain, Maps data, memoji, payment information, quicktype keyboard vocabulary, screen time, Siri information.

Conclusion:

"With sufficient time, money, and fortunate circumstance (e.g. capturing a phone in an after first unlock (AFU) state), law enforcement agents can typically extract significant (if not all) personal data from modern iOS devices, despite Apple's claims around user privacy. This is exacerbated by Apple's failure to widely deploy Complete Protection over user data, and its failure to more broadly secure cloud services. (particularly, in the decision to store cloud authentication tokens in AFU). These facts combine to offer extensive access to law enforcement agents, rogue governments, and criminals."

Therefore, although there are strong protections in place for Apple iPhones, these are mostly security ones, apart from the recently introduced privacy features in iOS 14. But even then, they don't guard against the phone itself, which we can never be certain is not compromised. However, if one is using an iPhone for any reason, they are fairly well guarded against remote attacks if they _disable iCloud completely_. But the device will still be vulnerable if the attacker have it in their hands, due to the availability of encryption keys in memory and the fact that those keys are not evicted on locking the phone –– only on turning it off.

### Android

The report also researched Android phones. 

Main findings:

- Android has an auto-backup feature for all apps as default that is not encrypted. Developers have to explicitly and deliberately opt out of that and opt into end-to-end encrypted backups.
- Android involves the coordination of many different companies, which means a large attack surface.
- Native apps do not provide end-to-end encryption and there is extensive usage of Google services, which do not use end-to-end encryption.
- Decryption keys remain in memory at all times AFU, making them vulnerable to capture.

Conclusion:

"The primary takeaway from this discussion is that there are many techniques to bypass user data protections on Android. Lacking an analogue to iOS Complete Protection, decryption keys for user data remain available in memory at all time after the first unlock of the device; live extraction then becomes a question of breaking security controls instead of breaking cryptography or hardware. Additionally, the extent of Google's data collection affords law enforcement and rogue actors alike considerable user data, acquirable either through the legal system or through a device bypass."

### Pick Your Mobile OS

A good rule of thumb is to favor free and open source software (FOSS), which Android at its core _is_; however, the intensive data harvesting practices of Google undermine many of its benefits. The main issue with Android therefore lies in Google and its mandatory services, a default on Android devices. In that sense, using iPhone with the least of Apple services enabled, as well as opting out of iCloud _completely_, should provide increased security, and also increased privacy, in comparison.

However, there _is_ a possibility to "de-Google" an Android device. Popular FOSS solutions exist to harden an Android phone, removing Google services and bringing encryption as a standard. Two notable ones are [CalyxOS](https://calyxos.org/) and [GrapheneOS](https://grapheneos.org/).

GrapheneOS is a FOSS project that is constantly maintained, has a high user base, and provides very good privacy and security assurances compared to regular Android and iOS. However, it has some tradeoffs. More notably, some apps that need Google services enabled might not work. Below are two links for reference; research and decide if the tradeoffs are worth it for your identity.

* Features overview: [https://grapheneos.org/features](https://grapheneos.org/features)
* Anonymous Phone Update by the Privacy Security & OSINT Podcast with Michael Bazzell: [part one](https://soundcloud.com/user-98066669/232-anonymous-phone-update-part-i), [part two](https://soundcloud.com/user-98066669/233-anonymous-phone-update-parts-ii-iii).

## What Computer to Use?

Choosing the right computer to use is very important. Generally, you should apply compartmentalization here and use a dedicated computer for your advocacy needs, and again, choose a free and open source software (FOSS) solution. But your setup can vary based on your specific needs.

Below are the different routes you can take based on their required dedication of time, money, effort, and skill level, from the least to the most demanding. Have your threat model be the primary consideration you take into account for selecting a route, however, instead of effort or time. If you get slacky and choose an easier route, but one that doesn't fulfill your threat model entirely, you'll soon find some of your assets or your identity entirely in trouble. Be careful and choose wisely!

### Basic Setup - Tor Browser

You should use the Tor Browser for your pseudonymous identity activities only if you have absolutely _no time, no money, no technical skills, no effort to allocate, and very limited resources_.

The reason is that it will provide the smallest level of protection for you; but it is also the easiest to use, as you would not need to purchase any additional hardware. You can simply use the computer you already have, install Tor Browser in it, and use that for your advocacy needs.

But beware of the shortcomings of this setup too, notably the limited protection it will give you. Tor usage can be deanonymized based on your non-Tor usage and behaviors, so keep that in mind. This route might make sense depending on your threat model, but _is not recommended._

### Good Setup - Live Tails

An improved setup is to compartmentalize _partially_ and flash [Tails](https://tails.boum.org/index.en.html) in a USB drive for usage with the laptop or computer you already have and use with your real-world identity. This route is suggested if you have some amount of time and learning motivation but limited resources and can't purchase a dedicated laptop.

Tails will route all traffic through the Tor anonymity network as well as strictly compartmentalize storage, getting rid of all data when you turn it off (if in Amnesia mode). 

Although [not perfect](https://tails.boum.org/doc/about/warnings/index.en.html), Tails can help you [protect your digital life from censorship and surveillance](https://tails.boum.org/about/index.en.html) in a somewhat easy way. You can setup a Tails USB stick to temporarily turn your computer into a secure machine or stay safe while using the computer of somebody else.

If you use Tails exclusively for your new identity's needs, and your regular OS for your real identity, your setup would be considerably secure and private. But if used on a compromised machine, for instance, a computer with viruses or malicious hardware, Tails won't _always_ be able to protect you. Considering how difficult it can be to spot some malicious software and hardware in a given device, physical compartmentalization is always a better choice!

### Best Setup - Dedicated Laptop

A better but more expensive setup is to have one computer exclusively for each use case. This setup will only work if you don't mix identities with use cases and devices, however, because behavior patterns can still be used to deanonymize your Tor usage. Also, higher time, effort, and technical dedication are required in this setup.

_This setup is encouraged and should be sufficient for most people, including human rights activists._

Here, you'll use two laptops: one for your real-world identity, and one for your pseudonymous identity. The former can run whichever operating system you'd like, so as long as you abide by the general habits suggested in [1.2: Basic Steps to Regain Online Privacy](01_2_regain_privacy.md). The latter, however, needs to be run in a privacy and security enforcing OS, such as Tails, Qubes, or Whonix.

#### Tails

If your budget allows it, you might want to purchase a dedicated laptop to use for your sensitive activities over Tor on Tails. You can purchase a used business laptop for cash and install Tails on it for increased privacy and security at lower costs.

You can also buy a used MacBook Air from 2012 or 2013 for cheap, reset it, and [harden it for increased security and privacy](https://github.com/drduh/macOS-Security-and-Privacy-Guide); then you can use it more safely with Tails.

Just make sure you only use this computer for the very specific set of activities your identity needs.

#### Whonix or Qubes OS

The reason for having these two operating systems separately here is because of the increased hardware and system requirements they have. Both [Whonix](http://www.dds6qkxpwdeubwucdiaord2xgbbeyds25rbsgr73tbfpqpt4a6vjwsyd.onion/) and Qubes OS are more demanding to the machine they run on, so you'd need a bigger budget –– and more time and effort –– to set it up.

Also reference [this comparison](https://www.whonix.org/wiki/Comparison_with_Others) (onion site [here](http://www.dds6qkxpwdeubwucdiaord2xgbbeyds25rbsgr73tbfpqpt4a6vjwsyd.onion/wiki/Comparison_with_Others)) to judge which system would be better for your specific case.

### Pick Your Computer Setup

The golden rule of computer usage is compartmentalization. You should never mix use cases in the same device. However, the level of effort and money you'll apply on that will depend on your threat model.

Using Tails on a dedicated laptop is likely to suffice for most use cases, including if you are a human rights activist facing censorship or restrictions from developing countries or mid-tier entities, and it gives you the most assurances for the lower price.

For further information on how to protect your identity and achieve online anonymity, I recommend you take a careful look at [The Hitchhiker's Guide to Online Anonymity](http://thgtoa7imksbg7rit4grgijl2ef6kc7b56bp56pmtta4g354lydlzkqd.onion/guide.pdf), as it discusses technical routes with greater detail.

Once you have decided the technology you'll be using going forward, you're ready to [Create Your New Identity](03_2_create_identity.md).