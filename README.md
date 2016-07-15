### Install [Node.js](https://nodejs.org/)

### Install Cordova and Ionic using npm
```
npm i cordova ionic
```

### Clone this repository
```
git clone https://github.com/seanstone/ble.git
```

### Fetch required pacakges and set up platform
```
cd ble
ionic state reset
cordova platform android
cordova plugin add cordova-plugin-ble-central
```

### Build and run
```
cordova run android
```

### For debugging, use Chrome
[chrome://inspect](chrome://inspect)
