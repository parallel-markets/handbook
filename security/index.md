---
nav_order: 7
---
# Security
{: .no_toc }

Given the sensitive nature of the information we deal with, security is of paramount importance.  This section contains some of our high level guidelines for helping ensure the safety and security of our confidential information.  This list is certainly not complete and represents a small subset of our overall security guidelines found in the Company's Security Policy.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Software
### Passwords :closed_lock_with_key:
Use a password manager!  [Wirecutter](https://thewirecutter.com/reviews/best-password-managers/) recommends [LastPass](https://www.lastpass.com/) or [1password](https://1password.com/), and [Wired has their own list](https://www.wired.com/story/best-password-managers/).  It doesn't matter which you use, just make sure you're using one for all of your passwords. Also:

1. Make sure you use a separate password for every service (for instance, your Gmail password should be different than your Slack password).
1. You should use the password autogeneration capabilities of your password manager to generate secure passwords.
1. Don't share passwords (with co-workers, friends, strangers, or any other people, living or dead :ghost:).  Every person should have their own account on every service.

### Multi-Factor Authentication :iphone:
You should use [Multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) (aka, 2 Factor Authentication, aka 2FA) for every service that provides it.  For most Company services, this is mandatory.

1. Always prefer a Time-based One-time Password option (a number that changes every 30 seconds) over text message.  SMS 2FA is vulnerable to an attack known as [a SIM Swap](https://www.wired.com/story/sim-swap-attack-defend-phone/).
1. Use an app like [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en&ref_topic=2954345) or [Authy](https://authy.com) to provide your Time-based One-time Passwords
1. Some services allow you to download "backup codes" that you can use instead of a time based code in case you loose your phone (or access to your time based password generator).  Make sure you store these somewhere safe!

### Secure Browsing
While browser extensions are easy to install and test out, make sure you only install extensions from sources you trust.  Here are a few extensions we do recommend:

* [HTTPS Everywhere](https://www.eff.org/https-everywhere) - ensure that you only visit sites that support encrypted HTTP
* [Privacy Badger](https://privacybadger.org) - A tool from the EFF, Privacy Badger automatically learns to block invisible trackers.
* [uBlock Origin](https://github.com/gorhill/uBlock#installation) - blocks ads and the data they collect

### Email :email:
Here are some general guidelines for email:

1. If you get an email that looks suspicious, forward the email to our IT support at [security@parallelmarkets.com](mailto:security@parallelmarkets.com).
1. An email can be suspicious, even if it's from someone you know, if there's an unexpected link :link: or attachment :file_folder:.
1. Don't be afraid to reach out to anyone directly to ask if they sent something you weren't expecting (for instance, reach out on Slack).
1. When in doubt, reach out to [security@parallelmarkets.com](mailto:security@parallelmarkets.com).

## Hardware :desktop_computer:
All company hardware should have the company's device profile installed to enable remote lock/wipe in case your laptop is stolen.  Your device should also:

1. Have full hard drive encryption enabled (for OSX, [use FileVault](https://support.apple.com/en-us/HT204837)).
1. Make sure you have your screensaver set to lock your computer after a short period of activity (and require a password)
1. Never leave your phone or laptop unattended in a public place (for instance, [at a coffeeshop](../work/where/#coffee-shops-coffee-and-co-working-spaces)).  Even if you leave your computer alone with a stranger for only a minute, [quick physical access is all that's required to hack your computer](https://en.wikipedia.org/wiki/Physical_access).
1. Ensure all of the important files on your devices are backed up [in one of our tools](../work/coordination/#communications-tools).  All computers eventually die, act as though yours could expire any day.

## Humans :bust_in_silhouette:
Be familiar with the general approaches used in [social engineering](https://en.wikipedia.org/wiki/Social_engineering_(security)), and know that you could be targeted based on your access to highly sensitive personal information.  You should understand the vectors used, like [Vishing :phone:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Vishing), [Phishing :fishing_pole_and_fish:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Phishing), and [Smishing :iphone:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Smishing).

## Network
In general, we operate with a stance of [Zero Trust](https://en.wikipedia.org/wiki/Zero_Trust).  We assume that our internal networks could be compromised and seek to secure resources rather than networks.  Given the nature of our [remote workforce](../work/index.md) and our utilization of cloud services, we cannot assume that resources are located within an enterprise-owned network boundary.
