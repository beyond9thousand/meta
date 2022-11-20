---
icon: lock
tags: [privacy, safety]
order: 99
---

!!!
Mobile apps mentioned here are deliberately excluded from [mobile apps](/guides/software/#mobile-apps) to make them more distinctly visible
!!!

### :icon-key: Two-factor authentication apps [!badge variant="danger" text="Critical"]

[Two-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication#Mobile_phone-based_authentication) or **2FA** is an additional layer of security used to ensure that people attempting to access an online account are who they claim to be. Users are required to provide a secondary password-like phrase, usually through a backup code or a periodically generated 6-digit number that is unique to every account.

This in turn ensures that your accounts remain protected in the event of password breaches or mishandling due to human error on the user end.

!!!danger
Using private messaging services, including social media platforms without activating 2FA is extremely dangerous. You are practically asking to get **hacked, impersonated and doxxed online.** It is highly advised against turning-off 2FA for convenience purposes.
!!!

- [andOTP](https://github.com/andOTP/andOTP) [!badge variant="warning" text="Unmaintained"](https://forum.xda-developers.com/t/app-4-4-open-source-andotp-open-source-two-factor-authentication-for-android.3636993/post-87021655)
- [Aegis](https://github.com/beemdevelopment/Aegis)

### :icon-circle-slash: Ad-blocking

+++ Android

==- Private DNS [!badge variant="ghost" text="Suggested"]

Starting with android 9, you have the option of enabling seamless ad-block system wide. This is achieved using [private DNS](https://adguard.com/en/blog/adguard-dns-announcement.html) providers.

To enable ad-blocking through private DNS:

- Go to **Settings > Network and Internet > Advanced > Private DNS**
- Select the field for entering private DNS provider
- To use [AdGuard's](https://en.wikipedia.org/wiki/AdGuard) resolver, enter `dns.adguard.com`
- Save your settings and continue browsing

[!button size="s" text="Other providers"](https://dnsprivacy.org/public_resolvers/#dns-over-tls-dot)

!!!
Advertisements shown inside major social media apps are an exception to this feature since they do not fall under consistent [host names](https://en.wikipedia.org/wiki/Ad_blocking#Hosts_file_and_DNS_manipulation) required for enforcing ad-blocking
!!!

===

+++

### :icon-mail: Temporary email services

Use a disposable email address instead of your work or personal account when unsure about signing up on a new service. An added benefit of using throaway email addresses is that you avoid ending up in random news mail letter subscriptions & other such annoyances.

- [Alt Address](https://altaddress.org/) [!badge variant="ghost" text="Suggested"]
- [Guerilla Mail](https://www.guerrillamail.com/)

### :icon-search: Search Engines

> Listed in decreasing order of preference based on privacy policy and performance

==- Searx [!badge variant="ghost" text="Suggested"]
[Searx](https://github.com/searx/searx) is a free and open-source metasearch engine that uses the [GNU Affero General Public License version 3](https://www.gnu.org/licenses/agpl-3.0.en.html) to protect its users' privacy.
To that end, Searx does not share users' IP addresses or search history with the search engines that provide results. Search engine tracking cookies are blocked, preventing user-profiling-based results modification.

> Any user may run their own [instance](https://linuxreviews.org/Searx#What_it_is_and_isn.27t) of Searx to maximise privacy, avoid congestion on public instances, preserve customised settings even if browser cookies are cleared, allow auditing of the source code being run, and so on.

[!button size="s" text="Instances"](https://searx.space/)

===

- [Startpage](https://www.startpage.com/)
- [Duckduckgo](https://duckduckgo.com/) [!badge variant="danger" text="Controversial"](https://9to5mac.com/2022/05/25/duckduckgo-privacy-microsoft-permission-tracking/)
