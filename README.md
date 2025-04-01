# OSINT & Information Discovery


## Objective

The objective of this lab was to practice ethical OSINT (Open-Source Intelligence) techniques by conducting targeted searches on oneself, applying advanced Google hacking filters, and analyzing Slack workspace data using grep commands. The lab emphasized awareness of publicly available information and how attackers may gather personal details or sensitive metadata.
### Skills Learned

- Hardening web browsers for safer browsing (Firefox security settings).

- Discovering personal information exposure via breaches (email, phone, password).

- Using public search engines to perform targeted reconnaissance with Google Dorking.

- Analyzing IP, MAC address, and vendor data across systems.

- Grepping through Slack workspace exports for patterns, links, and keywords.

- Applying regex for filtering and analyzing conversation relevance in large datasets.

- Enhancing personal awareness of data leaks and digital footprint.



### Tools Used
- Firefox (Hardened) – browser used for safe searches and testing exposure.

- HaveIBeenPwned – to test exposure of email, password, and phone data breaches.

- whatismyipaddress.com / whatsmyip.org – for IP and MAC address verification.

- Google Dorking – to run advanced search queries for public OSINT collection.

- Grep (Linux CLI tool) – to filter and analyze Slack data using keyword searches and regex.

## Steps
Ref 1: Browser Hardening
Screenshot showing Firefox hardened settings per provided guide.

Ref 2: Data Breach Discovery
Screenshots of search results from HaveIBeenPwned:

Email: found in 3 breaches

Password: found in 641 breaches

Phone: no breaches

Ref 3: IP and MAC Address Checks
Screenshots comparing IP from browser-based lookup tools and IP config commands (Windows vs VM). Also includes vendor lookup from MAC address ("Azurewave Technology Inc.").

Ref 4: Google Dork Searches
Screenshots of:

Instagram URL search using allinurl

School portal sports content via intitle and intext

YouTube search on basketball

Ref 5: Slack Workspace Grep Analysis
Series of screenshots using grep:

Searching for professor’s name in Slack export

Counting frequency of specific words (e.g., “git”, “GitHub”, “labs”)

Capturing and redirecting output to a file

Using regex for advanced text filtering

