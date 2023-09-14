# Awesome Asset Discovery
[<img src="https://i1.wp.com/redhuntlabs.com/wp-content/uploads/2020/05/RedHunt-Logo-Without-Text-Dark.png?w=512&ssl=1" align="right" width="100">](https://redhuntlabs.com/)

Asset Discovery is the initial phase of any security assessment engagement, be it offensive or defensive. With the evolution of information technology, the scope and definition of assets has also evolved. 

Earlier the servers, workstations and websites were primary IT assets of an organization, but today this definition is very limiting and should include anything and everything an organization and its entities has their data on (knowingly or unknowingly). The scope of ownership could differ, but it does not limit the attack surface, for example if an organization puts out open source code on Github, they are not the owner of Github but of the data they put under their repositories. In a scenario where some organization secret has been put on this Github account, it could pose a threat equal or more than running a vulnerable service.

We have explored this aspect of **assets** in our [blog post here](https://redhuntlabs.com/blog/redifining-assets-a-modern-perspective.html).

Through this repository, we want to put out a list of curated resources which help during asset discovery phase of a security assessment engagement. We welcome suggestions and contributions from the community in terms of resources as well as categories.

**[`To know more about our Attack Surface Management platform, check out NVADR.`](https://redhuntlabs.com/nvadr)**

## Contents

 - [Content Discovery](#content-discovery)
 - [IP Address Discovery](#ip-address-discovery)
 - [Domain / Subdomain Discovery](#domain--subdomain-discovery)
 - [Email Discovery](#email-discovery)
 - [Network / Port Scanning](#network--port-scanning)
 - [Business Communication Infrastructure Discovery](#business-communication-infrastructure-discovery)
 - [Source Code Aggregators / Search - Information Discovery](#source-code-aggregators--search---information-discovery)
 - [Cloud Infrastructure Discovery](#cloud-infrastructure-discovery)
 - [Company Information and Associations](#company-information-and-associations)
 - [Internet Survey Data](#internet-survey-data)
 - [Social Media / Employee Profiling](#social-media--employee-profiling)
 - [Data Leaks](#data-leaks)
 - [Internet Scan / Archived Information](#internet-scan--archived-information)

## [↑](#contents)Content Discovery
- [rustbuster](https://github.com/phra/rustbuster): Files, directories and vhost buster written in Rust.

## [↑](#contents)IP Address Discovery

- [Mxtoolbox](https://mxtoolbox.com/BulkLookup.aspx): Bulk Domain/IP lookup tool  
- [Domaintoipconverter](http://domaintoipconverter.com/): Bulk domain to IP converter  
- [Massdns](https://github.com/blechschmidt/massdns): A DNS resolver utility for bulk lookups  
- [Googleapps Dig](https://toolbox.googleapps.com/apps/dig/): Online Dig tool by Google 
- [DataSploit (IP Address Modules)](https://github.com/DataSploit/datasploit/tree/master/ip): An OSINT Framework to perform various recon techniques 
- [Domain Dossier](https://centralops.net/co/domaindossier.aspx): Investigate domains and IP addresses 
- [Bgpview](https://bgpview.io/): Search ASN, IPv4/IPv6 or resource name 
- [Hurricane Electric BGP Toolkit](https://bgp.he.net/): Keyword to ASN lookup 
- [Viewdns](https://viewdns.info/): Multiple domain/IP tools 
- [Ultratools ipv6Info](https://www.ultratools.com/tools/ipv6Info): Multiple information related to IPv6 address 
- [Whois](https://manpages.debian.org/jessie/whois/whois.1.en.html): Command line utility usually used to find information about registered users/assignees of an Internet resource.
- [ICANN Whois](https://whois.icann.org/en): Whois service by Internet Corporation for Assigned Names and Numbers (ICANN) 
- Nslookup [Linux](https://manpages.debian.org/jessie/dnsutils/nslookup.1.en.html) / [Windows](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/nslookup): Command line utility usually used for querying the DNS records
- [bgp](https://bgp.he.net/) : Internet Backbone and Colocation Provider ... Hurricane Electric IP Transit. Our Global Internet Backbone provides IP Transit with low latency, access to thousands of networks, and dual-stack 

## [↑](#contents)Domain / Subdomain Discovery

- [RedHunt Labs Attack Surface Recon API](https://devportal.redhuntlabs.com/home): RedHunt Labs' Recon API offers comprehensive domain intelligence and reconnaissance capabilities. With access to their extensive in-house database of over 6 billion records, including domains, subdomains, third-party SaaS, data leaks, and intelligent correlations, this API empowers you to enhance your Attack Surface Management and InfoSec workflows.
- [SubFinder](https://github.com/subfinder/subfinder): SubFinder is a subdomain discovery tool that discovers valid subdomains for websites. Designed as a passive framework to be useful for bug bounties and safe for penetration testing.
- [Amass](https://github.com/OWASP/Amass): A subdomain enumeration utility 
- [Sublist3r](https://github.com/aboul3la/Sublist3r): Subdomains enumeration tool with multiple sources 
- [Aiodnsbrute](https://github.com/blark/aiodnsbrute): Asynchronous DNS brute force utility 
- [LDNS](https://github.com/NLnetLabs/ldns): A DNS library useful for DNS tool programming 
- [Dns-nsec3-enum](https://nmap.org/nsedoc/scripts/dns-nsec3-enum.html): Nmap NSE Script for NSEC3 walking 
- [Nsec3map](https://github.com/anonion0/nsec3map): A tool to NSEC and NSEC3 walking
- [Crt.sh](https://crt.sh/?a=1): Domain certificate Search 
- [Ct-exposer](https://github.com/chris408/ct-exposer): A tool to discovers sub-domains by searching Certificate Transparency logs 
- [Certgraph](https://github.com/lanrat/certgraph): A tool to crawl the graph of certificate Alternate Names 
- [Appsecco - The art of subdomain enumeration](https://github.com/appsecco/the-art-of-subdomain-enumeration): The supplement material for the book "The art of sub-domain enumeration" 
- [SSLScrape](https://github.com/jhaddix/sslScrape): A scanning tool to scrape hostnames from SSL certificates 
- [Wolframalpha](https://www.wolframalpha.com/): Computational knowledge engine 
- [Project Sonar](https://opendata.rapid7.com/sonar.fdns_v2/): Forward DNS Data 
- [Project Sonar](https://opendata.rapid7.com/sonar.rdns_v2/): Reverse DNS Data 
- [GoBuster](https://github.com/OJ/gobuster): Directory/File, DNS and VHost busting tool written in Go
- [Bluto](https://github.com/darryllane/Bluto): Recon, Subdomain Bruting, Zone Transfers

## [↑](#contents)Email Discovery

- [Hunter](https://hunter.io/): Email search for a domain  
- [Skrapp](https://www.skrapp.io/): Browser addon to find emails on Linkedin  
- [Email Extractor](https://chrome.google.com/webstore/detail/email-extractor/jdianbbpnakhcmfkcckaboohfgnngfcc?hl=en): Chrome extension to extract emails from web pages  
- [Convertcsv](http://convertcsv.com/email-extractor.htm): Online tool to extract email addresses in text, web pages, data files etc. 
- [linkedin2username](https://github.com/initstring/linkedin2username): OSINT Tool: Generate username lists for companies on LinkedIn
- [Office365UserEnum](https://bitbucket.org/grimhacker/office365userenum/src/master/):  Enumerate valid usernames from Office 365 using ActiveSync.


## [↑](#contents)Network / Port Scanning

- [Zmap](https://github.com/zmap/zmap): A fast network scanner designed for Internet-wide network surveys  
- [Masscan](https://github.com/robertdavidgraham/masscan): An asynchronously TCP port scanner  
- [ZMapv6](https://github.com/tumi8/zmap): A modified version of Zmap with IPv6 support.  
- [Nmap](https://nmap.org/): A free and open source utility for network discovery. The most popular port scanner. 

## [↑](#contents)Business Communication Infrastructure Discovery

- [Mxtoolbox](https://mxtoolbox.com/): Online tool to check mail exchanger (MX) records 
- [MicroBurst](https://github.com/NetSPI/MicroBurst): PowerShell based Azure security assessment scripts 
- [Lyncsmash](https://github.com/nyxgeek/lyncsmash): Tools to enumerate and attack self-hosted Lync/Skype for Business 
- [Enumeration-as-a-Service](https://github.com/sosdave/Enumeration-as-a-Service): Script for SaaS offering enumeration through DNS queries 
- [ruler](https://github.com/sensepost/ruler) : A tool to abuse Exchange services


## [↑](#contents)Source Code Aggregators / Search - Information Discovery

- [Github](https://github.com/search/advanced): Github Advanced Search 
- [Bitbucket](https://www.google.com/search?q=site:bitbucket.org&q=<keyword>): Bitbucket Search using Google
- [Gitrob](https://github.com/michenriksen/gitrob): Reconnaissance tool for GitHub organizations 
- [Gitlab](https://gitlab.com/explore/projects): Search Gitlab projects 
- [Publicwww](https://publicwww.com/): Source Code Search Engine 
- [builtwith](https://builtwith.com/test.com) : Web technology information profiler tool. Find out what a website is built with.

## [↑](#contents)Cloud Infrastructure Discovery

- [CloudScraper](https://github.com/jordanpotti/CloudScraper): A tool to spider websites for cloud resources (S3 Buckets, Azure Blobs, DigitalOcean Storage Space) 
- [InSp3ctor](https://github.com/brianwarehime/inSp3ctor): AWS S3 Bucket/Object finder 
- [Buckets Grayhatwarfare](https://buckets.grayhatwarfare.com/): Search for Open Amazon s3 Buckets and their contents 
- [Spaces-finder](https://github.com/appsecco/spaces-finder): A tool to hunt for publicly accessible DigitalOcean Spaces 
- [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute): A Google Storage buckets enumeration script 
- [CloudStorageFinder](https://github.com/digininja/CloudStorageFinder): Tools to find public data in cloud storage systems

## [↑](#contents)Company Information and Associations

- [Crunchbase](https://www.crunchbase.com/): Information about companies (funding, acquisition, merger etc.) and the people behind them 
- [Companieshouse](https://beta.companieshouse.gov.uk/): United Kingdom's registrar of companies 
- [OverSeas Registries](https://www.gov.uk/government/publications/overseas-registries/overseas-registries): List of company registries located around the world 
- [Opencorporates](https://opencorporates.com): Open database of companies in the world 

## [↑](#contents)Internet Survey Data

- [Project Resonance](https://redhuntlabs.com/project-resonance): RedHunt Labs’s Internet wide surveys to study and understand the security state of the Internet.
- [Project Sonar](https://opendata.rapid7.com/): Rapid7’s internet-wide surveys data across different services and protocols 
- [Scans.io](https://scans.io): Internet-Wide Scan Data Repository, hosted by the ZMap Team    
- [Portradar](https://portradar.packet.tel/): Free and open port scan data by packet.tel 

## [↑](#contents)Social Media / Employee Profiling

- [LinkedInt](https://github.com/mdsecactivebreach/LinkedInt): A LinkedIn scraper for reconnaissance 
- [Glassdoor](https://www.glassdoor.co.in/Reviews/index.htm): Company review and rating search 
- [SocialBlade](https://socialblade.com/): Track user statistics for different platforms including YouTube and Twitter 
- [Social-Searcher](https://www.social-searcher.com/): Social Media Search Engine 
- [Checkuser](https://checkuser.org): Social existence checker

## [↑](#contents)Data Leaks

- [Dumpmon](https://twitter.com/dumpmon): A twitter bot which monitors multiple paste sites for password dumps and other sensitive information  
- [Pastebin_scraper](https://github.com/Critical-Start/pastebin_scraper): Automated tool to monitor pastebin for interesting information 
- [Scavenger](https://github.com/rndinfosecguy/Scavenger): Paste sites crawler (bot) looking for leaked credentials
- [Pwnbin](https://github.com/kahunalu/pwnbin): Python based Pastebin crawler for keywords.
- [PwnedOrNot](https://github.com/thewhiteh4t/pwnedOrNot): Tool to find passwords for compromised accounts

## [↑](#contents)Internet Scan / Archived Information

- [Cachedviews](https://cachedviews.com/): Cached view of pages on the Internet from multiple sources
- [Wayback Machine](http://web.archive.org/): Internet Archive  
- [Shodan](http://shodan.io/): Search engine for Internet-connected devices  
- [Censys](https://censys.io/): Another search engine for internet-connected devices  
- [Zoomeye](https://www.zoomeye.org/): Cyberspace Search Engine  

***

## Contributing

In case you would like to add information to this repository or suggest some ideas, please use one of the following options:
- [Create an Issue](https://github.com/redhuntlabs/Awesome-Asset-Discovery/issues/new/choose).
- [Send us Pull Requests](https://github.com/redhuntlabs/Awesome-Asset-Discovery/pulls)
- Drop an email to contact@redhuntlabs.com 

## Connect

To connect with us:
- [Website](https://redhuntlabs.com)
- [Twitter](https://twitter.com/redhuntlabs)
- [Facebook](https://www.facebook.com/redhunt.labs)

## License

This work is licensed under [**CC0 1.0 Universal**](https://github.com/redhuntlabs/Awesome-Asset-Discovery/blob/master/License.md)

***
