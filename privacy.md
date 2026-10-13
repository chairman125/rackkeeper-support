# RackKeeper Privacy Policy

Effective date: October 13, 2026

RackKeeper is an app for managing server room racks, equipment, connections and floor plans on the device. The developer does not collect or receive any of your information.

## Information collected

None. The app has no server run by the developer, no app accounts or sign-in, and no analytics, advertising or tracking, and it does not send your data over the internet.

## Information the app stores on the device

- **Data you enter:** rack and device names, asset numbers, IP addresses, contact names, login names in Server Logins and other records you type in or import.
- **Server passwords (optional):** passwords you enter in a device's Server Logins, and passwords that came in a data file you applied. You don't have to enter any. They are kept apart from the other data and are not included in restore points, so restoring one doesn't bring back a deleted password.
- **Device keys:** a key that signs the data files this device creates and a key that encrypts the stored data.
- **Sender name:** the name you enter when you create a data file, kept on the device for the next file.
- **Remembered team passphrase:** only if you choose to remember it.

Data, including server passwords, is stored encrypted on the device and excluded from iCloud backup. Keys and the team passphrase are kept in the iOS Keychain for this device only. Face ID and Touch ID checks for App Lock (optional) and for showing or copying a server password are handled by iOS; the app does not receive or store face or fingerprint data.

## When information leaves the device

Only when you send it yourself:

- When you send a data file (`.rackkeeper`) with AirDrop, Messages, Mail and so on, or save it to Files. The file is encrypted with the team passphrase you choose and contains the sender name you set and the device ID.
- Server passwords are left out of data files by default. They go into data files only if you turn on Share → Settings → ‘Include Passwords in Data Files’. Anyone who knows the team passphrase can then read the passwords in those files, and passwords in files you have already sent can't be taken back.
- When you export a CSV file. CSV files are not encrypted. Server passwords are never included in CSV files.

You choose the app or person to send to in the iOS share sheet.

## Purchases

Buying and restoring the full version is handled by Apple's App Store. The developer does not receive payment or Apple Account information. The app checks ownership with the Apple-signed transactions stored on the device.

## Retention and deletion

Data stays on the device until you delete it or delete the app. Clearing a server password, or deleting its login or device, deletes the password from the device. Share → Settings → ‘Erase All Data’ in the app deletes all server passwords. Deleting the app deletes its data, including server passwords, and the sender name on the device. iOS may keep the device keys and the remembered team passphrase in the Keychain after the app is deleted. You can erase the remembered team passphrase in the app under Share → Settings → ‘Forget Team Passphrase’.

## Contact

Email <bitsae.mooni@gmail.com>, or open a public issue at <https://github.com/chairman125/rackkeeper-support/issues>

A Korean version of this policy is available at [privacy-ko.html](privacy-ko.html).
