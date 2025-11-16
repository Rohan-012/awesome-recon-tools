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
## ▶️ Usage (crt.sh Subdomain Enumeration)

The crt.sh subdomain module is included automatically when you run the main toolkit.

Enter domain (example.com):
example.com


