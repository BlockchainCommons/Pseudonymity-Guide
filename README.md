# Blockchain Commons Pseudonymity Guide

<!--Guidelines: https://github.com/BlockchainCommons/secure-template/wiki -->

### _by [Namcios](https://github.com/namcios) and [Christopher Allen](https://github.com/ChristopherA)_

**Pseudonymity Guide** is a tutorial on how to securely create and operate a pseudonymous identity. It is intended to help activists, journalists, and others prevent or evade online stalking, doxxing, harassment, oppression, coercion, or censorship.

This guide is not meant to help malicious actors perform unethical, criminal, or illicit activities. It is written with the sole purpose of informing good-intentioned individuals, especially human-rights activists, about often-overlooked considerations and risks in online activities. Therefore, it provides insights and actionable steps that someone can take to sanitize their online environment and habits, as well as tips on creating and operating a pseudonymous identity separate from their real-world identity.

Start by reading the introduction below, which provides you with an overview of this guide's sections and their primary goals, the course of action you will take, and the benefits you can expect to gain from this guide.

## Introduction

In Part I of this guide, you are going to understand why you need privacy and why it is important. Privacy is a fundamental human right that precedes many others. This guide will discuss these intricacies and present cases and examples when an abuse of individual privacy has led to harsh consequences. Some negative side-effects of neglecting privacy are: loss of freedom, suppressed and diminished diversity in society, harassment, stalking, identity theft, permanent injuries to personal records or reputation, coercion, blackmail, and sometimes even death.

The interconnected digital world offers a unique tool for people to communicate, share ideas, comment on other's developments or projects, and can also lead to personal connections being developed in the physical world. However, such ease of flow of information also enables people to invade each other's private spaces, often resulting in the consequences mentioned above. Hackers, governments, and motivated entities in general have a huge amount of data available online, most often to the oblivion of regular people, which they can leverage to influence those people's behavior.

The hope of this guide is that an awareness of the ever-increasing pile of data being collected on you individually, with or without your consent, as well as of the likely consequences of that data falling in preying hands, may lead you to reconsider your relationship to the internet. Now, more than ever, it is of utmost importance for each and everyone to think what information about themselves they want and don't want made public in the internet.

After you understand all the primary moving pieces in online privacy, you will be prompted to think about your threat model in Part II. The guide will provide you with a basic notion of what a threat model is, why it is important, and how you can develop your own, as well as linking to resources for further research into the complex topic. A well-defined threat model will prevent you from trying to protect everything from everyone, something that is not achievable nor desirable. Instead, you will have a good understanding of who your true adversaries are, what information or assets you need to protect from them, and what are the actions you can take to enforce your threat model. Clarity on these is paramount to ensuring the success of your advocacy.

After defining your threat model, you will be ready to start creating a pseudonymous identity from scratch in Part III. The benefits of separating your real-world identity from the one you use for your advocacy needs can compound over the long-term, especially if you live in an authoritarian-ruled country. Ensuring that every human being can enjoy their dutiful rights is an honorable action, but one seldom secured by authoritarian regimes. In that case, being able to shed light on the issues surrounding your community, or even global humanity at large, can be empowered and facilitated by the correct use of a pseudonymous identity.

Beyond offering a step-by-step guide to creating a new pseudonymous identity, Part III of this guide will also discuss the technical choices you need to consider to make that happen. Your technical abilities and budget are leveraged to explain what route you should take regarding a computer and a mobile phone, as well as the software you want to have in them. This will tie back to the online privacy questions raised in Part I, as well as to the threat model you devised in Part II. Since human rights advocacy and activism is increasingly done online, the tools with which you connect to and engage with the internet matter. The correct selection and usage of such tools will play a big role in the successul safeguarding of your private information and assets from your adversaries.

Now that you know precisely what issues this guide aims to solve, and the ones it doesn't, you can begin to understand "Why Privacy Is Important" in [Section One]. You can also reference the table of contents below at any time.

## Table of Contents

**SECTION ONE: WHY PRIVACY MATTERS**

