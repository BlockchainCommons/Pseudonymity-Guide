# Appendix 1: Smartphones

A team of researchers of Johns Hopkins University published a [report](https://securephones.io/) that goes in depth into the _security_ of smartphones. The team compared the advertised security efforts of both iPhone and Android phones, mainly seeking to determine what security measures in these phones prevent unauthorized access to user data and how third parties may be able to bypass these measures. A summary of the report's main findings are below. It can help resolve the common arguments about whether iPhone or Android provides better security and privacy.

#### iPhone

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

#### Android

The report also researched Android phones. 

Main findings:

- Android has an auto-backup feature for all apps as default that is not encrypted. Developers have to explicitly and deliberately opt out of that and opt into end-to-end encrypted backups.
- Android involves the coordination of many different companies, which means a large attack surface.
- Native apps do not provide end-to-end encryption and there is extensive usage of Google services, which do not use end-to-end encryption.
- Decryption keys remain in memory at all times AFU, making them vulnerable to capture.

Conclusion:

"The primary takeaway from this discussion is that there are many techniques to bypass user data protections on Android. Lacking an analogue to iOS Complete Protection, decryption keys for user data remain available in memory at all time after the first unlock of the device; live extraction then becomes a question of breaking security controls instead of breaking cryptography or hardware. Additionally, the extent of Google's data collection affords law enforcement and rogue actors alike considerable user data, acquirable either through the legal system or through a device bypass."

#### Conclusion on Smartphones

A good rule of thumb is to favor free and open source software (FOSS), which Android at its core _is_; however, the intensive data harvesting practices of Google undermine many of its benefits. The main issue with Android therefore lies in Google and its mandatory services, a default on Android devices. In that sense, using iPhone with the least of Apple services enabled, as well as opting out of iCloud _completely_, should provide increased security, and also increased privacy, in comparison.

However, there _is_ a possibility to "de-Google" an Android device. Popular FOSS solutions exist to harden an Android phone, removing Google services and bringing encryption as a standard. Two notable ones are [CalyxOS](https://calyxos.org/) and [GrapheneOS](https://grapheneos.org/).

GrapheneOS is a FOSS project that is constantly maintained, has a high user base, and provides very good privacy and security assurances compared to regular Android and iOS. The detailed assessment of GrapheneOS, however, currently goes beyond the scope of this guide, so do your own research. Below you can find a couple of links for further reference:

* Features overview: [https://grapheneos.org/features](https://grapheneos.org/features)
* Anonymous Phone Update by the Privacy Security & OSINT Podcast with Michael Bazzell: [part one](https://soundcloud.com/user-98066669/232-anonymous-phone-update-part-i), [part two](https://soundcloud.com/user-98066669/233-anonymous-phone-update-parts-ii-iii).