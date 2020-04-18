# react-native-loader
A collection of animated spinners for react native using ReactART.

# Usage
## Installation
Install it via npm:

```
npm i -S react-native-loader
```

### Android
For Android, it works out of the box.

### iOS
For iOS, add `ART.xcodeproj` from `node_modules/react-native/Libraries/ART` to your Libraries then link `libART.a`.

## How to use
```jsx
import { Bubbles} from 'react-native-bubbles-loader';

// ...
<View>
  <Bubbles size={10} color="#FFF" />
</View>

```
