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