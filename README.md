some tools I use for privacy.


# Recommended reading
- [A curated checklist of tips to protect your digital security and privacy: https://github.com/Lissy93/personal-security-checklist](https://github.com/Lissy93/personal-security-checklist): very good advices and tools.
- [The Hitchhiker’s Guide to Online Anonymity: https://anonymousplanet-ng.org/](https://anonymousplanet-ng.org/) *"You should never share real individual experiences/details using your anonymous identities that could later lead to finding your real identity".*
- [https://www.privacyguides.org/](https://www.privacyguides.org/): A guide to restoring your online privacy.

# General Tools 
| Tool     | Description |
| ----------- | ----------- |
| [Firefox](https://www.firefox.com)     |  Open-source browser. The only one based on gecko (instead of Webkit based privacy browsers). [See why this is important here](https://reddit.com/r/privacy/comments/u62468/best_browser_that_isnt_chrome/i560lmr/?context=3).      |
| [ProtonMail](https://www.protonmail.com)  | Messaging service developed by CERN researchers.       |
| [InoReader](https://inoreader.com) | RSS reader that allows you to avoid using social networks. It can handle a YouTube channel, a Facebook page, etc. Drawbacks: uses ad tracker. |
| [NewsBlur](https://newsblur.com/) | RSS reader similar to InoReader but [open-source](https://github.com/samuelclay/NewsBlur). it has some ad trackers too. |
| OpenStreetMap: [OrganicMap](https://organicmaps.app) | Avoid using google maps. |
| [openPGP](https://www.openpgp.org/) | file encryption tool, [tutorial](https://pranabdas.github.io/linux/pgp/). |

# Tracking Bypass Service

| Tool     | Description |
| ----------- | ----------- |
| [SearX-NG](https://github.com/searxng/searxng) | allows you to do google searches (on a server which can be yours) without letting google know your ip and your browser. |
| [Invidious](https://github.com/iv-org/invidious) | allows you to use Youtube (on a server which can be yours) without letting google know your ip and your browser. |
| [ViewTube](https://github.com/ViewTube/viewtube-vue) | Similar to invidious i.e. for Youtube, but with a different interface. |
| [Nitter](https://github.com/zedeus/nitter) | allows you to use Twitter (on a server which can be yours) without letting twitter know your ip and your browser. |
| [Bibliogram](https://git.sr.ht/~cadence/bibliogram-docs) | allows you to use Instagram (on a server which can be yours) without letting Facebok know your ip and your browser. |

Similar services are available for Medium, TikTok, Imgur... See a list of [alternative-front-ends](https://github.com/mendel5/alternative-front-ends).

Use them in conjunction with the LibRedirect Firefox extension (see below).


# Firefox extensions 

| Extension    | Description |
| ----------- | ----------- |
| [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | ad-blockers. | 
| [Ghostery](https://addons.mozilla.org/fr/firefox/addon/ghostery/) | ad-blockers. | 
| [Multi-container](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/) | containerize website (cookies from a particular website can be used in a single dedicated container).  | 
| [Consent-o-matic](https://addons.mozilla.org/en-US/firefox/addon/consent-o-matic/) | automatically reject all (almost all) requests to accept cookies in pop-ups. | 
| [TemporaryContainer](https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/) | every new tab is a new temporary container. | 
| [Libredirect](https://addons.mozilla.org/en-GB/firefox/addon/libredirect/) | Redirects Twitter, YouTube, Instagram and more to privacy friendly alternatives (tracking bypass service). | 

I also use [LanguageTool](https://addons.mozilla.org/fr/firefox/addon/languagetool/) and [Grammelecte](https://addons.mozilla.org/en-US/firefox/addon/grammalecte-fr/) as grammar and spell checkers.

I use [cliget](https://addons.mozilla.org/fr/firefox/addon/cliget/) to simplify the download process when you have many files to download and you are logged on a website and [updatescanner](https://addons.mozilla.org/fr/firefox/addon/update-scanner/) for checking if a web page has been modified.

# DNS 

| DNS Service | Note |
| ----------- | ----------- |
| [NextDNS](https://nextdns.io/) | fast |
| [Quad9](https://www.quad9.net/) | |

# /etc/hosts or c:\windows\system32\drivers\etc\hosts

I use [Stevenblack/Hosts](https://github.com/StevenBlack/hosts). I set 100k domain as being 0.0.0.0 i.e., "127.0.0.1", for instance google ad services.

# on iPhone 

| Tool | Description | 
| ----------- | ----------- |
| [DnsCloak](https://apps.apple.com/fr/app/dnscloak-secure-dns-client/id1452162351) | it lets me use NextDNS and put an host file from [Stevenblack/Hosts](https://github.com/StevenBlack/hosts). | 
| [Signal](https://apps.apple.com/us/app/signal-private-messenger/id874139669) | a private messaging system, which unfortunately few people use. | 
| [OrganicMap](https://organicmaps.app) | avoid using google maps. |


 





