# Recommendations

**Customize your settings to your preferences.**

The following are my settings. Following or not following these recommendations will not affect the control you have over your devices, although it will affect [what is blocked](README.md#what-is-blocked).

## NextDNS

### Top-Level Domains (TLDs)
I recommend being restrictive with TLD blocks, to ensure foreign versions of blocked sites can't be accessed as a workaround. Blocking TLDs is easier than manually blocking each country's version of each site you want blocked.

In my **NextDNS > Security > Block Top-Level Domains (TLDs)** settings, I block all but the following
```txt
.app
.apple
.co
.com
.dev
.edu
.gov
.io
.microsoft
.net
.org
.us
```
Equivalent to this is to say that I block [these](TLDs.txt) TLDs.


### Websites, Apps, & Games
In my **NextDNS > Parental Control > Websites, Apps, & Games** settings, I block all but the following
```txt
Amazon
Zoom
```
Equivalent to this is to say that I block [these](Websites-Apps-&-Games.txt) Websites, Apps, & Games.


### Categories
In my **NextDNS > Parental Control > Categories** settings, I block [all](Categories.txt) categories.


### Denylist
In my **NextDNS > Denylist** settings, I block [these](Denylist.txt) domains. 

Creating a long Denylist may be time-consuming if done manually. Use [this](https://nextdns-blocklist-automator.dragon-tools.workers.dev) tool to automate it. You can add my list using [this](https://raw.githubusercontent.com/HyrumDickinson/digital-controls/refs/heads/main/Denylist.txt) url. 



## Screen Time


### Apps & Websites
In **Restrictions > Game Center**
- Set **Connect with Friends** to **Blocked**
- Set **Private Messaging** to **Blocked**
- Set **Adding Friends** to **Blocked**
- Set **Avatar & Nickname Changes** to **Blocked**
- Set **Multiplayer Games** to **Don't Allow**
- Set **Nearby Multiplayer** to **Blocked**
- Set **Profile Privacy Changes** to **Blocked**
- Set **Screen Recording** to **Blocked**

In the app list, block
```txt
Chess
Games
Image Playground
News
Podcasts
Stocks
Tips
TV
```


### Content & Privacy Restrictions
In **Feature Restrictions**
  - In **Siri** 
      - Set **Extensions** to **Blocked**
      - Set **Writing Assistance** to **Blocked**
      - Set **Math Assistance** to **Blocked**
  - In **Screen Distance** enable **Screen Distance**

In **Content Restrictions**
  - In **Movies**
    - Select **Don't Allow**
    - Disable **Show Movies in the Cloud**
  - In **TV Shows**
    - Select **Don't Allow**
    - Disable **Show TV Shows in the Cloud**
  - Set **Music Videos** to **Blocked**
  - Set **Music Profiles** to **Blocked**