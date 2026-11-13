Network Walks Internship Week 2 Assignment: Footprinting with Kali Linux and Zenmap

This repository is documentation of my attempt at the Week 2 laboratory work as presented by NetworkWalks for the batch B084 Cybersecurity internship. In this project, I managed to successfully conduct footprinting and reconnaissance using various Kali Linux tools, along with ZenMap. 

The Kali Linux tools involved are:
whois
whatweb
nslookup
curl
wafw00f
dnsreco

First, I performed footprinting against networkwalks.com, a target I had written permission to test, using six Kali Linux tools. I used WHOIS to find the domain registration details and name servers, WhatWeb to identify the web technologies in use, and Nslookup to resolve the domain to its IP address. Then, I used Curl with the -I option to inspect the HTTP response headers, Wafw00f to check whether a web application firewall was protecting the site, and DNSRecon to enumerate its DNS records. After that, I moved on to the scanning phase on my own local network. I used Zenmap with a ping scan to discover live hosts along with their IP and MAC addresses, and then viewed the network topology. Finally, after all steps were completed, I wrote up my findings in a report, rating each observation by risk level and adding recommendations for how each could be reduced. No exploitation was performed, as these exercises were only about information gathering and host discovery.

All activities were carried out only on systems where I had written permission or that I own, and everything here is for education and research purposes only.
