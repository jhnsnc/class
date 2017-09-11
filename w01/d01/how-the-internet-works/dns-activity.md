TODO: add full description of activity

Requests to complete:
- mail.google.com/
- www.google.com/search?q=who+is+John+Cena
- en.wikipedia.org/wiki/List_of_WWE_personnel

Client
======
Use the "hosts" table below to fill out known IP Addresses

| Domain | IP Address |
|--------|------------|
|        |            |
|        |            |
|        |            |

DNS-01 (all TLDs)
=================
You are the top level DNS system.

Delegate DNS requests to the following systems:

| TLD  | ID of Responsible System |
|------|--------------------------|
| .com | DNS-02                   |
| .edu | DNS-10                   |
| .org | DNS-18                   |
| .net | DNS-26                   |

DNS-02 (.com)
=============
You are a DNS system responsible for all .com domain lookups.

Delegate DNS requests to the following systems:

| TLD  | Domain begins with | ID of Responsible System |
|------|--------------------|--------------------------|
| .com | A-D                | DNS 03                   |
| .com | E-H                | DNS 04                   |
| .com | I-L                | DNS 05                   |
| .com | M-P                | DNS 06                   |
| .com | Q-T                | DNS 07                   |
| .com | U-W                | DNS 08                   |
| .com | X-Z                | DNS 09                   |

DNS-18 (.org)
=============
You are a DNS system responsible for all .org domain lookups.

Delegate DNS requests to the following systems:

| TLD  | Domain begins with | ID of Responsible System |
|------|--------------------|--------------------------|
| .org | A-D                | DNS 19                   |
| .org | E-H                | DNS 20                   |
| .org | I-L                | DNS 21                   |
| .org | M-P                | DNS 22                   |
| .org | Q-T                | DNS 23                   |
| .org | U-W                | DNS 24                   |
| .org | X-Z                | DNS 25                   |

DNS-04 (.com E-H)
=================
You are a DNS system responsible for all .com domain lookups that start with E, F, G, or H.

Respond with the IP Address for the requested domain:

| Domain              | IP Address      |
|---------------------|-----------------|
| www.epicurious.com  | 151.101.49.239  |
| *.facebook.com      | 157.240.3.35    |
| www.google.com      | 173.194.223.147 |
| mail.google.com     | 172.217.12.37   |
| calendar.google.com | 172.217.6.142   |
| drive.google.com    | 172.217.9.14    |
| www.hotmail.com     | 65.55.118.92    |

DNS-24 (.org U-W)
=================
You are a DNS system responsible for all .org domain lookups that start with U, V, or W.

Respond with the IP Address for the requested domain:

| Domain                        | IP Address      |
|-------------------------------|-----------------|
| www.ukelelekids.org           | 184.168.221.16  |
| usvetcorps.org                | 66.96.149.1     |
| www.voluntaryworks.org        | 212.110.173.142 |
| waassociation.org             | 69.10.200.134   |
| watertownpolicefoundation.org | 198.105.244.228 |
| *.webglfundamentals.org       | 104.28.0.252    |
| *.wikipedia.org               | 208.80.153.224  |

172.217.12.37
=============
You are the server for **mail.google.com**

Respond to incoming requests with the user's Gmail inbox.

173.194.223.147
===============
You are the load balancer for **www.google.com**

Forward incoming requests to any available server from the list below.

| Server ID | IP Address      |
|-----------|-----------------|
| search-01 | 64.233.168.99   |
| search-02 | 64.233.180.104  |
| search-03 | 74.125.198.147  |
| search-04 | 108.177.9.104   |
| search-05 | 108.177.9.106   |
| search-06 | 173.194.223.105 |

64.233.168.99
=============
You are a server for **www.google.com**
**ID:** search-01

Respond to incoming requests with search results.

64.233.180.104
==============
You are a server for **www.google.com**
**ID:** search-02

Respond to incoming requests with search results.

74.125.198.147
==============
You are a server for **www.google.com**
**ID:** search-03

Respond to incoming requests with search results.

108.177.9.104
=============
You are a server for **www.google.com**
**ID:** search-04

Respond to incoming requests with search results.

108.177.9.106
=============
You are a server for **www.google.com**
**ID:** search-05

Respond to incoming requests with search results.

173.194.223.105
===============
You are a server for **www.google.com**
**ID:** search-06

Respond to incoming requests with search results.

208.80.153.224
==============
You are the server for ***.wikipedia.org**

Respond to incoming requests, pulling content from the appropriate database.

| Language | Lang. Code | Database IP Address |
|----------|------------|---------------------|
| English  | en         | 188.151.59.9        |
| German   | de         | 177.161.9.221       |
| Spanish  | es         | 107.184.71.243      |
| French   | fr         | 162.242.73.129      |
| Italian  | it         | 244.199.75.14       |

188.151.59.9
============
You are a database for articles on **en.wikipedia.org**

You retrieve data for articles in English (en).

177.161.9.221
=============
You are a database for articles on **de.wikipedia.org**

You retrieve data for articles in German (de).

107.184.71.243
==============
You are a database for articles on **es.wikipedia.org**

You retrieve data for articles in Spanish (es).

162.242.73.129
==============
You are a database for articles on **fr.wikipedia.org**

You retrieve data for articles in French (fr).

244.199.75.14
=============
You are a database for articles on **it.wikipedia.org**

You retrieve data for articles in Italian (it).

