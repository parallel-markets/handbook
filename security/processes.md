---
parent: Security Practices
nav_order: 10
title: Processes
---
# Processes and Proceedures
{: .no_toc }

This page contains details on security-related processes and proceedures for both employees and contractors.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Accounts and Passwords :closed_lock_with_key:

### External Accounts

Do not sign up for a new service on behalf of Parallel without first receiving permission from [security@parallelmarkets.com](mailto:security@parallelmarkets.com)

This includes signing into web pages and web apps using your @parallelmarkets.com Google sign-in.

### Passwords
A password manager must be used for generating and storing all of your company passwords (and you should use one for your personal passwords too). A password manager lets you memorize one strong password, and then it generates and manages strong, unique passwords for every site for which you have a login.  At Parallel, all employees are required to use the password manager [1Password](https://1password.com), which should be preloaded on company devices.

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
You must use [Multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) (aka, 2 Factor Authentication, aka 2FA) for every service that provides support, including all third-party tools and company applications.  This second factor requirement can help prevent unauthorized users from being able to access accounts if one piece of evidence (such as password) is compromised.  Note that 2FA is mandatory for most Parallel services.

The following 2FA methods are acceptable:

 1. Use of an app like [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en&ref_topic=2954345) or [Authy](https://authy.com) to provide a time-based, one-time passwords (a number that changes every 30 seconds).
 1. Some services support external authentication devices like [Yubikeys](https://www.yubico.com); these are acceptable forms of 2FA as well (though not all services support them).
 1. Some services allow you to download "backup codes" that you can use instead of a time-based code in case you lose your phone (or access to your time-based password generator).  Make sure you store these somewhere safe!

> **Note:** SMS (text message) and phone call based 2FA are both vulnerable to an attack known as [a SIM Swap](https://www.wired.com/story/sim-swap-attack-defend-phone/).  These methods should not be used for 2FA unless there are no other 2FA option available for a specific service.

## Secure Browsing :computer:

### Public Computers
Never sign in to any Parallel Markets related account using public computers, such as library or hotel kiosks.

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
* MS Edge - go to [address autofill settings](edge://settings/addresses) and [payment method settings](edge://settings/payments)

## Contacting Security

Feel free to reach out to the Security Team at any point with questions, concerns, or suspicious emails for analysis at [security@parallelmarkets.com](mailto:security@parallelmarkets.com).  You can also ask for help in the `#security` room in Slack at any time.

## Training :school:

Everyone will be required to review security materials and take a quiz at least every 6 months.
