# 🔍 W2-PM1: Footprinting with Multiple Kali Tools

## 🎯 Objective
To perform passive and active reconnaissance on the target domain `networkwalks.com` (with written authorization) using six different Kali Linux tools to gather maximum publicly available information.

## 🛠️ Tools Used & Step-by-Step Guide

1. **WHOIS**: Extracted domain registration details.
   * *Command:* `whois networkwalks.com`
   * *Result:* Identified Registrar as GoDaddy, and Name Servers as Hostgator.
2. **WhatWeb**: Fingerprinted the web technologies.
   * *Command:* `whatweb networkwalks.com`
   * *Result:* Discovered WordPress 7.1.4, Apache server, and target IP `192.232.216.135`.
3. **Nslookup**: Resolved the domain to its IP.
   * *Command:* `nslookup networkwalks.com`
   * *Result:* Confirmed IP Address `192.232.216.135`.
4. **Curl**: Inspected HTTP headers.
   * *Command:* `curl -I https://networkwalks.com`
   * *Result:* Revealed WordPress REST API endpoint (`/wp-json/`).
5. **Wafw00f**: Detected Web Application Firewall.
   * *Command:* `wafw00f networkwalks.com`
   * *Result:* Identified **ModSecurity (SpiderLabs)** WAF.
6. **DNSRecon**: Enumerated DNS records.
   * *Command:* `dnsrecon -d networkwalks.com`
   * *Result:* Extracted Name Servers, Mail Servers, and SRV records.

## ⚠️ Challenges & Troubleshooting
* **Challenge:** DNSRecon showed a `RequestsDependencyWarning` regarding `urllib3` version mismatch in Kali.
* **Solution:** The warning did not stop the execution. The scan completed successfully, extracting all required records. I noted this as a common Python dependency warning in Kali Linux.

## 📸 Evidence & Screenshots
* `whois1.JPG`
* `whois2.JPG`
* `whois3.JPG`
* `whatweb.JPG`
* `nslookup.JPG`
* `curl.JPG`
* `wafw00f.JPG`
* `dnsrecon.JPG`
