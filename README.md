# pentest-tools
A collection of reconnaissance and security research tools for penetration testing and bug bounty hunting


⚠️ **Use only on assets you own or have permission to test.**  
Unauthorized scanning is illegal.

---

## Features
- Subdomain enumeration (Passive – crt.sh)
- DNS Records lookup
- Safe port scanning (Predefined list)
- Technology fingerprinting from HTTP headers
- WHOIS Lookup
- URL extraction from webpages
- Website screenshotting
- Modular, extensible structure

## 🔎 Subdomain Enumeration (crt.sh)

The toolkit includes a passive subdomain enumeration module powered by **crt.sh**,  
a public certificate transparency log search engine.

crt.sh allows you to discover **subdomains that appear in SSL certificates**,  
making it a powerful and completely passive reconnaissance technique.
## Usage crt.sh

The crt.sh subdomain module is included automatically when you run the main toolkit.

Enter domain (example.com):
example.com
![ESC2](https://github.com/Rohan-012/awesome-recon-tools/blob/33a6fc5087251d0dac608b858efcbb4e52668a47/images/crt.st.png)




## 🔍 Censys Asset Discovery

Censys is a powerful search engine for discovering public-facing hosts, services,  
certificates, and Internet assets. It collects data by scanning the entire  
IPv4 and IPv6 space daily.

This module lets you query **Censys Search API** to gather:

- Public IP information  
- Open ports  
- Service banners  
- Certificates  
- Hostnames  
- Technologies exposed  

This helps you expand and validate your reconnaissance results.

---

![ESC2](https://github.com/Rohan-012/awesome-recon-tools/blob/25d1197eb71c3793d03f56eff182e974b1d8b9c0/images/censys.png)

## 🔍 gobuster

Nice tool for brute forcing file/folder paths on a victim website.

**Install:** 

```bash
sudo apt install gobuster
```

**Usage:** 

```bash
gobuster dir -u "https://google.com" -w /usr/share/wordlists/dirb/big.txt --wildcard -b 301,401,403,404,500 -t 20
```

![ESC2](https://github.com/Rohan-012/awesome-recon-tools/blob/dca033f5fea87c7d3d10f006db893f7c46a0d550/images/gobuster.png)


