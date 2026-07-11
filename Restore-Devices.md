# Restore Devices after Reset
The following are for my own reference. Settings that sync back to your device when you log in with iCloud are not included.

## Setup Choices
| Prompt | Choice |
|---|---|
| Language | English |
| Select Your Country or Region | United States |
| Appearance | Default |
| Device Partially Set Up | Continue with Partial Setup |
| Transfer Your Apps & Data | Don't Transfer Anything |
| Location Services | Yes |
| Apple Analytics | Yes
| App Analytics | Yes |
| Screen Time | No (you'll set this up later) |
| Apple Intelligence | Yes |
| Choose Notifications to Summarize | News & Entertainment, Communication & Social, All Other Apps |
| Priority Notifications | Yes
| Camera Control | Light press to adjust zoom, exposure, and more |
| Action Button | Flashlight |
| Siri | Yes |
| Improve Siri & Dictation | Share Audio Recordings |
| Touch ID | Yes |
| Face ID | Yes, Don't Use Face ID with a Mask |
| Apple Pay | Yes |
| Light or Dark Display | Auto |
| Update Device Automatically | Yes |
| Multitasking & Windowing | Full Screen & Windowed Apps | 


## Apps

### Mac
From the Mac App Store, download:
```txt
Apple Configurator
Beeper
GarageBand
iMovie
Keynote: Design Presentations
Noir - Dark Mode for Safari
Numbers: Make Spreadsheets
Pages: Create Documents
Paprika Recipe Manager 3
uBlock Origin Lite
Xcode
```

From the web, download:
- [Anki](https://apps.ankiweb.net)
- [Grammarly Desktop](https://app.grammarly.com/apps)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Zoom](https://zoom.us/download)

### iPhone
Delete
```txt
Games
iTunes Store
News
Playground
Podcasts
Stocks
Tips
TV
```

Download
```txt
Chase
OnePay
Beeper
Anki
ResidentPortal
Sports
Apple Store
Support
Numbers
Pages
Keynote
Splitwise
Paprika 3
Noir
uBlock Origin Lite
Beli
Zipcar
OpenTable
AlaskaHawaiian
JetBlue
MyFitnessPal
Airbnb
Lyft
American
Target
Expedia
United
Walgreens
Walmart
State Farm
Amazon
MyChart
SpotHero
Zoom
Ventra
Venmo
Ticketmaster
PayPal
Duo Mobile
Amtrak
AMC Theatres
Illinois
FlixBus
AliExpress
ASICS
AutoZone
ChessClock
Illini
Flighty
Fly Delta
ICover: Live UIUC Bar Covers
MobileMeter
MyTSA
Nike
ParkChicago
Picsew
Southwest
Strong
TripIt
Wanderlog
GymTrakr
```

### iPad
Remove all widgets

Delete
```txt
Calculator
Calendar
Clock
Contacts
FaceTime
Files
Games
Health
Home
iTunes Store
Journal
Magnifier
Maps
Mail
Measure
Music
News
Photo Booth
Podcasts
Reminders
Shortcuts
Stocks
Tips
Translate
TV
Voice Memos
Weather
```

In **Settings > Home Screen & App Library**
- Disable **Show App Library in Dock**
- Disable **Show Suggested and Recent Apps in Dock**

Download
```txt
Noir
uBlock Origin Lite
```

Remove from Home Screen
```txt
App Store
Books
Camera
Find My
Messages
Noir
Passwords
Phone
Photos
Safari
Settings
uBlock Origin Lite
```

Move to Dock
```txt
Notes
Preview
```

In **Settings > Apple Pencil**
- Enable **Only Draw with Apple Pencil**
- Disable **Scribble**

## Development on Mac

In Visual Studio Code
- Sign in using **Continue with GitHub**
- Backup and Sync Settings using **Sign in with Github**
  
Follow the [instructions](https://brew.sh) to install Homebrew. 

In Terminal
```zsh
git config --global user.name "your name"
git config --global user.email "your email"
```

In Terminal
```zsh
mkdir Developer
cd Developer
```

Download [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/) and use it to install
```txt
Clion
DataGrip
IntelliJ IDEA
PyCharm
WebStorm
```

## Settings

### Universal Popups, Permissions, and Settings

Log into all of your apps. If prompted, allow
|Permission|Selection|When|
|---|---|---|
| "App" Would Like to Send You Notifications* | Allow | sparingly
| Allow "App" to use your location | Allow While Using App | always
| "App" would like full access to your Calendar | Allow Full Access | always
| Do you want to allow "App" to use Face ID | Allow | always
| Allow "App" to track your activity across other companies' apps and websites | Allow | always
| Allow "App" to access your visited places | Allow | always
| Allow "App" to share that you have notifications silenced when using Focus | Allow | always
| Allow "App" to find Bluetooth devices | Allow | always
| Allow "App" to Access Your Media Library | Allow | always
| "App" would like to access the Microphone | Allow | always
| "App" would like to access the Camera | Allow | always
| "App" would like to access your Motion & Fitness activity | Allow | always
| "App" would like full access to your Photo Library | Limit Access | always
|​"App” Would Like to Access Your Contacts | Allow Full Access | always
| Personalized Ads | Turn On Personalized Ads | always
| Improve Safety Features | Share My Data With Apple | always
| Allow iCloud Syncing | Allow | always

When Connecting Airpods
- Select **Announce Calls & Notifications**

In Safari
- Select **Turn On** for Show iCloud Tabs

In Settings
- In **Battery > Charging** set **Charging Limit** to **80%**
- In **Network > Firewall** enable **Firewall**
- In **Displays > Night Shift >** enable **Scheduled**, set **From To** to **Sunset to Sunrise**, and scroll **Color Temperature** to the max **More Warm**

In **Settings > Apps > Music** 
- Enable **Audio Quality > Lossless Audio**
- Set **Audio Quality > 5G & Wi-Fi Streaming** to **Lossless**
- Set **Audio Quality > Downloads** to **Lossless**
- Disable **Download over Cellular**
- Enable **Download in Dolby Atmos**
- Enable **Download Pins**
- Sign in to Home Sharing

In **Settings > Apps > Safari > Extensions**, for **uBlock Origin Lite** and **Noir**:
- Enable **Allow Extension**
- Enable **Allow in Private Browsing**
- Set **All Websites** to **Allow**

|Popup|Selection|
|---|---|
| Add (phone number) for iMessage and FaceTime | Yes |
| Wi-Fi Calling | Turn On |
| Upgrade to Wi-Fi Calling | Enable |
| Your Location Will Be Used to Make Emergency Calls | OK |

### Device-Specific Settings

On iPhone, in **Settings**
- In **Your Name**
  - In **Personal Information > Age Range for Apps** set **Share with Apps** to **Always**
  - In **iCloud > Saved to iCloud** turn iCloud **On** or enable it for all apps
- In **Camera > App Settings**
  - Set **Photographic Styles** to **Standard**
  - Set **Record Video** to **4K at 60 fps**
  - Set **Record Cinematic** to **4K at 30 fps**
- In **Notifications > Enhanced Safety Alerts** enable **Improve Alert Delivery**
- In **Screen Time > Communication Safety**
  - In **Sensitive Photos and Videos** enable **Communication Safety**
  - In **Analytics & Improvements** enable **Improve Communication Safety**
- In **Wallet & Apple Pay** 
  - Disable **Apple Cash**
  - In **Transit Cards** set an **Express Transit Card**
- In **Apps**
  - In **Chase**
    - Enable **Tap to Pay on iPhone Screen Lock**
    - Disable **Always Play Sounds**
    - Enable **Improve Tap to Pay on iPhone**
  - In **Freeform** set **Math Results** to **Off**
  - In **Journal**
    - In **Journaling Suggestions**
    - Enable **Turn On Journaling Suggestions**
    - In **Privacy & Security**
      - Enable **Sync Settings**
      - Disable **Reflection Prompts**
    - In **New Entry**
      - Enable **Show Suggested Moments**
      - Enable **Add Current Location**
      - Enable **Always Use Moment Date**
    - In **General** enable **Lock Journal**
    - Don't enable Health Access
  - In **Mail** 
    - In **Message List > Swipe Options** set **Swipe Right** to **Archive**
    - In **Messages**
      - In **Privacy Protection** enable **Protect Mail Activity**
      - In **Search > Include Results From** enable **Junk** and **Trash**
    - In **Composing**
      - Enable **Always Bcc Myself**
      - Set **Include Attachments with Replies** to **Always**
      - In **Signature** erase the default signature
  - In **Maps >**
    - Set **Preferred Type of Travel** to **Cycling**
    - In  **Extensions**
      - In **Ride Booking > Ride Booking Extensions** enable **Lyft** and **Show Rides From New Apps**
      - **Restaurant Booking > Table Booking Extensions** enable **OpenTable**
  - In **Messages**
    - Disable **Screen Unknown Senders**
    - Enable **Filter Spam**
    - In **Text Message Forwarding** enable all devices
    - Enable **Send Read Receipts**
  - In **Notes**
    - In **Password**
      - Set **Choose a Password Method** to **Use Device Passcode**
      - Enable **Use Face ID**
    - Disable **"On My iPhone" Account**
    - In **Viewing** set **Sort Checked Items** to **Automatically**
  - In **Phone > Announce Calls** set **Announce Calls** to **Headphones & Car**
  - In **Reminders**
    - In **Badge Count** enable **Include Due Today**
    - In **Categorization > Grocery Categorization** enable **Set Automatically**
  - In **Safari**
    - In **Tabs** set **Close Tabs** to **After One Day**
    - In **Privacy & Security** enable **Require Face ID to Unlock Private Browsing** and **Not Secure Connection Warning**
    - In **Settings for Websites > Location** set **Location Access On All Websites** to **Allow**
  - In **Shortcuts** enable **Private Sharing**
  - In **Translate > Languages** download all available languages
  - In **Venmo**
    - Enable **Tap to Pay on iPhone Screen Lock**
    - Disable **Always Play Sounds**
    - Enable **Improve Tap to Pay on iPhone**

On iPad, in **Settings**
- In **Camera** set **Record Video** to **4K at 60 fps**
- In **Wallet & Apple Pay** 
  - Disable **Apple Cash**
  - In **AutoFill Cards** enable **Apple Pay Compatibility**
- In **Apps**
  - In **Notes**
    - In **Password**
      - Set **Choose a password Method** to **Use Device Passcode**
      - Enable **Use Face ID**
    - Disable **"On My iPad" Account**
    - Set **Screen Unknown Callers** to **Ask Reason for Calling**
  - In **Reminders**
    - In **Badge Count** enable **Include Due Today**
    - In **Grocery Categorization** enable **Set Automatically**
  - In **Safari**
    - In **General**
      - Enable **Show Favorites Bar**
      - Enable **Show Links on Hover**
    - In **Tabs** set **Close Tabs** to **After One Day**
    - In **Privacy & Security**
      - Enable **Require Face ID to Unlock Private Browsing**
      - Enable **Not Secure Connection Warning**
    - In **Settings for Websites > Location** set **Location Access On All Websites** to **Allow**
  - In **Translate > Languages** download all available languages

On Mac
- In **Settings**
  - In **General**
    - In **Language & Region > Translation Languages** download all **Languages available for download**
    - In **Login Items & Extensions > App Background Activity** disable **Podcasts.app** and **Stocks.app**
  - In **Menu Bar > Allow in the Menu Bar**, disable **Grammarly Desktop**, **JetBrains Toolbox**, and **Zoom**
  - In **Wallpaper > Dynamic Wallpapers** select **Tahoe** or the latest OS
  - In **Keyboard** enable **Dictation**
- In **Calendar > Settings** enable **Turn on time zone support**
- In **Finder > Settings**
  - In **General**, enable **Sync Desktop & Documents folders**
  - In **Advanced**, enable **Show all filename extensions** and enable **Remove items from the Trash after 30 days**
- In **Journal > Settings > General**
  - Enable **Add Current Location**
  - Enable **Always Use Moment Date**
- In **Mail > Settings**
  - In **General** set **When searching all mailboxes, include results from** to **Trash**, **Junk**, and **Encrypted Messages**
  - In **Junk Mail** enable **Enable junk mail filtering**
- In **Maps > Settings** set **Preferred Transport Type** to **Cycling**
- In **Notes > Settings** 
  - Enable **Automatically sort checked items**
  - Disable **Enable the On My Mac account**
  - In **Locked notes** enable **Use Touch ID**
- In **Reminders > Settings > Badge Count** enable **Include due today**
