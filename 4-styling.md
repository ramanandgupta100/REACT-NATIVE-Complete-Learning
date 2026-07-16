# STYLING

### 1. on the same line (Inline styles)

```javascript
style = {{ fontSize:40, marginTop:20 }}
```



***

### 4. Using Object (Stylesheet)

```javascript
import { Text, StyleSheet } from "react-native";

export default function App() {
  return (
      <>
      <Text style={styles.title}>Hello World</Text>
      </>
  );
}

const styles = StyleSheet.create({
  title: {
    fontSize: 24,
    fontWeight: "bold",
    color: "#333",
  },
  // remaining styles
});
```
