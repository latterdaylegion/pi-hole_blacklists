# pi-hole_blacklists

Grabbed adult list from https://dsi.ut-capitole.fr/blacklists/index_en.php
```bash
ftp ftp://ftp.ut-capitole.fr/pub/reseau/cache/squidguard_contrib/adult.tar.gz
```
Extracted domains list (120Mb+ at time of writing)

Had to split up to upload to github for use in Pi-hole as I could not get other methods to work at this time.

THe adult_blacklist_custom is based on the urls list provided from UT1. I found a lot of the domains in the links were not in the main adult block list so I decided to create this custom list. There have been some false positives like google.com and github.com so just whitlist in Pi-Hole as needed. 

There may be a better way so I am open to suggestions.

# Planned:
- working to automate the download and splitting of the domains to smaller files. 