# RackKeeper Privacy Policy

Effective date: November 16, 2026

RackKeeper is an app for managing server room racks, equipment, connections and floor plans on the device. This policy covers the Android app (Google Play) and the upcoming iPhone and iPad app (App Store). The developer does not collect or receive any of your information.

## Information collected

None. The app has no server run by the developer, no app accounts or sign-in, and no analytics, advertising or tracking, and it does not send your data over the internet. The Android app does not even have permission to access the internet.

## Information the app stores on the device

- **Data you enter:** rack and device names, asset numbers, IP addresses, contact names, login names in Server Logins and other records you type in or import.
- **Server passwords (optional):** passwords you enter in a device's Server Logins, and passwords that came in a data file you applied. You don't have to enter any. They are kept apart from the other data and are not included in restore points, so restoring one doesn't bring back a deleted password.
- **Device keys:** a key that signs the data files this device creates and a key that encrypts the stored data.
- **Sender name:** the name you enter when you create a data file, kept on the device for the next file.
- **Remembered team passphrase:** only if you choose to remember it.

Data, including server passwords, is stored encrypted on the device.

- iPhone and iPad: data is excluded from iCloud backup. Keys and the team passphrase are kept in the iOS Keychain for this device only. Face ID and Touch ID checks for App Lock (optional) and for showing or copying a server password are handled by iOS.
- Android: data is excluded from Android backups and device-to-device transfers. The device keys and the remembered team passphrase are encrypted with a key that exists only in this device's Android Keystore, and kept in the app's storage. Fingerprint, face and screen lock checks for App Lock (optional) and for showing or copying a server password are handled by Android.

On both, the app does not receive or store face or fingerprint data.

## When information leaves the device

Only when you send it yourself:

- When you send a data file (`.rackkeeper`) or save it as a file (iPhone and iPad: AirDrop, Messages, Mail and so on, or save to Files; Android: Quick Share, a messaging app, email and so on, or save as a file). The file is encrypted with the team passphrase you choose and contains the sender name you set and the device ID.
- Server passwords are left out of data files by default. They go into data files only if you turn on Share → Settings → ‘Include Passwords in Data Files’. Anyone who knows the team passphrase can then read the passwords in those files, and passwords in files you have already sent can't be taken back.
- When you export a CSV file. CSV files are not encrypted. Server passwords are never included in CSV files.

You choose the app or person to send to in the iOS or Android share sheet.

## Purchases

- iPhone and iPad: buying and restoring the full version is handled by Apple's App Store. The developer does not receive payment or Apple Account information. The app checks ownership with the Apple-signed transactions stored on the device.
- Android: the Android app currently has no in-app purchases.

## Retention and deletion

Data stays on the device until you delete it or delete the app. Clearing a server password, or deleting its login or device, deletes the password from the device. Share → Settings → ‘Erase All Data’ in the app deletes all server passwords. You can erase the remembered team passphrase in the app under Share → Settings → ‘Forget Team Passphrase’.

- iPhone and iPad: deleting the app deletes its data, including server passwords, and the sender name on the device. iOS may keep the device keys and the remembered team passphrase in the Keychain after the app is deleted.
- Android: deleting the app deletes its data, including server passwords, the device keys, the remembered team passphrase and the sender name.

## Contact

Email <bitsae.mooni@gmail.com>, or open a public issue at <https://github.com/chairman125/rackkeeper-support/issues>

A Korean version of this policy is available at [privacy-ko.html](privacy-ko.html).
