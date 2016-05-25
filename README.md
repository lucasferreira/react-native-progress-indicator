# react-native-progress-indicator
React Native cross-plataform module to create Progress Indicators in your apps.

This module universalized the use of natives modules ActivityIndicatorIOS, ProgressViewIOS and ProgressBarAndroid into a single re-useful View for using both in Android and iOS platforms, that let you able to write a single code base progress indicators.

### Installation

```bash
npm install react-native-progress-indicator --save
```

## Example

```javascript
import ProgressIndicator from 'react-native-progress-indicator';

// inside your Components
<ProgressIndicator size="large" />

// or in progressbar mode
<ProgressIndicator progress={0.7} />
```

All of others props from native modules are available to use in ProgressIndicator module. Please in the RN docs: 
https://facebook.github.io/react-native/docs/activityindicatorios.html

https://facebook.github.io/react-native/docs/progressviewios.html

https://facebook.github.io/react-native/docs/progressbarandroid.html

## License
MIT
