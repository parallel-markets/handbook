---
parent: Security Practices
nav_order: 11
title: Devices
---
# Devices
{: .no_toc }

If you are an employee, Parallel will send you a laptop that you will use to do your work.  If you are a contractor, then you will need to provide your own device.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## All Devices :100:

Whether you are an employee with a company laptop or a contractor using your own computer, you are expected to follow these guidelines:

1. Make sure you have your screensaver set to lock your computer after a short period of inactivity (and require a password).
1. Never leave your phone or laptop unattended in a public place (for instance, [at a coffeeshop]({{ site.baseurl }}{% link work/where.md %}#coffee-shops-coffee-and-co-working-spaces)).  Even if you leave your computer alone with a stranger for only a minute, [quick physical access is all that's required to hack your computer](https://en.wikipedia.org/wiki/Physical_access).
1. Ensure all of the important files on your devices are backed up [in one of our tools]({{ site.baseurl }}{% link work/coordination.md %}#communications-tools).  All computers eventually die, act as though yours could expire any day.
1. Never download/save any customer or user data to your local computer.
1. When traveling, make sure to completely power off your computer (choose the full "shut down" option, don't just close the lid or "hibernate").
1. Do not allow your web browser (e.g. Chrome, Safari, Firefox) to store passwords when prompted. This presents an unnecessary risk and is redundant.
1. Ensure you're familiar with our [data protection]({{ site.baseurl }}{% link security/data-protection.md %}) rules and the data that should not be stored on devices

## Personal Computers :desktop_computer:

If you are using a personal computer as a contractor, you will not be able to have access to any sensitive areas of our various tools (including any of our admin areas and some third party vendors).

If you are an employee, you should not use your personal devices for any company work, with the sole exception below.  Company proprietary information (code, documents, etc) should never be downloaded to personal devices.

### Personal Mobile Phone and Tablet Usage :iphone:

Incidental personal device usage is permitted for accessing Parallel Markets' email, Slack, Google Workspace tools (Voice, Docs, Drive, etc) and [ParallelMarkets.com](https://app.parallelmarkets.com).

All personal mobile computing devices used to access the aforementioned Parallel-managed data must be passcode-enabled.  2FA will be enforced by the Security team for all employee and contractor ParallelMarkets.com and Google Workspace accounts. Mobile computing best practices dictate that these devices should be running the latest version of the operating system available, and all new patches applied. For assistance with determining the suitability of your mobile device, please contact the [Security Team](mailto:security@parallelmarkets.com).

## Company Issued Computers :computer:

All Company issued laptops will have software installed to enable:

 1. remote lock/wipe in case your laptop is stolen
 1. remote monitoring to detect and report malware or viruses
 1. remote monitoring to ensure compliance with the [Acceptable Use Policy]({{ site.baseurl }}{% link security/acceptable-use.md %})

This software should not be disabled or uninstalled.

Additional guidelines apply to company laptops; you should:

1. Have full hard drive encryption enabled (for macOS, [use FileVault](https://support.apple.com/en-us/HT204837))
1. Never connect anything to your company computer that was not purchased and approved by Parallel.
  * This rule includes anything that you physically plug into your computer - including external hubs, lights, keyboards, mice, headphones, etc.  It also includes all thumbdrives / jump drives, external hard drives, keyboards, monitors, USB devices, etc.  If you plug it in, it must have been provided by Parallel or received prior approval.
  * This includes connecting via wires (USB, Thunderbolt, etc) as well as via Bluetooth.
  * Even the most seemingly innocuous peripheral could potentially pose risk to the company. It is critically important that you seek approval before connecting *any* external device (via wires or Bluetooth). The dangers are [well documented](https://www.sciencedaily.com/releases/2019/02/190225192119.htm) by both [consumer press](https://www.cnet.com/tech/services-and-software/usb-devices-spreading-viruses/) and the [US Government](https://www.cisa.gov/uscert/sites/default/files/publications/RisksOfPortableDevices.pdf).
  * If you have a personal device you'd like to plug in (for instance, a personal monitor or USB hub), you may email [security@parallelmarkets.com](mailto:security@parallelmarkets.com) to request approval.  Make sure to include a link to the product (or the make, model, and description).

## Network :satellite:
In general, we operate with a stance of [Zero Trust](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/).  We assume that our internal networks could be compromised and seek to secure resources rather than networks.  Given the nature of our [remote workforce]({{ site.baseurl }}{% link work/index.md %}) and our utilization of cloud services, we cannot assume that resources are located within an enterprise-owned network boundary.

To help reduce networking risks, we utilize [Cloudflare for Teams](https://www.cloudflare.com/teams/).  Everyone should install and utilize the Warp client via the Self Service app.
