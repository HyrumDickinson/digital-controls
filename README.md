# What the digital controls do

Technology can be both beneficial and harmful. Self control fails to limit the harmful ([see why](Why-Use-Digital-Controls.md)). 

### 4-layer protection

1. Configuration profiles, which were originally designed for companies for controlling work-issued devices. 
2. Screen time settings, which were originally designed for parents for controlling their children’s devices. 
3. Standard/administrator account separation on Macs, which was originally designed for reducing cybersecurity risk. 
4. Digital lockboxes, which let you put the passcodes to the other three layers in container that opens a time delay after you request access.

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

## 1. Update all devices to the latest operating system.

*Some features necessary for this guide do not exist in older software versions. Beta updates introduce unpredictable bugs.*

On all of your devices, go to **Settings > General > Software Update** and install all available updates. 

## 2. Separate administrator / standard accounts on Mac

*Standard mode is for regular use and all restrictions implemented in this guide apply to it. Administrator mode is for full control and will have no restrictions.*

### Factory reset your Mac

Back up your data. Screenshot your home screen, list of apps, and any other information you want to remember. Then select **Settings > General > Transfer or Reset Mac > Erase All Content and Settings**.

Set up your Mac as a new device. Do not restore from backup. When prompted to create an account, name it **Admin**. This will be your administrator account. Continue setting up your Mac until you reach the home screen. Download your apps and restore your settings.

### Create a standard account

Go to **Settings > Users & Groups > Add User**. Set **New User** to **Standard**. Set **Full Name** to your first name. Set a password. Click **Create User**. This will be your standard account for regular use.

### Restrict Apple Configurator to administrator account only

Download Apple Configurator from the Mac App Store. 

With Apple Configurator closed, right-click on the Apple Configurator icon. Select **Get Info**. At the bottom right of the app info screen, select the lock icon. Scroll down to **Sharing & Permissions** and open the section. 

By **everyone**, set privilege to **No Access**. At the bottom left of the app info screen, select **+**. Select **Administrators** and set privilege to **Read & Write**. 

Select the lock icon again and close the app info screen. 

## 3. Put iPhone and iPad in supervised mode

*Supervised Mode allows you to install configuration profiles that can control settings and install DNS profiles.*

Back up your iPhone and iPad. Screenshot your home screen, list of apps, and any other information you want to remember. 

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

On your Mac, iPhone, and iPad, go to **Settings > Screen Time > App & Website Activity > Turn on Apple & Website Activity**. Confirm that **Share Across Devices** is on. 

On your Mac, go to **Settings > Screen Time > Lock Screen Time Settings** and set a Screen Time Passcode. When prompted, sign in using your new Apple Account.

## 5. Get NextDNS

*This is a DNS service that filters all webtraffic through your devices. It is a more robust solution than Apple's built-in Screen Time settings.*

*See a good explaination of the NextDNS settings [here](https://github.com/yokoffing/NextDNS-Config). My settings differ from theirs.*

Sign up for a free account at [NextDNS](https://nextdns.io/).

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

Select **More options**, scroll down, enable **Prohibit Disablement**, and disable **Sign Configuration Profile**. Then select **Download**. 

A popup will appear saying 







