# Pseudonymity Guide

This guide aims to provide the reader a simple yet effective way to create and operate a new pseudonymous identity.


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