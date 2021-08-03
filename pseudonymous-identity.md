# Pseudonymity Guide

This guide aims to provide the reader a simple yet effective way to create and operate a new pseudonymous identity.

## Introduction

The internet has become a hotbed for data harvesting. Users are faced with ever-increasing requirements of data submission to access online services (aka know-your-customer, or KYC procedures).

Although KYC is marketed as being a counter-terrorism practice, it often leads to the user having their personal information compromised. This is because data collecting companies, for example your phone number operator or bank, that do so for providing their services are bad in securing that data.

The solution, however, is not always hardened security for those companies' systems. They will always pose a security and privacy issue because they represent single points of failure –– one system which guards many data points. It is therefore easier for such a single system to be targetted by hackers or attackers, compared to a distributed system, for example.

But full anonymity in the internet is likely a far-fetched reality. Tracking companies and their practices can extend far beyong your browser and its cookies. Someone who seeks online anonymity––or at least pseudonymity––must go at great lengths, usually at the expense of time and money.

Therefore, before you start thinking about hiding from the entire world online, you should think about who or what you're trying to guard against.

Common attacks that anyone should consider actively protecting against include:

- **Marketing manipulation.** Marketing companies can purchase your information from other corporations, e.g. bank, social media, hospitals or clinics, and bombard you with their marketing efforts through mail, email, phone number, etc. This can also be used to manipulate persons or groups of people, as in the [Cambridge Analytica case](https://www.theguardian.com/technology/2019/mar/17/the-cambridge-analytica-scandal-changed-the-world-but-it-didnt-change-facebook).
- **Credit card fraud.** Culprits can steal your information through social engineering or phishing scams and make purchases in your name. This can usually be reverted but will result in at least many days of headaches.
- **Identity theft.** Also through social engineering, people can commit crimes under your name, permanently injuring your personal records and affecting your life.
- **Personal stalking.** Technology has enabled tracking to be easier and more accurate, often putting peoples' lives in danger. That restaurant checkin on Facebook can come back to haunt you. Information sellers can also be harmful in this case, and might've been liable in the [Amy Boyer case](https://epic.org/privacy/boyer/).
- **Government surveillance.** Some examples include: NSA's [ECHELON](https://techcrunch.com/2015/08/03/uncovering-echelon-the-top-secret-nsa-program-that-has-been-watching-you-your-entire-life), [FinCEN](https://www.thomsonreuters.com/en-us/posts/investigation-fraud-and-risk/fincen-leaks-aml/), [XKeyScore](https://www.hackread.com/xkeyscore-nsa-tool-spy-data-online/), [Fascia](https://www.digitaltrends.com/mobile/nsa-tracking-cell-phone-location/), [Optic Nerve](https://www.theguardian.com/world/2014/feb/27/gchq-nsa-webcam-images-internet-yahoo), [PRISM](https://www.theverge.com/2013/7/17/4517480/nsa-spying-prism-surveillance-cheat-sheet). The issue is that many of these projects, created under the justification to target and trim terrorism, more often than not [don't deliver](https://www.wired.com/2015/05/breaking-news-federal-court-rules-nsa-bulk-data-collection-illegal/) and end up harming civilians.

Mass surveillance is dangerous; it can silence or manipulate people. Privacy, and as of today also digital privacy, is therefore not only a basic right but should be encouraged and practiced by regular people everyday.

"Arguing that you don't care about the right to privacy because you have nothing to hide is no different than saying you don't care about free speech because you have nothing to say."

– Edward Snowden.

## Define Your Threat Model

Before creating your pseudonymous identity, you should step back and take some time to figure out your threat model and the security requirements associated.

>  NOTE: Beware that this guide does not aim to help you guard from highly skilled, highly motivated individuals with unlimited resources (for example if the NSA is coming after you individually).

You should think about what do you want to protect and who do you want to protect it from. Additionally, you may want to consider the consequences if you fail. This will help you determine how serious each threat is and plan accordingly. You will most likely take into account the likelihood of each threat happening, evaluate it against the potential harm it may cause, and the general cost to protect against it.

In the end, you'll have to decide how much trouble you're willing to go through to try and prevent potential but dire consequences. This might require listing out the options you have that could help mitigate such scenarios and proof-testing them one by one.

The _exact_ steps you should take to define your threat model go beyond the scope of this guide. We will present you, however, with an overview and link to good resources. Generally, however, you should think about:

1. What do you want to protect? Think about the assets you have which you don't wish to lose. This could encompass a wide range of goods, from physical to digital and pure information. It could be your bitcoin, your identity, your car, your smartphone, etc. Think about each and every good you wouldn't want falling in undesirable hands and list them out.
2. Who do you want to protect it from? Now, look back on your list of assets you want to protect and think about who shouldn't get a hold of them. This may change from asset to asset. For example, you might not want your spouse to have all the keys to your bitcoin, but you probably wouldn't bother to have them borrow your car. Again, you'll have to think about your unique circumstances, priorities, and levels of threat. In summary, who or what are the people/companies/governments that shouldn't be able to get to or control or seize each of the listed assets?
3. How bad are the consequences if you fail? Take a moment to think about the worst-case scenarios that could come true if that entity took hold of that asset. Would they only be able to steal the asset itself? Would you or your family be put in danger? If so, what kind, online danger or physical danger? Both? It might also be helpful to rank the potential consequences; it might make it easier for you to spot the worse ones.
4.  Out of those potential consequences, which ones should you really guard against? You may take into consideration both the likelihood of that consequence happening as well as how dire it would be. If something really bad is very likely to happen and is possible to be guarded against, that could be on the top of your priority list. Of course, not everything is possible to be prevented, but that also doesn't mean you shouldn't try. Threat modeling will help you figure out what you should work towards improving so that the chance of someone doing something bad with that diminishes. So in this step you should focus on deciding what threats you should work to mitigate.
5. Finally, think about how much trouble are you willing to go through to try to prevent the potential consequences selected in the previous step. Different assets and different bad actors require different measures for protection, and that is what this step covers. Here you will think about what would be necessary to mitigate the chance of each threat to take place. Let your thoughts run free and outline all the possible steps you could take to make sure that threat's likelihood of happening would be diminished significantly or completely. Think about the options you have available to help mitigate your unique threats. Then, you will need to decide which of those steps you are willing to act upon. This is necessary because some of them might require a commitment of time, money, or skills which you either may not have or may decide not to be worth it. So elicit the requirements for mitigating each threat, in terms of money, time, efforts, technical skills, among others. Next, carefully evaluate how realistic each option is for your circumstances.

The above five steps are based on the Surveillance Self Defense (SSD) initiative of the Electronic Frontier Foundation (EFF). You can find the complete guide [here](https://ssd.eff.org/en/module-categories/security-scenarios) –– it encompasses different requirements based on your specific activity. Take a look at it through the lens of the new identity you want to create and its required activities or scenarios.

For more complete and serious ways of determining your threat model, you can browse through these resources (evaluate which ones might better fit your needs):

- [Threat Modeling: 12 Available Methods](https://insights.sei.cmu.edu/blog/threat-modeling-12-available-methods/) by Carnegie Mellon University
- [LINDDUN privacy engineering](https://www.linddun.org/): a systematic elicitation and mitigation of privacy threats in software systems
- [Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html): OWASP Cheat Sheet Series
- [PASTA Threat Modeling](https://versprite.com/tag/pasta-threat-modeling/)
- [STRIDE Threat Modeling](https://en.wikipedia.org/wiki/STRIDE_%28security%29)
- [DREAD Risk Assessment Model](https://en.wikipedia.org/wiki/DREAD_%28risk_assessment_model%29)

## Hardware Choices

A quick note about hardware choices for your technological needs. You have plenty of options regarding _what_ to use, but perhaps the most important aspect is _how_ you use it.

More notably, you could –– and should:

- **Remove bloatware.** Every hardware comes with default software already installed out of the box. Evaluating which ones you _must_ keep versus the ones you can safely delete without compromising the functioning of the system can go a long way. Bloatware can compromise the performance, security, and privacy of that system –– and thus yours too.
- **Remove apps and programs not used frequently.** The idea is similar to the bloatware case, but here you are the one keeping unnecessary apps and programs you don't really use anymore. Make a habit of regularly evaluating the many applications you have installed in your system and see if you still need them installed. The greater the number of applications, the greater the attack surface and the bigger the system's vulnerability. You are better off uninstalling a certain app and installing it again once you need it than just keeping it around. _Only keep the bare minimum of applications that you need_. And while you're at it, you can also remove unused files.
- **Be skeptical of links.** Everytime you receive a message with a link, especially if it includes a sense of urgency, do not click on it. Be aware. Check the website, scrutinize the link to make sure it is pointing to where it should be. Some phishing sites use similarly-looking characters to fool you into thinking it's a legit site. Check for those. If the link is a shortened URL, use a URL expander service such as [URL Expander](https://urlex.org/) or [Expand URL](https://www.expandurl.net/) to see what the full link looks like. If the link came from someone you know and it looks suspiscious, consider giving that person a call to confirm veracity.
- **Use a VPN.** Some think VPNs are the holy grail of privacy, but that is often not the case. VPNs are better for security, because they make sure all your network traffic gets tunneled through their encrypted channels. As a plus you do get a new public-facing IP address though. Still, there are plenty of advantages for using a good VPN. Yes, there are also bad ones. By using a VPN you're trusting that company not to snoop on your traffic or keep logs of it, so a bad VPN would do just that –– spy on your network traffic and keep logs. Additionally, it might be helpful to use a VPN service that does not require extensive information for account setup and that you can pay for with Bitcoin. [Mullvad](https://mullvad.net/en/) is a good choice for all the above reasons. And they have an [onion website](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion/en/) too if you'd like to use Tor.
- **Harden your internet browser.** Your internet browser can reveal a great deal of information about you. So you should carefuly consider which one to use, how to use it, and when to use it. There are plenty of hardening guides online and different people prefer different browsers. I like Firefox because it is open source and flexible for customization. Here's a good [Firefox hardening guide](https://chrisx.xyz/blog/yet-another-firefox-hardening-guide/) and here's [another one](https://restoreprivacy.com/firefox-privacy/). Proceed with caution though and just harden it as much as you need, things can break otherwise. If you use plenty of things which broke after hardening the browser, consider using separate browsers for different types of tasks. Again, you might need to determine how far you want to go.
- **Perform regular updates.** Software updates exist for a reason. Yes, they do often introduce nice and cool new features. But more importantly, they fix bugs. Every software has some kind of bug, and updates fix them; this is how it works. So make sure you're keeping up with your devices' software updates. Some will give you the option to enable autoupdates.
- **Compartmentalize.** Software separation is good, but physical separation is better. If you have two identities, or two different roles or jobs which you wouldn't like getting mixed, or doxxed, consider having separate devices for each. If you keep them separate themselves also, that's a bonus. And if one phone gets compromised and becomes a wiretap and tracking device, information in the other device will likely be safe. So evaluate if you could benefit from having multiple devices and go down that route if so. And just so that doesn't incur a high investment, you don't need a flagship device most of the times. Also – if you end up using two separate phones for two different uses, get two different VPNs, one for each; compartmentalize that as well.
- **Prevent physical access.** This one might be a bit harder, but there are some steps you could take to diminish the risk of having your device be compromised through physical access. You can, for instance, make sure you don't lose sight of it when on risky environments. That is to say that maybe losing sight of your phone while at home likely won't incur high risk, but leaving it in your hotel room while you go for a jog could pose a more serious threat. So analyze and think what would consist threatening situations and hug that phone if you need to. One note on physical access, which is something this guide will cover in the next section –– if you ever find yourself walking into risky places or situations, either don't bring your phone with you (you can take a burner phone instead) or turn it off. When you turn your phone off, its encryption keys are evicted from memory, increasing the security of your data (at least marginally). And when leaving your device unattended, you can put it in a temper bag, or a Faraday bag, or both. Again, analyze and think how far you need to go in your specific case.
- **Consider resetting your device.** Although not a complete and flawless solution that fits every circumstance, resetting your device can be a good idea if it's become too bloated, or if you think it's been compromised by software, or if you just want to start anew. And doing it regularly can be even better. Just don't assume that if you're doing this you don't need the above; they complement each other.

### Smartphones

A common battle lies between iPhone and Android, where advocates pick sides and argue what is best in regards to security and privacy. A team of researchers of Johns Hopkins University published a [report](https://securephones.io/) that goes in depth into the security of smartphones. The team compared the advertised security efforts of both iPhone and Android phones, mainly seeking to determine what security measures in these phones prevent unauthorized access to user data and how third parties may be able to bypass these measures. A summary of the report's main findings are below.

#### iPhone

Main findings:

- iCloud is a big vulnerability. When Apple's cloud backup services are enabled for an end-to-end encrypted app, that encryption is compromised and often made worthless.
- Encryption keys are not evicted from the device's memory when the phone is locked, only when it is turned off, leaving it vulnerable to exploits even without a password (in locked state).
- Passcode guessing attacks are often feasible using a tool called GrayKey, however, that is not true every single time. But it is possible.

More details:

- iPhones are widely used, so it is highly valuable to seek exploits on iPhones.
- Apple software and technical modifications are centralized, so the user can never be sure their device is not vulnerable.
- iOS 14 introduced some privacy control features, but they focus on ensuring privacy against app developers only. That is already a meaningful step taken, but those features do not protect against the phone itself.
- iCloud _backup_ data that is vulnerable, since Apple has the keys, includes: app data, Apple Watch backups, device settings, home screen and app organization, iMessage, SMS, MMS, photos, videos, purchase history from Apple services, ringtones.
- iCloud data accessible to Apple: Safari history and bookmarks, calendars, contacts, find my iPhone, iCloud Drive, messages in iCloud, Notes, photos, reminders, Siri shortcuts, voice memos, wallet passes.
- iCloud data end-to-end encrypted: Apple card transactions, home and health data, iCloud Keychain, Maps data, memoji, payment information, quicktype keyboard vocabulary, screen time, Siri information.

Conclusion:

"With sufficient time, money, and fortunate circumstance (e.g. capturing a phone in an after first unlock (AFU) state), law enforcement agents can typically extract significant (if not all) personal data from modern iOS devices, despite Apple's claims around user privacy. This is exacerbated by Apple's failure to widely deploy Complete Protection over user data, and its failure to more broadly secure cloud services. (particularly, in the decision to store cloud authentication tokens in AFU). These facts combine to offer extensive access to law enforcement agents, rogue governments, and criminals."

Therefore, although there are strong protections in place for Apple iPhones, these are mostly security ones, apart from the recently introduced privacy features in iOS 14. But even then, they don't guard against the phone itself, which we can never be certain is not compromised. However, if one is to use an iPhone for any reason, they would be fairly guarded against remote attacks if they _disable iCloud completely_. But the device will still be vulnerable if the attacker have it on their hands, due to the availability of encryption keys in memory and the fact that those keys are not evicted on locking the phone –– only on turning it off.

#### Android

The report also researched Android phones. Main findings:

- Android has an auto-backup feature for all apps as default which is not encrypted. Developers have to explicitly and deliberately opt out of that and opt into end-to-end encrypted backups.
- Android involves the coordination of many different companies, which means a large attack surface.
- Native apps do not provide end-to-end encryption and there is extensive usage of Google services, which do not use end-to-end encryption.
- Decryption keys remain in memory at all times AFU, being vulnerable to capture.

Conclusion:

"The primary takeaway from this discussion is that there are many techniques to bypass user data protections on Android. Lacking an analogue to iOS Complete Protection, decryption keys for user data remain available in memory at all time after the first unlock of the device; live extraction then becomes a question of breaking security controls instead of breaking cryptography or hardware. Additionally, the extent of Google's data collection affords law enforcement and rogue actors alike considerable user data, acquirable either through the legal system or through a device bypass."

The main issue with Android therefore lies in Google and its mandatory services, a default on Android devices. Although the research did not cover, there is the possibility to "de-Google" an Android device. Popular open source software solutions exist to harden an Android phone, removing Google services and bringing encryption as a standard. Two notable ones are [CalyxOS](https://calyxos.org/) and [GrapheneOS](https://grapheneos.org/). But their assessment goes beyond the scope of this guide, so do your own research.


## Creating Your New Identity

Before starting, you should define what you're seeking to guard yourself from by creating and operating under a new, parallel identity by defining your threat model.

This can vary on a case-by-case basis, but two popular choices would be to either guard against basic online doxxing and other less sophisticated attacks, or to fully protect yourself against an abusive or totalitarian nation-state.

### Basic Threat Model

A more basic threat model seeks to prevent doxxing and similar threats. It doesn't guard against sofisticated actors such as nation-states, serious hackers, and anyone who has access to expensive lawyers and other resources.

Accordingly, privacy and security needs are smaller.

In this case, one would need:
1. A pronounceable handle, ideally not already in use by ProtonMail and GitHub, and optionally not already in use by Twitter and Gmail. Also check for availability of a cheap domain name.
2. Create a ProtonMail account. You will need a working SMS or a working non-ProtonMail email.
3. Have ProtonMail create an initial GPG key for you.
4. Register a GitHub account for your handle using your new ProtonMail email.
5. Add your GPG key to your GitHub account.
6. Purchase a WebAuthN key, for instance, a YubiKey, for increased security.

### Advanced Threat Model

The previous scenario disregarded some risks in its process, which weren't critical for that case but would be for a person who faces greater risk.

Vulnerabilities in the basic threat model:
* Searching for handle availability while not using Tails and/or Tor
* Not using a dedicated, untraceable phone and phone number
    * Using your current phone number for your new identity would be the highest vulnerability
    * A midway could be using an eSIM on your current phone, if it has that functionality. In this case, your vulnerability would be the carrier but it would at least be separated from your personal phone number.

A hardened identity creation process would be:
1. Use Tor and VPN in each and every step, making sure to connect to VPN first then Tor.
2. But first you'd need a VPN subscription. The best choice here is [Mullvad](https://mullvad.net/en/) which you can buy with Bitcoin through their [onion website](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion/en/).
3. But to purchase the VPN you'd need clean BTC, which is somewhat difficult to get. You can either buy from someone you know, or from a stranger in a peer to peer market. However, the latter would only be 100% clean if you transacted with cash, and the availability and feasibility for that would depend on the country you're in.
4. Additionally, you would also need untraceable phone and phone number. This can be very hard to get, especially considering that many solutions can be [honeypots](https://www.vice.com/en/article/m7e733/anom-fbi-andrew-young-encryption-honeypot).

## Operating Your New Identity

### Basic Threat Model

### Advanced Threat Model