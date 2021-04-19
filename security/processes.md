---
parent: Security Practices
nav_order: 9
title: Processes
---
# Processes and Proceedures
{: .no_toc }

This page contains details on 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Accounts and Passwords :closed_lock_with_key:

### External Accounts

Do not sign up for a new service on behalf of Parallel without first receiving permission from [mailto:security@parallelmarkets.com](security@parallelmarkets.com)

This includes signing into web pages and web apps using your @parallelmarkets.com Google sign-in.

### Passwords
Use a password manager!  A password manager let you memorize one strong password, and then it generates and manages strong, unique passwords for every site for which you have a login.  Employees can install [LastPass](https://www.lastpass.com/) or [1password](https://1password.com/) via the Self Service App that is installed on your company device.

1. Make sure you use a separate password for every service (for instance, your Gmail password should be different than your Slack password).
1. You should use the password autogeneration capabilities of your password manager to generate secure passwords.  Passwords should:
 * have a minimum length of 12 characters
 * never be reused - whether across services or on the same service
 * should not be the same as username
 * should not be predictable (for instance, follow a pattern across services)
1. Don't share passwords (with co-workers, friends, strangers, or any other people, living or dead :ghost:).  Every person should have their own account on every service.
1. Don't write any passwords down.
1. Password "hints" are not to be used. If a password is forgotten, a mechanism must be in place to replace a password/passphrase with sufficient controls to verify the identity of the requester of the password reset.
1. If an account or password is suspected to have been compromised,  [contact the Security Team](#contacting-security) immediately.

### Multi-Factor Authentication :iphone:
You should use [Multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) (aka, 2 Factor Authentication, aka 2FA) for every service that provides it.  Note that 2FA is mandatory for most Parallel services.

1. Always prefer a time-based one-time password option (a number that changes every 30 seconds) over text message.  SMS 2FA is vulnerable to an attack known as [a SIM Swap](https://www.wired.com/story/sim-swap-attack-defend-phone/).
1. Use an app like [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en&ref_topic=2954345) or [Authy](https://authy.com) to provide your time-based one-time passwords
1. Some services allow you to download "backup codes" that you can use instead of a time-based code in case you lose your phone (or access to your time-based password generator).  Make sure you store these somewhere safe!

## Secure Browsing :computer:

### Extensions
While browser extensions are easy to install and test out, make sure you only install extensions from sources you trust.  Here are a few extensions we do recommend:

* [HTTPS Everywhere](https://www.eff.org/https-everywhere) - ensure that you only visit sites that support encrypted HTTP
* [Privacy Badger](https://privacybadger.org) - A tool from the EFF, Privacy Badger automatically learns to block invisible trackers.
* [uBlock Origin](https://github.com/gorhill/uBlock#installation) - blocks ads and the data they collect

### Form autofill :memo:
Form autofill is [known](https://www.popularmechanics.com/technology/security/a24687/autofill-bad/) [to be](https://www.techadvisory.org/2019/01/the-dangers-of-autocomplete-passwords/) [dangerous](https://thehackernews.com/2017/01/browser-autofill-phishing.html) since it can share more information than you intended without your consent. We recommend turning form autofill off in your browser:

* Apple Safari - go to settings (Safari, then Preferences in the menu), then choose the AutoFill and [uncheck all checkboxes](https://support.apple.com/guide/safari/autofill-ibrwa005/mac).
* Google Chrome - go to [address autofill settings](chrome://settings/addresses) and [payment methods settings](chrome://settings/payments)
* Mozilla Firefox - go to [privacy preferences](about:preferences#privacy) and scroll down to **Forms and Autofill**

## Email :email:
Here are some general guidelines for email:

1. If you get an email that looks suspicious, forward the email to our IT support at [security@parallelmarkets.com](mailto:security@parallelmarkets.com).
1. An email can be suspicious, even if it's from someone you know, if there's an unexpected link :link: or attachment :file_folder:.
1. Don't be afraid to reach out to anyone directly to ask if they sent something you weren't expecting (for instance, reach out on Slack).
1. Follow the guidelines for identifying phishing emails provided [in this guide](https://www.itgovernance.co.uk/blog/5-ways-to-detect-a-phishing-email).
 * The Security Team will, from time to time, simulate phishing attacks to our company email addresses to ensure everyone is aware of the threat.
 * If you receive a suspicious email, forward it to [security@parallelmarkets.com](mailto:security@parallelmarkets.com) for analysis before clicking any links or downloading any attachments.
1. When in doubt, reach out to [security@parallelmarkets.com](mailto:security@parallelmarkets.com) or `#security` in Slack.

## Security Awareness :eyes:
1. Never sign in to any Parallel Markets related account using public computers, such as library or hotel kiosks.
1. If you receive a security report of any kind (issue, customer ticket, etc.) never dismiss it as invalid. Please [contact the Security Team](#contacting-security).
1. Be familiar with the general approaches used in [social engineering](https://en.wikipedia.org/wiki/Social_engineering_(security)), and know that you could be targeted based on your access to highly sensitive personal information.  You should understand the vectors used:
 * [Vishing :phone:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Vishing) - Someone may call you asking for information.  Never share sensitive data over the phone.
 * [Phishing :fishing_pole_and_fish:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Phishing) - You may get an email that looks valid at first glance but contains an attachment with malware or a link to a site that will install malware.
 * [Smishing :iphone:](https://en.wikipedia.org/wiki/Social_engineering_(security)#Smishing) - Be aware of suspicious texts, and don't click links that look suspicious or weren't expected.

## Contacting Security

Feel free to reach out to the Security Team at any point with questions, concerns, or suspicious emails for analysis at [security@parallelmarkets.com](mailto:security@parallelmarkets.com).  You can also ask for help in the `#security` room in Slack at any time.
