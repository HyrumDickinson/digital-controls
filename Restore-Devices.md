# Restore Devices after Reset

The following are my guidelines for restoring device apps and settings after a reset. Customize your guidelines to your preferences.


## Setup Choices

### Mac
- Select **English** for Language
- Select **United States** for Select Your Country or Region
- Select **Set up as new** for Transfer Your Data to This Mac
- Ignore the Accessibility settings
- Follow the instructions in README.md for Create a Mac Account
- Log in to iCloud and **Agree** to the Terms and Conditions
- Select **Customize Settings** for **Your Mac Settings**
- Select **Enable Location Services on this Mac**
- Select **Share Mac Analytics with Apple** and **Share crash and usage data with app developers** for Analytics
- Select **Set Up Later** for Screen Time
- Set up Apple Intelligence
- **Choose Notifications to Summarize**
  - **News & Entertainment**
  - **Communication & Social**
  - **All Other Apps**
- Set up Siri
- Select **Share Audio Recordings** for Improve Siri & Dictation
- Set up Touch ID
- Set up Apple Pay
- Select **Auto** for Choose Your Look
- Select **Continue** for Update Mac Automatically

### iPhone
- Select **English** for Language
- Select **United States** for Select Your Country or Region
- Select **Default** for Appearance
- Select **Continue with Partial Setup** at iPad Partially Set Up
- Select **Don't Transfer Anything** at Transfer Your Apps & Data
- Set up Face ID and select **Don't Use Face ID with a Mask**
- Sign in using your Apple Account
- **Agree** to the Terms and Conditions
- **Customize** Your iPad Settings
- Select **Continue** for Update Your iPad Automatically
- Select **Turn On Location Services**
- Set up Apple Pay
- Select **Set Up Later in Settings** for Screen Time
- Select **Share with Apple** for iPhone Analytics
- Select **Share with App Developers** for App Analytics
- Select **Auto** for Light or Dark Display
- Set up Apple Intelligence
- **Choose Notifications to Summarize**
  - **News & Entertainment**
  - **Communication & Social**
  - **All Other Apps**
- Select **Turn On Priority Notifications**
- Enable **Light press to adjust zoom, exposure, and more** for Camera Control
- **Customize** Action Button and set it to **Flashlight**
- Set up Siri
- Select **Share Audio Recordings** for Improve Siri & Dictation

### iPad
- Select **English** for Language
- Select **United States** for Select Your Country or Region
- Select **Default** for Appearance
- Select **Continue with Partial Setup** at iPad Partially Set Up
- Select **Don't Transfer Anything** at Transfer Your Apps & Data
- Set up Face ID
- Sign in using your Apple Account
- **Agree** to the Terms and Conditions
- **Customize** Your iPad Settings
- Select **Continue** for Update Your iPad Automatically
- Select **Turn On Location Services**
- Set up Apple Pay
- Select **Set Up Later in Settings** for Screen Time
- Select **Share with Apple** for iPad Analytics
- Select **Share with App Developers** for App Analytics
- Select **Auto** for Light or Dark Display
- Set up Siri
- Select **Share Audio Recordings** for Improve Siri & Dictation
- Select **Full Screen & Windowed Apps** for Multitasking & Windowing


## Apps

### Mac
From the Mac App Store, download:
- Apple Configurator
- Beeper
- GarageBand
- iMovie
- Keynote: Design Presentations
- Noir - Dark Mode for Safari
- Numbers: Make Spreadsheets
- Pages: Create Documents
- Paprika Recipe Manager 3
- uBlock Origin Lite
- Xcode

From the web, download:
- [Anki](https://apps.ankiweb.net)
- [Grammarly Desktop](https://app.grammarly.com/apps)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Zoom](https://zoom.us/download?os=mac)

### iPhone
Delete the following apps:
- Games
- iTunes Store
- News
- Playground
- Podcasts
- Stocks
- Tips
- TV

Remove these apps from the Home Screen:
- App Store

Download these apps:
- Apple Store
- Beeper
- Support

### iPad
Remove all widgets

Delete the following apps:
- Calculator
- Calendar
- Clock
- Contacts
- FaceTime
- Files
- Games
- Health
- Home
- iTunes Store
- Journal
- Magnifier
- Maps
- Mail
- Measure
- Music
- News
- Photo Booth
- Podcasts
- Reminders
- Shortcuts
- Stocks
- Tips
- Translate
- TV
- Voice Memos
- Weather

In **Settings > Home Screen & App Library**
- Disable **Show App Library in Dock**
- Disable **Show Suggested and Recent Apps in Dock**

Download the following apps from the App Store:
- Noir
- uBlock Origin Lite

Remove these apps from the Home Screen:
- App Store
- Books
- Camera
- Find My
- Grammarly
- Messages
- Noir
- Passwords
- Phone
- Photos
- Safari
- Settings
- uBlock Origin Lite

Move the following apps to the Dock
- Notes
- Preview
- Docs
- Sheets
- Slides
- Miro
- FreeForm


## Settings

### Universal Popups, Permissions, and Settings

Log into all of your apps. If prompted, allow
- To **"App" Would Like to Send You Notifications** choose **Allow** sparingly
- To **Allow "App" to use your location** choose **Allow While Using App** always
- To **Personalized Ads** choose **Turn On Personalized Ads** always
- To **"App" would like full access to your Calendar** choose **Allow Full Access** always
- To **Do you want to allow "App" to use Face ID** choose **Allow** always
- To **Allow "App" to track your activity across other companies' apps and websites** choose **Allow** always
- To **Allow "App" to access your visited places** choose **Allow** always
- To **Allow "App" to share that you have notifications silenced when using Focus** choose **Allow** always
- To **"App" would like to access the Microphone** choose **Allow** always
- To **"App" would like to access the Bluetooth** choose **Allow** always
- To **"App" would like to access the Camera** choose **Allow** always
- To **"App" would like to access your Motion & Fitness activity** choose **Allow** always
- To **"App" would like full access to your Photo Library** choose **Limit Access** always
- To **Improve Safety Features** choose **Share My Data With Apple** always
- Allow **iCloud Syncing** always

Popups
- Select **Yes** for **Add (phone number) for iMessage and FaceTime?**
- At the **Wi-Fi Calling** popup select **Turn On**
- At the **Upgrade to Wi-Fi Calling** popup select **Enable**
- Select **Enable** for **Upgrade to Wi-Fi Calling?**
- Select **OK** for **Your Location Will Be Used to Make Emergency Calls**

When Connecting Airpods
- Select **Announce Calls & Notifications**

In Safari
- Select **Turn On** for Show iCloud Tabs

In Settings
- In **Battery > Charging** set **Charghe Limit** to **80%**
- In **Network > Firewall** enable **Firewall**

In **Settings > Apps > Music** 
- Enable **Audio Quality > Lossless Audio**
- Set **Audio Quality > 5G & Wi-Fi Streaming** to Lossless
- Set **Audio Quality > Downloads** to Lossless
- Disable **Download over Cellular**
- Enable **Download in Dolby Atmos**
- Enable **Download Pins**
- Enable **Automatic Downloads**
- Sign in to Home Sharing


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