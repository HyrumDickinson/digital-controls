# What digital controls do

*Technology can be both beneficial and harmful. Self control fails to limit the harmful ([see why](Why-Use-Digital-Controls.md)).*

### 4-layer protection

1. Configuration profiles, which were originally designed for companies for controlling work-issued devices. 
2. Screen time settings, which were originally designed for parents for controlling their children’s devices. 
3. Standard/administrator account separation on Macs, which was originally designed for reducing cybersecurity risk. 
4. Digital lockboxes, which let you put the passcodes to the other three layers in a secure container that opens a time delay after you request access.

Omitting any layer of protection renders these digital controls ineffective by opening signficant loopholes that take mere seconds to exploit.

### What it's like to have digital controls

The following are blocked from all of your devices:
- Social media & forums
- Movies & TV & Podcasts
- Games
- Internet search engines
- Artificial Intelligence
- News
- Religion
- Dating apps
- Loopholes like internet archives, torrents, and pirating sites

It is impossible to get around these blocks except through two methods
1. Waiting 12 hours (recommended)
2. Factory resetting your devices ([see more](Loophole.md))

When you have gotten around these blocks, you have **full control**.

All blocks and settings, including the lockbox wait time, are 100% customizable to your personal preferences during setup and while you have full control.


# How to set up digital controls on Apple devices

## 1. Update and back up all devices.

*Some features necessary for this guide do not exist in older software versions. Beta updates introduce unpredictable bugs.*

On all of your devices, go to **Settings > General > Software Update** and install all available updates. 

On all of your devices. screenshot your home screen, list of apps, and any other information you want to keep after factory reset.

As a reference, see my guidelines for restoring my apps and settings on Mac [here] (Restore-Devices.md).

## 2. Separate administrator / standard accounts on Mac

*Standard mode is for regular use and all restrictions implemented in this guide apply to it. Administrator mode is for full control and will have no restrictions.*

### Factory reset your Mac

Then select **Settings > General > Transfer or Reset Mac > Erase All Content and Settings**.

Set up your Mac as a new device. Do not restore from backup. When prompted to create an account, name it **Admin**, and disable **Allow computer account password to be reset with your Apple Account**. This will be your administrator account. 

Continue setting up your Mac until you reach the home screen. Download your apps and restore your settings.

### Create a standard account

Go to **Settings > Users & Groups > Add User**: 
- Set **New User** to **Standard**. 
- Set **Full Name** to your first name. 
- Set a password. 
- Enable **Allow computer account password to be reset with your Apple Account**
- Click **Create User**

### Restrict Apple Configurator to administrator account only

Download Apple Configurator from the Mac App Store. 

With Apple Configurator closed, right-click on the Apple Configurator icon. Select **Get Info**. At the bottom right of the app info screen, select the lock icon. Scroll down to **Sharing & Permissions** and open the section. 

By **everyone**, set privilege to **No Access**. At the bottom left of the app info screen, select **+**. Select **Administrators** and set privilege to **Read & Write**. 

Select the lock icon again and close the app info screen. 

## 3. Put iPhone and iPad in supervised mode

*Supervised Mode allows you to install configuration profiles that can control settings and install DNS profiles.*

### Connect iPhone/iPad to Apple Configurator

Open Apple Configurator on your Mac. Connect your iPhone to your Mac with a USB cable. Right-click your iPhone in Apple Configurator. 

Select **Prepare**, then **Supervise Devices** and **Allow devices to pair with other computers**. Click **Next**. Select **Do not enroll in device management service**. 

Do not sign into Apple School Manager or Apple Business. Select **Skip**. 

Create an organization and name it your name. Select your organization. Select **Next**. 

Select **Prepare**. A popup will appear that says **Configurator could not perform the requested action because ‘iPhone’ has already been prepared**. Select **Erase**.

Wait until the **Preparing** screen in Apple Configurator disappears. 

### Set up your iPhone/iPad

At one point your iPhone will say **iPhone Partially Set Up**, referring to the supervising organization you created. Select **Continue with Partial Setup**.

