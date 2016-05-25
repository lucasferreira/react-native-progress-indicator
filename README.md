# react-native-progress-indicator
React Native cross-plataform module to create Progress Indicators in your apps.

This module universalized the use of RN modules ActivityIndicatorIOS, ProgressViewIOS and ProgressBarAndroid into a single reusefull View for using both in Android and iOS platforms.

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

## License
MIT
