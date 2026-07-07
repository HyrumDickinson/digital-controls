# Recommendations

**Customize your settings to your preferences.**

The following are set in my setup. Following or not following these recommendations will not affect the control you have over your devices, although it will affect [what is blocked](README.md#what-is-blocked).

## Top-Level Domains (TLDs)
I recommend being restrictive with TLD blocks, to ensure foreign versions of blocked sites can't be accessed as a workaround. Blocking TLDs is easier than manually blocking each country's version of each site you want blocked.

In my **NextDNS > Security > Block Top-Level Domains (TLDs)** settings, I block all but the following
```txt
.app
.apple
.co
.com
.edu
.gov
.io
.net
.org
.us
```
Equivalent to this is to say that I block [these](TLDs.txt) TLDs.

## Websites, Apps, & Games
In my **NextDNS > Parental Control > Websites, Apps, & Games** settings, I block all but the following
```txt
Amazon
Zoom
```
Equivalent to this is to say that I block [these](Websites-Apps-&-Games.txt) Websites, Apps, & Games.

## Categories
In my **NextDNS > Parental Control > Categories** settings, I block [all](Categories.txt) categories.

## Denylist
In my **NextDNS > Denylist** settings, I block [these](Denylist.txt) domains. 

Creating a long Denylist may be time-consuming if done manually. Use [this](https://help.nextdns.io/t/p8yg8my/tool-nextdns-blocklist-automator-sync-custom-raw-lists-easily-100-client-side-upgrade-your-blocklist) tool to automate it. You can add my list using [this](https://raw.githubusercontent.com/HyrumDickinson/digital-controls/refs/heads/main/Denylist.txt) url. 

## Configuration Profile Settings
- Disable **Allow Siri while device is locked**
- Disable **Show user-generated content in Siri (supervised only)**
- Disable **Allow Siri**
- Disable **Allow Siri Suggestions**
- Disable **Allow Image Playground (supervised only)**

## Downtime
If you are a student, I recommend Downtime start after midnight so it never interferes with assignment deadlines.
- Set **Scheduled** to **Every Day**
- Set **From** to **12:15 AM**
- Set **To** to **7:00 AM**

## App Limits
- I have a **1 hour** App Limit for **Music**, because it's great for exercise but makes studying less efficient.
  
- I have a **1 minute** App Limit for **Journal** to allow pasting in new entries and disallow reading old entries.

- I have a **0 minute** App Limit for **Games**, **Chess**, **Apple TV**, **Podcasts**, and **News**.

## Always Allowed
The more limited your Always Allowed list is, the more effective Downtime is. 

This is my list
```txt
Phone
Messages
FaceTime
Maps
```
In addition to what you list, Clock, Wallet, Settings, Health, Find My, Home, Fitness, Watch, and Files will always be available. 

## Content & Privacy Restrictions

### App Store, Media, Web, & Games
- Set **Access to Web Content** to **Limit Adult Websites** and select **Customize**
- Add [these](Restricted-Web-Content.md) urls to the **Restricted** list and select **Done**
- Disable **Allow Music Profiles**
- Disable **Allow Music & TV Shared Libraries**
- Disable **Allow Adding Friends**
- Disable **Allow Connect with Friends**
- Disable **Allow Private Messaging**
- Disable **Allow Avatar & Nickname Changes**
- Disable **Allow Profile Privacy Changes**
- Set **Allow Multiplayer Games With** to **No One**
- Disable **Allow Nearby Multiplayer**

### Intelligence & Siri
- Disable **Image Creation**
- Disable **Writing Tools**
- Disable **Intelligence Extensions**
- Disable **Allow Siri & Dictation**
- Disable **Allow Explicit Language in Siri and Dictionary**
- Disable **Allow Web Search Content in Siri**
- Disable **Math Results**

### Store Restrictions
- Set **Movies** to **Don't Allow**
- Set **TV Shows** to **Don't Allow**
- Disable **Allow Music Videos**
- Disable **Allow Installing Apps**
- Disable **Allow Deleting Apps**
- Disable **Allow In-app purchases**

### App & Feature Restrictions
- Disable **Allow Book Store**
- Disable **Allow iTunes Store**
- Disable **Allow Podcasts**
- Disable **Allow News**