## 04 September 2023

# Information Gathering (Reconnaissance)

Information Gathering is a Specific Skill in which you gather information about target using different methods.
There are two type of Information Gathering -

- Pasive Recon
- Active Recon

## Passive Recon

Physical/Social Aspect

### Location Information

- Statellite images
- Drone recon
- Building layout (badge readers, break areas, security, fencing)

### Job Information

- Employees (name, job title, phone number, manager, etc.)
- Pictures (badge photos, desk photos, computer photos, etc.)

## Web/Host

- Target Validation (WHOIS, nslookup, dnsrecon)
- Finding Subdomains (Google Fu, dig, Nmap, Sublist3r, Bluto, crt.sh, etc.)
- Fingerprinting (Nmap, Wappalyzer, WhatWeb, BuiltWith, Netcat)
- Data Breaches (HaveIBeenPwned, Breach-Parce, WeLeakInfo)

## Our Target - [TESLA](https://bugcrowd.com/tesla)

## Email OSINT

### Tools -

#### To Find the email addresses of the target

- [Hunter.io](https://hunter.io/)

- [Phonebook.cz](https://phonebook.cz/)

- [Voilanorbert.com](https://www.voilanorbert.com/)

- [Clearbit Extention](https://clearbit.com/)

#### To Verify the email addresses of the target

- [Email Hippo](https://tools.emailhippo.com/)

- [Email Checker](https://email-checker.net/)

#### Using Breach Parse 

Breach Parse is tool which looks into the data breached and find out the email addresses that have been breached.
 
[Breach Parse](https://github.com/hmaverickadams/breach-parse)

## 05 September 2023

### [Dehashed](https://dehashed.com/)

Dehashed is a Paid Service which is used to search by Username/Email/Password [basically more specific stuff] which can give us the hashed password for 
some of the user's in the hashed format.

Try to search information when find it. For example you had a email you searched it but now you have password for the mail then try to search that 
password you may get some new information. Try this until you do not stuck in a loop with the same information.

[Hashes.com](https://hashes.com/en/decrypt/hash) 

Hashes can sometimes crack the hash but it is not that powerfull. Try it ones then go to the hard method.

## Hunting Sub-Domains

### Tools

- [Sublist3r](https://github.com/aboul3la/Sublist3r) {As of now this tools is not working currently there are alternatives(5 Spet 2023)}

- [Crt.sh](https://crt.sh/)

Challenge (To install owasp amass)

- [OWASP amass](https://github.com/owasp-amass/amass) {Alternative of the Sublist3r but More Usefull and Complicated}

- [httprobe](https://github.com/tomnomnom/httprobe) {Used to check if a perticular sub-domain exists or not}


