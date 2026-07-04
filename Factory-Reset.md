# Factory reset is a failsafe

## The factory reset failsafe

While digital controls are on, factory reset using your device's settings app is impossible. However, it is always possible to factory reset an Apple device that you have physical access to. 

Options include
- Factory reset using your iCloud account
- Factory reset using your Mac

Factory reset is not recommended because a reset wiping digital controls from a device precludes restoring from a backup (restoring from a backup would restore the digital controls). Then, restoring digital controls after wiping them with a factory reset and setting up the device without them takes hours, because again, you have to factory reset and can't restore from a backup (see the setup instructions for why). In contrast, adjusting settings to unblock or reblock content, or even remove layers of protection entirely, takes minutes when the Lockbox is open.

However, in a pinch when you do not wait 12 hours for your Lockbox to open, factory reset is faster. You can access anything within about half an hour after starting. 

## Options to close the factory reset failsafe

### 1. Block factory reset when you have physical access to a device
This is impossible.

### 2. Block setting a device up after factory reset
This is impossible.

Apple devices are Activation Locked to the iCloud account that is signed in to them. This is so a thief who steals your device can't wipe it and set it up as theirs, unless you give them your Apple Account password. Trying to treat yourself as the "thief" wouldn't work because you can always use a device Activation Locked to an Apple Account that isn't wiped and that you're logged in to to reset the password of that Apple Account, giving you access to the password you need to then bypass Activation Lock after wiping it.

### 3. Use a full MDM solution to always automatically restore digital controls immediately after factory reset
This is possible.

This is how employers make it impossible for their employees to remove company control over company devices. During setup, the serial number is always automatically sent to Apple, which forces the device to reenroll in the company's MDM. If you set up your own MDM which includes your digital controls, than using factory reset to wipe digital controls becomes impossible.

Full MDM solutions are explicitly only allowed for registered companies. One reason why is because personal access to an MDM would allow anyone to install an MDM on anyone else's device that they knew the password to and had physical access to, and then remotely have permanent full control over it, able to read and write anything. This would be a significant security risk. This is also why you should never put your personal information on a company device.

You could attempt to bypass Apple's rules banning individuals from owning an MDM account, to put one on your own devices and remove the factory reset loophole. [This](https://www.techlockdown.com/articles/managed-mode-iphone) guide claims to explain how. 

I don't use an MDM because:
1. It may be illegal 
2. It may cost money

## Is the factory reset failsafe worth closing?

Having the ability to wipe digital controls without waiting for the Lockbox to open is a reliable failsafe in case of an issue with the Lockbox. 

At the same time, it isn't a convenient loophole for impulsive digital control bypassing because it's time-consuming to manually set devices back up, especially if you mean to restore the controls later, requiring another factory reset and manual setup. 

Thus, I think the factory reset loophole is not worth closing.

## Building loopholes is not recommended

Set up correctly, digital controls are genuinely impossible to quickly bypass while you do not have full control.

While you have full control, it is easy to make additional loopholes to allow near-instant bypass of digital controls later.

- You could store a copy of your Lockbox codes outside the Lockbox.
- You could store local backups of all of your devices, without and then with digital controls, to a hard drive.

Any loophole renders digital controls no more effective than self-control alone. If you intend to rely on self-control alone, it's a waste of time and effort to set up digital controls in the first place. Thus, digital controls only make sense if you do not set up a loophole. 