- 1.1: Why Is Privacy Important?
- 1.2: Basic Steps To Regain Online Privacy

**SECTION TWO: THREAT MODELING**

- 2.1: Define Your Threat Model

**SECTION THREE: A NEW IDENTITY**

- 3.1: Technical Choices For A New Identity
- 3.2: Create Your New Identity
- 3.3: Operate Your New Identity

_Old table of contents:_

- [Privacy Basics](./privacy-basics.md)
    - [Introduction](./privacy-basics.md#introduction)
    - [Threat Modeling](./privacy-basics.md#threat-modeling)
    - [Hardware and Software Choices](./privacy-basics.md#hardware-and-software-choices)
        - [Smartphones](./privacy-basics.md#smartphones)
        - [Computers](./privacy-basics.md#computers)
    - [Device Usage](./privacy-basics.md#device-usage)
- [Pseudonymous Identity](./pseudonymous-identity.md)
    - [Technical Choices](./pseudonymous-identity.md#technical-choices)
    - [Create Your New Identity](./pseudonymous-identity.md#create-your-new-identity)
    - [Operate Your New Identity](./pseudonymous-identity.md#operate-your-new-identity)

## Status - Edited

**Pseudonymity Guide** has been edited but should not be used for production tasks until it has had further testing and auditing.

### Roadmap

August 2021

- Finish first version of the guide

September-October 2021

- [ ] Improve organization by separating guide into sections with clear objectives.
- [x] Provide more clarity in README with an intro. What can the reader expect from the guide and what will they gain from it?
- [ ] Create "Why Is Privacy Important?" file
- [ ] Break up "Privacy Basics" into more granular files (steps to regain privacy, threat modeling, technology choices, etc.)

## Origin, Authors, Copyright & Licenses

Unless otherwise noted (either in this [/README.md](./README.md) or in the file's header comments) the contents of this repository are Copyright © 2021 by Blockchain Commons, LLC, and are [licensed](./LICENSE) under the [spdx:BSD-2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html).

In most cases, the authors, copyright, and license for each file reside in header comments in the source code. When it does not, we have attempted to attribute it accurately in the table below.

This table below also establishes provenance (repository of origin, permalink, and commit id) for files included from repositories that are outside of this repo. Contributors to these files are listed in the commit history for each repository, first with changes found in the commit history of this repo, then in changes in the commit history of their repo of their origin.

| File      | From                                                         | Commit                                                       | Authors & Copyright (c)                                | License                                                     |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------ | ----------------------------------------------------------- |
| exception-to-the-rule.c or exception-folder | [https://github.com/community/repo-name/PERMALINK](https://github.com/community/repo-name/PERMALINK) | [https://github.com/community/repo-name/commit/COMMITHASH]() | 2020 Exception Author  | [MIT](https://spdx.org/licenses/MIT)                        |

## Financial Support

**Pseudonymity Guide** is a project of [Blockchain Commons](https://www.blockchaincommons.com/). We are proudly a "not-for-profit" social benefit corporation committed to open source & open development. Our work is funded entirely by donations and collaborative partnerships with people like you. Every contribution will be spent on building open tools, technologies, and techniques that sustain and advance blockchain and internet security infrastructure and promote an open web.

To financially support further development of Pseudonymity Guide and other projects, please consider becoming a Patron of Blockchain Commons through ongoing monthly patronage as a [GitHub Sponsor](https://github.com/sponsors/BlockchainCommons). You can also support Blockchain Commons with bitcoins at our [BTCPay Server](https://btcpay.blockchaincommons.com/).

## Contributing

We encourage public contributions through issues and pull requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [Contributor License Agreement](./CLA.md).

### Discussions

The best place to talk about Blockchain Commons and its projects is in our GitHub Discussions areas.

[**Gordian System Discussions**](https://github.com/BlockchainCommons/Gordian/discussions). For users and developers of the Gordian system, including the Gordian Server, Bitcoin Standup technology, QuickConnect, and the Gordian Wallet. If you want to talk about our linked full-node and wallet technology, suggest new additions to our Bitcoin Standup standards, or discuss the implementation our standalone wallet, the Discussions area of the [main Gordian repo](https://github.com/BlockchainCommons/Gordian) is the place.

[**Wallet Standard Discussions**](https://github.com/BlockchainCommons/AirgappedSigning/discussions). For standards and open-source developers who want to talk about wallet standards, please use the Discussions area of the [Airgapped Signing repo](https://github.com/BlockchainCommons/AirgappedSigning). This is where you can talk about projects like our [LetheKit](https://github.com/BlockchainCommons/bc-lethekit) and command line tools such as [seedtool](https://github.com/BlockchainCommons/bc-seedtool-cli), both of which are intended to testbed wallet technologies, plus the libraries that we've built to support your own deployment of wallet technology such as [bc-bip39](https://github.com/BlockchainCommons/bc-bip39), [bc-slip39](https://github.com/BlockchainCommons/bc-slip39), [bc-shamir](https://github.com/BlockchainCommons/bc-shamir), [Sharded Secret Key Reconstruction](https://github.com/BlockchainCommons/bc-sskr), [bc-ur](https://github.com/BlockchainCommons/bc-ur), and the [bc-crypto-base](https://github.com/BlockchainCommons/bc-crypto-base). If it's a wallet-focused technology or a more general discussion of wallet standards,discuss it here.

[**Blockchain Commons Discussions**](https://github.com/BlockchainCommons/Community/discussions). For developers, interns, and patrons of Blockchain Commons, please use the discussions area of the [Community repo](https://github.com/BlockchainCommons/Community) to talk about general Blockchain Commons issues, the intern program, or topics other than the [Gordian System](https://github.com/BlockchainCommons/Gordian/discussions) or the [wallet standards](https://github.com/BlockchainCommons/AirgappedSigning/discussions), each of which have their own discussion areas.

### Other Questions & Problems

As an open-source, open-development community, Blockchain Commons does not have the resources to provide direct support of our projects. Please consider the discussions area as a locale where you might get answers to questions. Alternatively, please use this repository's [issues](./issues) feature. Unfortunately, we can not make any promises on response time.

If your company requires support to use our projects, please feel free to contact us directly about options. We may be able to offer you a contract for support from one of our contributors, or we might be able to point you to another entity who can offer the contractual support that you need.

### Credits

The following people directly contributed to this repository. You can add your name here by getting involved. The first step is learning how to contribute from our [CONTRIBUTING.md](./CONTRIBUTING.md) documentation.

| Name              | Role                | Github                                           | Email                                 | GPG Fingerprint                                    |
| ----------------- | ------------------- | ------------------------------------------------ | ------------------------------------- | -------------------------------------------------- |
| Christopher Allen | Principal Architect | [@ChristopherA](https://github.com/ChristopherA) | \<ChristopherA@LifeWithAlacrity.com\> | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |
| Namcios           | Lead Author               | [@namcios](https://github.com/namcios)           | \<namcios@protonmail.com\>                | 55A2 4BE0 AEE5 DB41 52C6 A410 8E3A 3683 1726 9AB4  |

## Responsible Disclosure

We want to keep all of our software safe for everyone. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner. We are unfortunately not able to offer bug bounties at this time.

We do ask that you offer us good faith and use best efforts not to leak information or harm any user, their data, or our developer community. Please give us a reasonable amount of time to fix the issue before you publish it. Do not defraud our users or us in the process of discovery. We promise not to bring legal action against researchers who point out a problem provided they do their best to follow the these guidelines.

### Reporting a Vulnerability

Please report suspected security vulnerabilities in private via email to ChristopherA@BlockchainCommons.com (do not use this email for support). Please do NOT create publicly viewable issues for suspected security vulnerabilities.

The following keys may be used to communicate sensitive information to developers:

| Name              | Fingerprint                                        |
| ----------------- | -------------------------------------------------- |
| Christopher Allen | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

You can import a key by running the following command with that individual’s fingerprint: `gpg --recv-keys "<fingerprint>"` Ensure that you put quotes around fingerprints that contain spaces.
