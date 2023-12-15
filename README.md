> [!NOTE]
> Beginning September 1st, 2021, there will be no more DNS checks. A small VPS was used for this, but it has now become too expensive.

---

![Version Alpha](https://img.shields.io/badge/version-alpha-blue?style=for-the-badge) ![Repo Size](https://img.shields.io/github/repo-size/Bon-Appetit/shorturl-domains?style=for-the-badge&logo=github&label=Repo%20Size)

# Short URL Domains
This collection brings together domains used in shortlink services, similar to bitly. Rather than crafting a new list, we leverage the excellent work of others and consolidate everything into a single list.

> [!CAUTION]
> The repository has seen a significant amount of effort to ensure the validity of the domains. DNS checks are handled cautiously to reduce the risk of false results. However, it's important to note that things can change rapidly. **Please bear in mind that there's no warranty regarding the accuracy of this list. Exercise caution, especially for critical use cases.**

### List of adult domains

#### block.txt
This compilation contains all domains aggregated from various sources. Each domain has undergone syntax verification, and any duplicates have been eliminated. Additionally, specific domains, such as those from whitelists, have been omitted.

**As this file is too big to view in your web browser, feel free to download this HTML file ([Gist: search.html](https://gist.github.com/CodeAlDente/ee033860b0963b34ed107e95102870f7#file-search-html)) to query domains.**

### Blacklist sources

#### bl-sources.txt
This file contains a list of website links, one after the other, pointing to domains associated with adult websites.

#### bl-custom.txt
Custom black list: Domains which aren't listed in the sources will be added here to have them included in the block list.

#### bl-custom
In this directory, you will discover dedicated blacklist files utilized to structure external data or domains in a specific format, facilitating smooth integration and functionality within background processes.

### Whitelist sources

#### wl-sources.txt
This file holds a list of website links, one after the other, leading to domains that we want to keep off the block list (usually to prevent mistakenly blocking legitimate websites).

#### wl-custom.txt
Custom white list: Domains which should be excluded from the block list will be added here.

#### wl-custom
Within this directory, you'll find specialized whitelist files. These are primarily employed to organize external data or domains into a specific structure or format for seamless integration and functionality in background processes.

### Is something missing or incorrect?
If you've got a domain that needs to be added or removed, just open an issue and drop the details there. It'd be awesome if you could include a URL pointing to a file within a GitHub Repository or Gist.

Thank you!