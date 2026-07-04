# What digital controls do
*Technology can be both beneficial and harmful. Self control alone is less effective at limiting the harmful than when paired with digital controls ([see why](Why-Use-Digital-Controls.md)).*

### How blocks are enforced
1. Configuration profiles
2. Screen time settings
3. Standard/administrator account separation on Macs
4. A digital time-delay Lockbox which holds the passcodes to the other three layers

Omitting any of these 4 layers of protection renders digital controls ineffective by opening loopholes that take seconds to exploit.

### What is blocked
The following are blocked from all of your devices:
- Social media & forums
- Movies, TV & podcasts
- Games
- NSFW content
- most Artificial Intelligence
- News
- Religion
- Dating apps
- Food Delivery
- Loopholes like internet archives, torrents, and pirating

Customize your blocks to your preferences.

### How to bypass blocks

It is impossible to bypass or edit these blocks except through two methods
1. Waiting 12 hours (recommended)
2. Factory resetting your devices ([see more](Factory-Reset.md))

Once you have bypassed these blocks, you have **full control**.




# How to set up digital controls
*This guide is for Apple devices. Similar controls can be set up on Windows and Android devices, but the details on how to set them up may be different. Windows PCs have administrator/standard account separation comparable to Macs, and both Windows and Android have their own versions of Screen Time Settings. Windows and Android have their own methods to set up device supervision and install configuration profiles.*

## 1. Update and back up all devices.
*Some features necessary for this guide do not exist in older software versions. Avoid beta updates because they introduce unpredictable bugs.*

- On all of your devices, go to **Settings > General > Software Update** and install all available non-beta updates. 
- On all of your devices, screenshot your home screen, list of apps, and anything else you want to restore after factory reset. You will not restore your devices from backups.
- As a reference, see my guidelines for restoring my apps and settings [here](Restore-Devices.md).

## 2. Separate administrator / standard accounts on Mac
*Standard mode is for regular use and all restrictions implemented in this guide apply to it. Administrator mode is for unrestricted full control.*

### Factory reset your Mac
- Select **Settings > General > Transfer or Reset Mac > Erase All Content and Settings**.
- Set up your Mac as a new device. Do not restore from backup. When prompted to create an account, name it **Admin**, and disable **Allow computer account password to be reset with your Apple Account**. This will be your administrator account. 
- Continue setting up your Mac until you reach the home screen. Download your apps and restore your settings.

### Create a standard account
Go to **Settings > Users & Groups > Add User**: 
- Set **New User** to **Standard**. 
- Set **Full Name** to your first name. 
- Set a password. 
- Enable **Allow computer account password to be reset with your Apple Account**
- Click **Create User**

### Restrict Apple Configurator to administrator account only
- Download Apple Configurator from the Mac App Store. 
- With Apple Configurator closed, right-click on the Apple Configurator icon. Select **Get Info**. At the bottom right of the app info screen, select the lock icon. Scroll down to **Sharing & Permissions** and open it. 
- Set privilege of **everyone** to **No Access**. At the bottom left of the app info screen, select **+**. Select **Administrators** and set privilege to **Read & Write**. 
- Select the lock icon again and close the app info screen. 

## 3. Put iPhone and iPad in supervised mode
*Supervised Mode allows you to install configuration profiles that are unremovable which are removable only by the supervision entity or a factory reset.*

### Connect iPhone/iPad to Apple Configurator
- Open Apple Configurator on your Mac. Connect your iPhone/iPad to your Mac with a USB cable. Right-click your iPhone/iPad in Apple Configurator. 
- Select **Prepare**, then **Supervise Devices** and **Allow devices to pair with other computers**. Click **Next**. Select **Do not enroll in device management service**. 
- Do not sign into Apple School Manager or Apple Business. Select **Skip**. 
- Create an organization and name it your name. Select your organization. Select **Next**. 
- Select **Prepare**. A popup will appear that says **Configurator could not perform the requested action because ‘iPhone’ has already been prepared**. Select **Erase**.
- Wait until the **Preparing** screen in Apple Configurator disappears. Your device will factory reset to allow installation of the supervision entity.

### Set up your iPhone/iPad
- At one point your iPhone/iPad will say **iPhone/iPad Partially Set Up**, referring to the supervising organization you created. Select **Continue with Partial Setup**.
- Do not restore your iPhone from backup. Select **Don't Transfer Anything**.
- Once you reach the home screen, confirm that the top of your Settings app says **This iPhone is supervised and managed by [your name]**. Disconnect the USB cable, download your apps, and restore your settings.

