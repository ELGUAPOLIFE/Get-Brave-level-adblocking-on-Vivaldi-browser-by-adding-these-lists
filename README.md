# Get Brave level adblocking on Vivaldi browser by adding these lists ⚙️Without Any Extensions⚙️

# Filter combination for Vivaldi's Built-in Adblocker

**Important Configuration Notes:**

*   Allow all lists to use ABP Snippet rules.
*   Uncheck the option: "Rules that allow the document type cause all resources to be allowed for matching pages".
*   Avoid using unnecessary extra filters beyond those listed below, as incorrect combinations (especially with AdGuard, ABP anti-CV, and uBO filters) can reduce blocking effectiveness.

## 🔍 Tracker Blocking Sources

### Built-in Filters

*   [DuckDuckGo Tracker Radar](https://downloads.vivaldi.com/ddg/tds-v2-current.json)
*   [EasyPrivacy](https://downloads.vivaldi.com/easylist/easyprivacy-current.txt)

### Custom Trackers Filters (Must) ✨

*   [AdGuard Tracking Protection Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt) (Link from official [AdGuard site](https://adguard.com/kb/general/ad-filtering/adguard-filters/#adguard-filters))

## 🛡️ Ad Blocking Sources

### Built-in Filters

*   [ABP Anti-Circumvention List](https://downloads.vivaldi.com/lists/abp/abp-filters-anti-cv-current.txt)
*   [AdBlock Warning Removal List](https://downloads.vivaldi.com/lists/abp/antiadblockfilters-current.txt)

### Custom Adblocking Filters (Must) ✨

*   [AdGuard Base Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt) (Includes Easylist, link from official [AdGuard site](https://adguard.com/kb/general/ad-filtering/adguard-filters/#adguard-filters))
*   [HaGeZi's Pro++ DNS Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)

## Annoyance Filters (Must) ✨

*   [AdGuard Annoyances Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt) (Combines: Cookie Notices, Popups, Mobile App Banners, Other Annoyances, Widgets. Link from official [AdGuard site](https://adguard.com/kb/general/ad-filtering/adguard-filters/#adguard-filters))

## Social Media Filters (Optional)

*   [AdGuard Social Media Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt) (Link from official [AdGuard site](https://adguard.com/kb/general/ad-filtering/adguard-filters/#adguard-filters))

## Malicious Content Filters (Optional)

*   [Phishing URL Blocklist (Vivaldi)](https://malware-filter.gitlab.io/malware-filter/phishing-filter-vivaldi.txt)
*   [Malicious URL Blocklist (Vivaldi)](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-vivaldi.txt)

## Gambling & NSFW Filters (Optional)

*   [HaGeZi's Gambling DNS Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/gambling.txt)
*   [HaGeZi's NSFW DNS Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/nsfw.txt)

### Notes: Blocking YouTube and Facebook ads without an extension is exceptionally difficult because major technology companies host ads on their proprietary domains, employ dynamic content, and frequently revise their ad delivery structures.
