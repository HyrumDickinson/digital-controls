# Factory reset is a known loophole / failsafe

## How to factory reset

While digital controls are on, factory reset using your device's settings app is impossible. However, barring complicated solutions that I have not implemented, it is always possible to factory reset an Apple device that you have physical access to. 

Options include
- Factory reset from your iCloud account online
- Factory reset using your Mac

Factory reset is not recommended because a reset from a device with digital controls disallows restoring from a backup. Manually reinstalling apps and resetting settings is inconvenient. Additionally, restoring digital controls after a reset that wipes them takes several hours. In contrast, adjusting settings to unblock or reblock content after waiting for the 12-hour lockbox wait takes seconds.

However, in a pinch when you do not wait 12 hours to access blocked content, factory reset is faster. You can access anything after a reset within about half an hour after starting. 

## Options to prevent factory reset from being a way to get around digital controls

### 1. Block factory reset when you have physical access to a device
This is impossible.

### 2. Block setting a device up after factory reset
This is impossible.

Apple devices are Activation Locked to the iCloud account that is signed in to them. This is so a thief who steals your device can't wipe it and set it up as theirs, unless you give them your Apple Account password. You could try to use this to your advantage to treat yourself as the "thief", but it wouldn't work because:
- In **Settings > Screen Time > Content & Privacy > Preference Restrictions** disable **Allow Account Changes**. This blocks you from removing the activation lock from your devices.
- Put your main Apple Account password in the Lockbox only. This blocks you from using the password to get past Activation Lock unless your Lockbox is open. 
- Remove your ability to reset your Apple Account password when the Lockbox is closed. This is impossible because, unless forget your device password or wipe the device, you can always use a device Activation Locked to an Apple Account to reset the password of that Apple Account. 

Even if this were possible, removing your own access to your main Apple Account password would be dangerous. It would make you permanently lose access to your devices and data if your Lockbox were deleted or you were for some reason permanently unable to open it.

   
### 3. Use a full MDM solution to always automatically restore digital controls immediately after factory reset
This is possible.

This is how employers make it impossible for their employees to remove company control over company devices. During setup, the serial number is always automatically sent to Apple, which forces the device to reenroll in the company's MDM. If you set up your own MDM which includes your digital controls, than using factory reset to wipe digital controls becomes impossible.

Full MDM solutions are explicitly only allowed for registered companies. One reason why is because personal access to an MDM would allow anyone to install an MDM on anyone else's device that they knew the password to and had physical access to, and then have permanent full control over it, able to read and write anything. This would be a significant security risk. This is also why you should never put your personal information on a company device.

You could attempt to bypass Apple's rules banning individuals from owning an MDM account, to put one on your own devices and remove the factory reset loophole. [This](https://www.techlockdown.com/articles/managed-mode-iphone) guide claims to explain how. 

I don't use an MDM because:
1. It may be illegal 
2. It may cost money
3. It's highly technical

## Is the factory reset loophole worth closing?

Having the ability to wipe digital controls without waiting for the Lockbox to open is a reliable failsafe in case of an issue with the Lockbox. 

At the same time, this isn't a convenient loophole for impulsive digital control bypassing because it's time-consuming to manually set devices back up (restoring from a backup would restore the digital controls). It's even more time consuming to restore the digital controls afterwards if your backup that contains them is replaced by a newer one that doesn't. 

Thus, I think it's wisest to keep the option for factory reset to wipe the digital controls. 