# xpx-vue-native-tutorail

## ProximaX Sirius Vue-native demo development code

### 1. Get Sirius Desktop Wallet for Testnet
```
  Server side Wallet: https://bctestnetwallet.xpxsirius.io/#/home
  a. Create Wallet, name it “my-wallet”
  b. “Save Paper Wallet” or “Show Private Key” and save it. 
  c. Continue and sign-in to my-wallet, select “Account”, and copy the Address.
  d. Get test xpx from this link: https://bctestnetfaucet.xpxsirius.io/#/
  e. Paste your wallet Address into: “Enter your Testnet Address”, press “Send”. 10K xpx will send to your wallet
  
  Wait for 15-20sec, you should see 10K xpx in your wallet.
  
  Source code for this Wallet:
  https://gitlab.com/df-wallet-developers/df-wallet-v0.1.0/-/tree/test/fix/src 
  
```
### 2. Install VScode 

  [https://code.visualstudio.com/](https://code.visualstudio.com/)

### 3. Add Vue-native in VScode

```

npm install --global vue-native-cli
npm install --global expo-cli

```

### 4. Download and run Demo, xpx-vue-native-tutorial
```
  git clone https://github.com/sophal1983/xpx-vue-native-tutorial.git
  cd xpx-vue-native-tutorial 
```

### 5. Project setup
```
npm install
{install all node_modules and library as in package.json}

Install ProximaX Blockchain SDK for JavaScript (option):
npm install tsjs-xpx-chain-sdk rxjs
{only require if it is not install automatically by "npm install"}

Read More:
```

[https://github.com/proximax-storage/tsjs-xpx-chain-sdk](https://github.com/proximax-storage/tsjs-xpx-chain-sdk)

### 6. Compiles and hot-reloads for development
```
run App at browser:
npm run serve

```
### 7 Run App on Phone
[screenshod txpx-vue-native-tutorail](https://photos.app.goo.gl/isgS3LB7VvNBrxNF7)

```
a. Enable Developer mode on your Phone:

```
How to Access Developer Options and Enable USB Debugging on Android. [https://www.howtogeek.com/129728/how-to-access-the-developer-options-menu-and-enable-usb-debugging-on-android-4.2/](https://www.howtogeek.com/129728/how-to-access-the-developer-options-menu-and-enable-usb-debugging-on-android-4.2/)
```
b. Connect PC to Phone with USB cable, select “File transfer”.  
c. At Terminal, type “adb devices” to make sure Phone is hock to PC: 
 > adb devices
 List of devices attached
 8UE5T18205002780 device
(Your UUID will be different)
d. To run Apk on phone: npm run android
```
### 8. HELP AND REFERENCES

##### ProximaX Developers Chat Group at Telegram:  https://t.me/proximax_devs

###### IMPORTANT LINKS:

###### About ProximaX:

   - [Enterprise website!](https://www.proximax.io/)
   - [Company profile!](https://www.proximax.ltd/)
   - [Corporate brochure](https://suite-app.proximax.io/s/edDrecHDwszEDWm)
   - [Enterprise brochure (short, non-techie)](https://suite-app.proximax.io/s/4CZ7gr7R3qHHmMx)
   - [PowerPoint presentation deck](https://suite-app.proximax.io/s/4CZ7gr7R3qHHmMx)
   - [Fact Sheet for Exchange Listings](https://suite-app.proximax.io/s/Bt8HEJPXqj5KKL5)
   - [Video: Blockchain Reimagined and Evolved ](https://suite-app.proximax.io/s/rEcRSGY8rosAKwk)
   - [Video: Post Blockchain Mainnet Activities](https://youtu.be/2ZqeFpGfqSE)

[Sirius](https://www.youtube.com/watch?v=uOr1J0XJS7M) Dev Portals:
  - [Sirius Chain](https://bcdocs.xpxsirius.io/)
  - [Sirius Storage](https://storagedocs.xpxsirius.io/)
  - Supercontracts (not yet available)
  - Sirius Stream (not yet available)

##### Sirius SDKs:

- [GitHub](https://github.com/proximax-storage)

[Sirius](https://github.com/proximax-storage) Tools:
- [Mainnet web wallet](https://wallet.xpxsirius.io/)
- [Mainnet explorer](http://explorer.xpxsirius.io/)
- [Mainnet iOS mobile wallet](https://apps.apple.com/us/app/proximax-sirius-wallet/id1475020250)
- [Mainnet Android mobile wallet](https://play.google.com/store/apps/details?id=io.proximax.siriuschainwallet)
- [Testnet web wallet](http://bctestnetwallet.xpxsirius.io/)
- [Testnet explorer](http://bctestnetexplorer.xpxsirius.io/)
- [Testnet faucet](https://bctestnetfaucet.xpxsirius.io/) 
 
###### Competitor Analysis:
- [Comparison table](https://suite-app.proximax.io/s/AYFYJ78KnHzwkKi)

##### [About](https://suite-app.proximax.io/s/AYFYJ78KnHzwkKi) eDLX:
- [Paper: Radicalizing the Equity Market](http://bit.ly/2P8xT4z)
- [Brochure](https://suite-app.proximax.io/s/zcS5kH87XQGxtWC)
- [Brochure (Chinese)](https://suite-app.proximax.io/s/NjgBPAfi6HT4nNj)
- [Brochure (Spanish)](https://suite-app.proximax.io/s/6jEHnjyKEA8xNnB)
- [Overview of eDLX for License to Operate](https://suite-app.proximax.io/s/3TqBTftJymXyCgm)
- [Website](https://www.proximax.ltd/solutions/edlx)
- Video: General intro (not yet available)

###### About SiriusID:
- [Brochure](https://suite-app.proximax.io/s/jzKJDBCSKdmgK25)
- [Paper](https://suite-app.proximax.io/s/CWssi8J66RAwx3e)
- [Website](https://www.proximax.ltd/solutions/siriusid)
- Video: General intro (coming soon!)

###### About mWallet:

- [Brochure](https://suite-app.proximax.io/s/G7AZt36iHda56zD)
- [Brochure(Chinese)](https://suite-app.proximax.io/s/7XRrf8dB2mtek2o)
- [Brochure (Spanish)](https://suite-app.proximax.io/s/9XpBdagXwmLX2Zd)
- [Website](https://www.proximax.ltd/solutions/mwallet) 
- Video: General intro (not yet available)

###### About ProximaX Forms:

- Brochure (not yet available)
- Website (not yet available)
- Video: General intro (not yet available)

##### About ProximaX KYC:

- [Website](https://kyc.proximax.io/)
- [Brochure](https://suite-app.proximax.io/s/oiGjyKnfLQGftN3)

[About](https://suite-app.proximax.io/s/oiGjyKnfLQGftN3) ProximaX Suite:
- [Website](https://suite.proximax.io/)

[Open](https://suite.proximax.io/) Source Apps:
- [Notes](https://github.com/proximax-storage/notes)
- [Vault](https://github.com/proximax-storage/vault)
- [File It!](https://github.com/proximax-storage/file-it)

[Voting](https://github.com/proximax-storage/file-it) & Notary:
- [MOCD Whitepaper](https://suite-app.proximax.io/s/tTci9XFqgbAq3sQ)

[Why](https://suite-app.proximax.io/s/tTci9XFqgbAq3sQ) become a ProximaX Technology Partner?
- [Flyer](https://suite-app.proximax.io/s/5F6Sj7NsZEA7MNc)

[List](https://suite-app.proximax.io/s/5F6Sj7NsZEA7MNc) of System Integrators:
- [List](https://suite-app.proximax.io/s/89FsdKjf4Yp73BF)

[Private](https://suite-app.proximax.io/s/89FsdKjf4Yp73BF) Platform & Apps Fees:
- [Fees table](https://suite-app.proximax.io/s/Qa3WQDibFf3pBN6)
- [Internal Fees Spreadsheet](https://t.me/c/1495989157/1672)

[Contractual](https://t.me/c/1495989157/1672) Templates:
- [Technology Partnership Agreement](v.1.3 (https://suite-app.proximax.io/s/GR4oQ2cZEasNmTH))
- [MOU (v.1.1)](https://suite-app.proximax.io/s/XGBQ9j4W4RKPA5f)
- [Mutual NDA (v.1.1)](https://suite-app.proximax.io/s/abnjPtB2pFM99Jp)

  
