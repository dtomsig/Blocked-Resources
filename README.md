This is a repository I created for listing domains and YouTube content (channels and videos) that I want blocked on my
browsers.

blocklist.txt is imported into the uBlock Origin extension for Firefox to block web content hosted on domains that match
a specified pattern. blocklist.txt contains three rules for each pattern. Most of the patterns are just the domain name
itself. However, some patterns use wildcards and can match multiple domain names. The purpose of each rule is to
(1) block URLs matching a pattern from appearing in DuckDuckGo, (2) block URLs matching a pattern from appearing in
Google, and (3) instruct uBlock Origin to block requests to URLs matching a pattern.

Separately, blocktube_backup.json is imported into the BlockTube extension for Firefox to block YouTube content.