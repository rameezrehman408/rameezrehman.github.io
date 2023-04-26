---
categories: pki
date: "2022-09-24T09:00:00Z"
title: PKI Training - Day3 - Advanced Cryptography 2
---


# ADSS Server CRL Monitor

# ADSS OCSP Server
* RFC 6960, RFC 5019

ADSS OCSP Server has multi-tenancy built in. This can be used to serve all 16 different CAs (in the categories of 1 for RootCA, 5 for Goverment offline, 5 for Commercial offline and 5 for Government issuing).

All servicing systems are in high availability. DBs are in Master/Slave configuration (using the Mirroring service).

Creation of a new issuing CA (expanding the footprint of the project, not scaling) may require multi-month planning and execution.

E-Passports and EMV PKI (Financial Cards) are also based on certificates.


Team:
* Security Officer
* Domain Controller
* Domain Owner
* User1 M of N
* User2 M of N
* User3 M of N




end
