# Short URL Domains
This repository is a compilation of domains which are used for shortlink-services like bitly. Instead of creating yet another list of domains we make use of the awesome work by others and combine it all into one list.

## ![#ff0000](https://placehold.co/15/ff0000/ff0000) PLEASE READ:
There have been a lot of effort put into this repository to make sure the domains are all valid. Also the DNS checks are run with caution to make sure to avoid false results as much as possible. But keep in mind that things change quickly. **THERE IS NO WARRANTY GIVEN THAT THE LIST IS 100% ACCURATE. PLEASE USE IT CAREFULLY, ESPECIALLY IN PRODUCTION.**

| File                   | Description                                                      |
|:-----------------------|:-----------------------------------------------------------------|
| ~/domains.txt          | This is a combined list of all valid domains from the sources.   |
| ~/domains_sources.txt  | Sources to be used for the domains listed line-by-line.          |
| ~/excludes.txt         | Domains which should be excluded from appearing in the list.     |
| ~/excludes_sources.txt | Sources used for the excluded domains, also listed line-by-line. |

## Workflow: The way it works
A background script downloads the content of all sources from here and combines them into one list. While doing so all duplicates and invalid domains will be removed to increase the quality of the list. Later on a DNS check is run on each domain to make sure it is reachable ("online").

**What are invalid domains?**
Domains, that...
- are not in the expected format
- have invalid characters in their name
- have extensions which do not exist
- have no DNS records (A/AAAA)

## Contribute: Help to maintain the list
Please help improving this list by adding or removing sources. Send a pull request or create an issue ticket for that.

### Add / Remove a single domain
This repository only makes use of sources which already exist. To add or remove a domain, please reach out to the corresponding maintainer of the list. On the next update the domain will then be added or removed here as well.

### Whitelist domain
First try to contact the maintainer of the source which has the domain included. If they do not respond, please create an issue ticket here.