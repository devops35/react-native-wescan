
# react-native-wescan

## Getting started

`$ npm install react-native-wescan --save`

### Mostly automatic installation

`$ react-native link react-native-wescan`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-wescan` and add `RNWescan.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNWescan.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<


## Usage
```javascript
import RNWescan from 'react-native-wescan';


RNWescan.scanDocument((response) => {
  console.log(response) //It will give the private path of the final image
})
```
