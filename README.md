# react-native-a-beep
A very lite module to play system sounds and beep for react-native apps (no sound files)

## Install
```javascript
npm install "react-native-a-beep"
react-native link (RN < 0.60)
```
## Usage

```javascript
import RNBeep from 'react-native-a-beep';
```
Examples:
```
<Button onPress={ () => {RNBeep.beep()} } title="Beep Success"></Button>
<Button onPress={ () => {RNBeep.beep(false)} } title="Beep Fail"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(RNBeep.AndroidSoundIDs.TONE_CDMA_ABBR_ALERT)} } title="Beep Android Custom"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(41)} } title="Beep Something"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(RNBeep.iOSSoundIDs.AudioToneBusy)} } title="Beep iOS Custom"></Button>
```

Happy Beep!

FREE!