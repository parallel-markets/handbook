---
parent: Security Practices
nav_order: 11
title: Data Protection
---
# Data Protection
{: .no_toc }

This page contains details on data classification levels with acceptable storage requirements for each.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Green :green_book:
This is any data that is publicly shareable and does not expose Parallel Markets or its customers to any harm or material impact.  This data can be stored on company systems but shared publicly.

Examples:

 * This handbook
 * Our general product descriptions on [parallelmarkets.com](https://parallelmarkets.com)
 * Public announcements and blog posts

## Yellow :lemon:
This is any data and information that should not be made publicly available that is created and used in the normal course of business. Unauthorized access or disclosure could cause minimal risk or harm and/or adversely impact Parallel Markets, its partners, employees, contractors, and customers.  This data can be stored on company devices, Google Workspace and other private cloud environments (so long as the data is not publicly accessible).

Examples:

 * General internal company communications
 * Vendor contracts
 * Internal policies or procedures
 * Business metrics (number of customers, number of users, etc.)

## Orange :orange_book:

This is any data subject to laws and regulation that should not be made generally available. This category includes any data for which unauthorized access or disclosure could cause significant or financial material loss, risk of harm to Parallel Markets if exposed to unauthorized parties, break contractual obligations and/or adversely impact Parallel Markets, its partners, users, employees, contractors and customers.  This data cannot be stored on personal devices (though there are some limited exceptions, see below).

Examples:

 * Parallel Markets intellectual property (computer code, internal product descriptions, designs, etc.)
 * Open security incidents, vulnerabilities and risks
 * Audit logs

> **Note:** Some intellectual property may be stored on company devices for those employees who need local access to perform their work.  This includes engineers and designers on the product team, for instance.  This information must be encrypted at rest and approval must be granted by the Security Team before any employee can store Orange data on their Parallel Markets' device.

## Red :red_circle:
This data is restricted and must remain confidential. This is Parallel Markets' most sensitive data and access to it should be considered privileged and must be explicitly approved. Exposure of this data to unauthorized parties could cause extreme loss to Parallel Markets and/or its users and customers. In the gravest scenario, exposure of this data could trigger or cause a business extinction event.

Examples:

 * User data (including email addresses, any submitted documentation, authentication information, etc.)
