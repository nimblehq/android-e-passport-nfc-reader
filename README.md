# E-Passport-NFC-Reader-Android

This repository modified this [EPassportNFCReader](https://github.com/alimertozdemir/EPassportNFCReader) for using the data from input instead of scanning the MrzData.

## Step to run and test

1. Please considering set this information at the `setData()` method in `MainActivity` for decoding the encrypted NFC data:
   - passportNumber
   - expirationDate
   - birthDate
2. Build & run on your device.
3. Now you can start to scan your passport from NFC without doing Mrz scanning.
