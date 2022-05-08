some tools I use for privacy.


# Recommended reading


- [A curated checklist of tips to protect your digital security and privacy: https://github.com/Lissy93/personal-security-checklist](https://github.com/Lissy93/personal-security-checklist): very good advices and tools.
- [Awesome privacy - https://github.com/pluja/awesome-privacy](https://github.com/pluja/awesome-privacy): List of free and open source privacy services as an alternative to proprietary services.
- [The Hitchhiker’s Guide to Online Anonymity: https://anonymousplanet-ng.org/](https://anonymousplanet-ng.org/) *"You should never share real individual experiences/details using your anonymous identities that could later lead to finding your real identity".*
- [https://www.privacyguides.org/](https://www.privacyguides.org/): A guide to restoring your online privacy.
- [ToSdr](https://tosdr.org/): evaluate well-known websites (e.g. facebook, wikipedia) in terms of privacy.
- [r/privacy](https://www.reddit.com/r/privacy): active community on privacy.

# General Tools 
| Tool     | Description |
| ----------- | ----------- |
| [Firefox](https://www.firefox.com)     |  Open-source browser. The only one based on gecko (instead of Webkit based privacy browsers). [See why this is important here](https://reddit.com/r/privacy/comments/u62468/best_browser_that_isnt_chrome/i560lmr/?context=3).      |
| [ProtonMail](https://www.protonmail.com)  | Messaging service developed by CERN researchers.       |
| [Signal](https://apps.apple.com/us/app/signal-private-messenger/id874139669) | A private messaging system, which unfortunately few people use. | 
| [KeePassX](https://keepass.info/) | An open-source and safe password manager. |
| [openPGP](https://www.openpgp.org/) | File encryption tool, [tutorial](https://pranabdas.github.io/linux/pgp/). |
| [openVPN](https://openvpn.net/) | Open-source vpn service (server side and client side). |



# Tracking Bypass Service

| Tool     | Description |
| ----------- | ----------- |
| [SearX-NG](https://github.com/searxng/searxng) | Allows you to do google searches (on a server which can be yours) without letting google know your ip and your browser. |
| [SimplyTranslate](https://sr.ht/~metalune/SimplyTranslate/) | private translations (Google Translate, DeepL, ICIBA and LibreTranslate). | 
| [Invidious](https://github.com/iv-org/invidious) | Allows you to use Youtube (on a server which can be yours) without letting google know your ip and your browser. |
| [ViewTube](https://github.com/ViewTube/viewtube-vue) | Similar to invidious i.e. for Youtube, but with a different interface. |
| [Teddit](https://codeberg.org/teddit/teddit) | Alternative Reddit front-end focused on privacy. |
| [Nitter](https://github.com/zedeus/nitter) | Allows you to use Twitter (on a server which can be yours) without letting twitter know your ip and your browser. |
| [Bibliogram](https://git.sr.ht/~cadence/bibliogram-docs) | Allows you to use Instagram (on a server which can be yours) without letting Facebok know your ip and your browser. |

Similar services are available for Medium, TikTok, Imgur or even Reuters... See a list of [alternative-front-ends](https://github.com/mendel5/alternative-front-ends).

Use them in conjunction with the LibRedirect Firefox extension (see below).

# Other services (available on mobile and computer)

| Tool     | Description |
| ----------- | ----------- |
| OpenStreetMap: [OrganicMap](https://organicmaps.app) | Avoid using google maps. |
| [InoReader](https://inoreader.com) | RSS reader that allows you to avoid using social networks. It can handle a YouTube channel, a Facebook page, etc. Drawbacks: uses ad tracker. |
| [NewsBlur](https://newsblur.com/) | RSS reader similar to InoReader but [open-source](https://github.com/samuelclay/NewsBlur). it has some ad trackers too. |

The website [https://12ft.io/](https://12ft.io/) helps you to bypass the paywall of news sites.

# Firefox configuration hardening & extensions 

I harden the browser settings and make it more secure by customizing [user.js](https://github.com/pyllyukko/user.js/).

| Extension    | Description |
| ----------- | ----------- |
| [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | Ad-blockers. | 
| [Ghostery](https://addons.mozilla.org/fr/firefox/addon/ghostery/) | Ad-blockers. | 
| [Multi-container](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/) | Containerize website (cookies from a particular website can be used in a single dedicated container).  | 
| [Consent-o-matic](https://addons.mozilla.org/en-US/firefox/addon/consent-o-matic/) | Automatically reject all (almost all) requests to accept cookies in pop-ups. | 
| [TemporaryContainer](https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/) | Every new tab is a new temporary container. | 
| [Libredirect](https://addons.mozilla.org/en-GB/firefox/addon/libredirect/) | Redirects Twitter, YouTube, Instagram and more to privacy friendly alternatives (tracking bypass service). | 

[NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/) is a good tool if you want a granular control of what scripts on sites are run.

Off topic: I also use [LanguageTool](https://addons.mozilla.org/fr/firefox/addon/languagetool/) and [Grammelecte](https://addons.mozilla.org/en-US/firefox/addon/grammalecte-fr/) (for french) as grammar and spell checkers. I use [cliget](https://addons.mozilla.org/fr/firefox/addon/cliget/) to simplify the download process when you have many files to download and you are logged on a website and [updatescanner](https://addons.mozilla.org/fr/firefox/addon/update-scanner/) for checking if a web page has been modified.

# DNS 

Some DNS servers protects you from security threats, blocks ads and trackers on websites and in apps.

| DNS Service | Note |
| ----------- | ----------- |
| [NextDNS](https://nextdns.io/) | Fast. |
| [Quad9](https://www.quad9.net/) | |

# /etc/hosts or c:\windows\system32\drivers\etc\hosts

I use [Stevenblack/Hosts](https://github.com/StevenBlack/hosts). I set 100k domain as being 0.0.0.0 i.e., "127.0.0.1", for instance google ad services.

# Security tools dedicated to the iPhone 

| Tool | Description | 
| ----------- | ----------- |
| [DnsCloak](https://apps.apple.com/fr/app/dnscloak-secure-dns-client/id1452162351) | It lets me use a DNS service and put an host file from [Stevenblack/Hosts](https://github.com/StevenBlack/hosts). | 
| [StrongBox](https://strongboxsafe.com/) | An open-source password manager that works with a KeePass db. |

# Screen protector 

I use a removable and reusable screen protector for each device e.g. [Amazon link](https://www.amazon.fr/ScreenForce-Removable-Privacy-Protection-MacBook/dp/B089BV9PSD/ref=sr_1_16?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=filtre%2B%C3%A9cran%2Bmacbook%2Bpro%2B13&sr=8-16&th=1).

# Hygiene

I do not connect to any personal service on a machine that is not mine. For example, I never connect to my personal mailbox on my computer lent by my employer. You never know what is installed on it and even what happens when you return the computer. 




 





