---
description: By using React Native Web View
---

# How to display a Website inside React Native App ?

### React Native Web View

Install

```
npm i react-native-webview
```

Example:

```javascript
import { WebView } from "react-native-webview";

export default function App() {
  return(
  <WebView source={{ uri: "https://space.com" }} />
 )
}
```

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