### Reconnect Apple Watch to iPhone
- On your Apple Watch, go to **Settings > General > Reset > Erase All Content and Settings**.
- After your Apple Watch restarts, pair it with your iPhone. 

## 4. Get NextDNS
*This is a free DNS service that can filter all webtraffic through your devices and will be locked to them by your supervising entity. See a good explaination of NextDNS's settings options [here](https://github.com/yokoffing/NextDNS-Config). My choices differ from theirs.*

- Sign up for a free account at [NextDNS](https://nextdns) using your Screen Time Apple Account

### Security
- Enable **Threat Intelligence Feeds**
- Disable **AI-Driven Threat Detection**
- Enable **Google Safe Browsing**
- Enable **Cryptojacking Protection**
- Enable **DNS Rebinding Protection**
- Enable **IDN Homograph Attacks Protection**
- Enable **Typosquatting Protection**
- Enable **Domain Generation Algorithms (DGAs) Protection**
- Enable **Block Newly Registered Domains (NRDs)**
- Enable **Block Dynamic DNS Hostnames**
- Enable **Block Parked Domains**
- Block [these](TLDs.md) **Top-Level Domains (TLDs)**
- Enable **Block Child Sexual Abuse Material**

### Privacy
- Remove **NextDNS Ads & Trackers Blocklist**.
- Add **HaGeZi - Multi PRO++** blocklist
- Add Apple **Native Tracking Protection**
- Enable **Block Disguised Third-Party Trackers**
- Disable **Allow Affiliate & Tracking Links**

### Parental Control
- Block [these](Websites-Apps-&-Games.md) **Websites, Apps, & Games**
- Block [these](Categories.md) **Categories**
- Don't set a **Recreation Time**
- Enable **SafeSearch**
- Enable **YouTube Restricted Mode**
- Enable **Block Bypass Methods**

### Denylist
- Block [these](Denylist.md) urls

### Allowlist
- Allow [these](Allowlist.md) urls

### Settings
- Enable **Logs**
- Enable **Log clients IPs**
- Enable **Log domains**
- Disable **Block Page**
- Enable **Anonymized EDNS Client Subnet**
- Enable **Cache Boost**
- Enable **CNAME Flattening**
- Disable **Bypass Age Verification**
- Disable **Web3**

## 6. Get Configuration Profile
*Enabled by your supervision profile, configuration profiles override settings on your device and can only be removed by the supervision entity or a factory reset.*

### Download Configuration Profile
- In the NextDNS dashboard, go to **Setup > Setup Guide > Configuration Profile**. Click on the line that says **Use our Apple Configuration Profile Generator available at apple.nextdns.io**.
- Select **More options**, scroll down, enable **Prohibit Disablement**, and disable **Sign Configuration Profile**. Select **Download**. Click **OK** on the popup that appears but do not install the profile.

### Customize Configuration Profile
  In your Mac administrator account open **Apple Configurator**. At the top of the screen, select **File > Open > Downloads** and open the downloaded **.mobileconfig** file. 

In the **General** section
- Set **Security** to **Never**
- Set **Automatically Remove Profile** to **Never**

In the **Restrictions** section
- Disable **Allow Siri while device is locked**
- Disable **Show user-generated content in Siri (supervised only)**
- Disable **Allow Siri**
- Disable **Allow Siri Suggestions**
- Disable **Allow app clips (supervised only)**
- Disable **Allow Erase All Content and Settings (supervised only)**
- Disable **Allow installing configuration profiles (supervised only)**
- Disable **Allow adding VPN configurations (supervised only)**
- Enable **Force automatic date and time (supervised only)**
- Disable **Allow modifying account settings (supervised only)**
- Disable **Allow pairing with non-Configurator hosts (supervised only)**
- Disable **Allow putting into recovery mode from an unpaired device (supervised only)**
- Disable **Allow Image Playground (supervised only)**

Save your changes and move the file to your iCloud Documents folder.

### Install Configuration Profile
- Connect your iPhone/iPad to your to your Mac using a USB cable. Right-click your iPhone/iPad in Apple Configurator. Select **Add > Profiles**. Select the **.mobileconfig** file. 
- On your Mac, go to **Settings > General > Device Management**, click the **+**, and select the **.mobileconfig** file. 

Go to **Settings > General > VPN & Device Management** and confirm that you see the following settings
- **VPN** set to **Not Connected**
- **Restrictions and Proxies** and **Configuration Profile** set to **NextDNS (and some code)**
- Within **Configuration Profile** there should not be an option to remove the profile
- **Configuration Profile > Restrictions** contains 
    - Siri suggestions not allowed
    - App ratings enforced
    - Pairing with iTunes not allowed
    - Image Playground not allowed
    - Installing configuration profiles not allowed
    - Siri while locked not allowed
    - Automatic date & time enforced
    - Siri uncurated content enfoced
    - VPN creation not allowed
    - Siri not allowed

Confirm that in **Settings > General > Software Update** there is no option to install Beta Updates. Then confirm that in **Settings > General > Transfer or Reset iPhone** the  **Erase All Content and Settings** option is faded out.

## 5. Create new Apple Account for Screen Time
*This account will be used for Screen Time and will be the only account that can change Screen Time settings. It will not be used for any other purpose.*

### Get new burner phone number
- Use an app that you don't use for other burner numbers to get a new screen time phone number. I use [TextFree](https://textfree.us/), which requires a subscription to receive verification codes. Get the one-month subscription and immediately cancel it via the App Store. 

### Get a new burner email address
- Use a site that you don't use for other email accounts to get a new screen time email address using your burner phone number. I use [Yahoo](https://mail.yahoo.com/).

### Get a new Apple Account
- Use your screen time phone number and email to create a new Screen Time Apple Account. You will get a popup saying **We cannot create your account at this time**. Contact Apple Support and get the block removed.

### Log into Screen time with your new Apple Account
- On your iPhone, iPad, and Mac standard account, go to **Settings > Screen Time > App & Website Activity > Turn on Apple & Website Activity**. Confirm that **Share Across Devices** is on. 
- On your Mac, go to **Settings > Screen Time > Lock Screen Time Settings** and set a Screen Time Passcode. When prompted, sign in using your Screen Time Apple Account.

## 7. Set Screen Time Settings
*These settings allow customizability not available to configuration profiles. These settings are for Mac and will sync to your other devices. Mac's screen time interface differs slightly from iPhone/iPad.*

- Go to **Settings > Screen Time > App & Website Activity** and select **Turn on App & Website Activity**.

### Downtime
- Set **Scheduled** to **Every Day**
- Set **From** to **10:00 PM**
- Set **To** to **7:00**
- Enable **Block at Downtime**

### App Limits
- Create a **1 minute** app limit for **Journal** and enable **Block at end of limit**
- Create a **1 hour** app limit for **Music** and enable **Block at end of limit**

### Always Allowed
- Add [these](Allowed-Apps.md) apps. It may take some time for your app list to sync between your devices. If apps are missing, ensure all devices are charging and wait for them to sync.

### Screen Distance
- Enable **Screen Distance**

### Content & Privacy Restrictions
- Enable **Content & Privacy Restrictions**

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

## 8. Lockbox
*Your Lockbox Codes will be stored there and nowhere else*

Your **Lockbox Codes** are
1. Mac administrator account password
2. NextDNS account password
3. Screen Time Apple Account password
4. Screen Time Email password

- Update your Lockbox Codes so they each consist of at least 30 random letters, numbers, and symbols. Copy these passwords to your Notes app.
- Confirm that all email logins for your Lockbox Code accounts are your Screen Time Email account
- Confirm that you do not have 2FA set up on any of your Lockbox Code accounts. Delete your Screen Time Phone Number account and ensure that it is unrecoverable
- Create a Pluckeye account on their [website](https://lockbox.pluckeye.net/login).
- Select **new box**. Set **Unlock Delay** to 12 hours and **Relock Delay** to 4 hours. Set **Self-destruct date** to 2100-01-01.
- Copy the passwords from your Notes app to the **Information to store** section of your lockbox.
- Press **Create it!**.
- Confirm that you have Screen Time set up and syncing on your Mac standard account and turned off and not syncing on your Mac administrator account. 
- If you have fingerprint login set on your Mac administrator account, remove it.
- Close all apps in your Mac administrator account, reboot your Mac, and log into your Mac standard account only.
- Using your Mac, create a random four-digit Screen Time Passcode. Ensure that you do not remember the passcode. 
- Delete the Lockbox Codes from your Notes app and anywhere else you have stored them on your devices, including from **Deleted** folders. 
- Lock your Lockbox by selecting **relock**.

At this point, your digital controls setup is complete.

## 9. Maintenance
*You have full control over all settings, after the lockbox time delay.*

To adjust any layer of your digital controls, wait 12 hours to open the Lockbox
- To change Lockbox settings, open the Lockbox.
- To access your Mac administrator account, open the Lockbox to get the password.
- To change Screen Time settings, open the Lockbox to get your Screen Time Apple Account passcode and use it to reset your Screen Time Passcode.
- To change configuration profile settings, open the Lockbox to get the Mac administrator password and log in to your Mac administrator account. Then use Apple Configurator to remove, modify, or reinstall configuration profiles.