Do not restore your iPhone from backup; set it up as a new device.

Once you reach the home screen, confirm that a **This iPhone is supervised and managed by [your name]** label is at the top of your **Settings** app. You may now disconnect the USB cable. Download your apps and restore your settings.

### Reconnect Apple Watch to iPhone

On your Apple Watch, go to **Settings > General > Reset > Erase All Content and Settings**.

After your Apple Watch restarts, pair it with your iPhone. 

## 4. Create new Apple Account for Screen Time

*This account will be used for Screen Time and will be the only account that can change Screen Time settings. It will not be used for any other purpose.*

### Get new burner phone number

Use an app (that you don't use for other burner numbers) like [TextFree](https://textfree.us/) to get a new burner phone number. A subscription is required to receive verification codes. Get the one-month subscription and immediately cancel it via the App Store. 

### Get a new burner email address

Use a site (that you don't use for other email accounts) like [Yahoo](https://mail.yahoo.com/) to get a new burner email address using your burner phone number.

### Get a new Apple Account

Use your burner email address and phone number to create a new Apple Account. You will get a popup saying **We cannot create your account at this time**. Contact Apple Support and they will remove the block. 

### Log into Screen time with your new Apple Account

On your iPhone, iPad, and Mac standard account, go to **Settings > Screen Time > App & Website Activity > Turn on Apple & Website Activity**. Confirm that **Share Across Devices** is on. 

On your Mac, go to **Settings > Screen Time > Lock Screen Time Settings** and set a Screen Time Passcode. When prompted, sign in using your new Apple Account.

## 5. Get NextDNS

*This is a DNS service that filters all webtraffic through your devices. It is a more robust solution than Apple's built-in Screen Time settings.*

*See a good explaination of the NextDNS settings [here](https://github.com/yokoffing/NextDNS-Config). My settings differ from theirs.*

Sign up for a free account at [NextDNS](https://nextdns using your Screen Time Apple Account.

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
- Block [these](TLDs.md) **Top-Level Domains (TLDs)**.
- Enable **Block Child Sexual Abuse Material**

### Privacy

- Remove **NextDNS Ads & Trackers Blocklist**.
- Add **HaGeZi - Multi PRO++** blocklist
- Add Apple **Native Tracking Protection**
- Enable **Block Disguised Third-Party Trackers**
- Disable **Allow Affiliate & Tracking Links**

### Parental Control

- Block [these](Websites-Apps-&-Games.md) **Websites, Apps, & Games**.
- Block [these](Categories.md) **Categories**.
- Don't set a **Recreation Time**.
- Enable **SafeSearch**
- Enable **YouTube Restricted Mode**
- Enable **Block Bypass Methods**

### Denylist

- Block [these](Denylist.md) urls.

### Allowlist

- Allow [these](Allowlist.md) urls.

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

### Create Configuration Profile

In the NextDNS dashboard, go to **Setup > Setup Guide > Configuration Profile**. Click on the line that says **Use our Apple Configuration Profile Generator available at apple.nextdns.io**.

Select **More options**, scroll down, enable **Prohibit Disablement**, and disable **Sign Configuration Profile**. Then select **Download**. Click **OK** on the popup that appears but do not install the profile.

Open **Apple Configurator**. At the top of the screen, select **File > Open > Downloads** and open the **.mobileconfig** file. 

### Customize Configuration Profile

In the **General** section,
- Set **Security** to **Never**
- Set **Automatically Remove Profile** to **Never**

In the **Restrictions** section,
- Disable **Allow Siri**
- Disable **Allow Siri Suggestions**
- Disable **Allow Erase All Content and Settings (supervised only)**
- Disable **Allow installing configuration profiles (supervised only)**
- Disable **Allow adding VPN configurations (supervised only)**
- Enable **Force automatic date and time (supervised only)**
- Disable **Allow pairing with non-Configurator hosts (supervised only)**
- Disable **Allow putting into recovery mode from an unpaired device (supervised only)**
- Disable **Allow Image Playground (supervised only)**

Save your changes and move the file to your iCloud Documents folder.

### Install Configuration Profile

Connect your iPhone/iPad to your to your Mac using a USB cable. Right-click your iPhone/iPad in Apple Configurator. Select **Add > Profiles** and the **.mobileconfig** file. 

On your Mac administrator account, go to **Settings > General > Device Management**, click the **+**, and select the **.mobileconfig** file. 

Go to **Settings > General > VPN & Device Management** and confirm that you see the following settings.
- **VPN** set to **Not Connected**
- **Restrictions and Proxies** and **Configuration Profile** set to **NextDNS (and some code)**
- Within **Configuration Profile** no option to remove the profile
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

Confirm that in **Settings > General > Software Update** there is no option to install Beta Updates.

Confirm that in **Settings > General > Transfer or Reset iPhone** the  **Erase All Content and Settings** option is faded out.

## 7. Set Screen Time Settings

*These settings allow some customizability not available in configuration profiles. The instructions are for Mac; whose Screen Time interface differs slightly from iPhone/iPad**

Go to **Settings > Screen Time > App & Website Activity** and select **Turn on App & Website Activity**.

### Downtime

- Set **Scheduled** to **Every Day**
- Set **From** to **10:00 PM**
- Set **To** to **7:00**
- Enable **Block at Downtime**

### App Limits

- Create a **1 minute** app limit for **Journal** and enable **Block at end of limit** is enabled
- Create a **1 hour** app limit for **Music** and enable **Block at end of limit** is enabled

### Always Allowed

- Add [these](Allowed-Apps.md) apps.

### Screen Distance

- Enable **Screen Distance**

### Content & Privacy Restrictions

- Enable **Content & Privacy Restrictions**

### App Store, Media, Web, & Games

- Set **Access to Web Content** to **Limit Adult Websites** and select **Customize**
- Add [these](Restricted-Web-Content.md) urls to the **Restricted** list and select **Done**.
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

## 8. Other settings

*Make these and any other changes you need admin access for*

- Pin your websites and clear your browser history.
- Clear your Google data and turn off data collection
- On your iPhone, iPad, and Mac, install **Ublock Origin Lite** and **Noir** from the App Store. Then go to **Settings > Apps > Safari > Extensions** and for each app, enable **Allow Extension** and **Allow in Private Browsing**, and set **All Websites** to **Allow**.

## 9. Lockbox

*Your Lockbox Passwords, which you will store there and nowhere else, are the passwords to your
1. Screen Time Email account
2. Screen Time Apple Account
3. NextDNS account
4. Mac administrator account*

Set each of your Lockbox Passwords to consist of random letters, numbers, and symbols, and be at least 30 characters long. Copy the passwords to your Notes app.

Create a Pluckeye account on their [website](https://lockbox.pluckeye.net/login).

Select **new box**. Set **Unlock Delay** to 12 hours and **Relock Delay** to 4 hours. Set **Self-destruct date** to 2100-01-01.

Copy the passwords from your Notes app to the **Information to store** section of your lockbox.

Press **Create it!**.

Close all apps in your Mac administrator account, reboot your Mac, and log into your Mac standard account only.

Using your Mac, mash your keyboard with your eyes closed and arms crossed to change your four-digit screen time passcode to something random. Confirm that you are not able to remember your screen time passcode by attempting to change it again.

When you are ready, delete the Lockbox Passwords from your Notes app and anywhere else you have stored them on your devices, including from applicable *Deleted* folders. 

At this point, your digital controls are complete.

## 10. Maintenance

*You have full control over all settings, after the lockbox time delay.*

To change Lockbox settings, open the lockbox.

To change Screen Time settings, reset your Screen Time Passcode using your Screen Time Apple Account. 

To change configuration profile settings, modify the **.mobileconfig** file in Apple Configurator using your Mac administrator account. Then use Apple Configurator to remove the old profile from your iPhone and iPad and install the new one. Switch profiles for your Mac using the Administrator account's Settings app.











