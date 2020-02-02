---
title: ""
date: 2019-12-03T14:06:52+01:00
draft: false
---



## Background:


MikroTik is a network equipment manufacturer know for its low-cost
routers used to provide both last-mile access to home users and are
used in core network infrastructure. Although they are also known for
the security
[flaws](https://www.cvedetails.com/vendor/12508/Mikrotik.html) on
their products.

## Project Goals
  - Characterize attacks to MikroTik devices (RouterOS);
  - Automate Attack Classification based on CVE.



## Contributions

  - We reveal the landscape of MikroTik devices worldwide. See our paper (to appear);
  - We propose a realistic, easy deploy honeypot that mimics low-cost MikroTik routers;
  - We propose an automated classification of the traffic collected at
  the honeypot and discuss ways for mitigating the collected attacks.


> **Our Honeypot**: You can find our open source honeypot described
in our [repository](https://github.com/cpbscholten/routeros_honeypot).

> **Signatures**: 
We have developed
[signatures](https://github.com/joaoceron/Mikrotik/blob/master/misc/signatures.txt)
for the well-known vulnerabilities related to the MikroTik devices.
They are compatible with the Berkeley Packet Filter.


