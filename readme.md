## React Native Library
---

### Default library contains:
- react-native-screens 
- react-native-safe-area-context
- @react-navigation/native-stack
- react-native-vector-icons
- axios
- @types/react-native-vector-icons

Default Yarn Installation
```
yarn add react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons
```

Default NPM Installation
```
npm install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons
```

Default Expo Installation
```
expo install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons
```

---

### Redux library contains:
- react-native-screens 
- react-native-safe-area-context
- @react-navigation/native-stack
- react-native-vector-icons
- axios
- redux
- react-redux
- redux-persist
- @react-native-community/async-storage
- @types/react-native-vector-icons
- @types/react-redux

Redux Yarn Installation
```
yarn add react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux
```

Redux NPM Installation
```
npm install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux
```

Redux Expo Installation
```
expo install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux
```

---

### Redux+Animations library contains:
- react-native-screens 
- react-native-safe-area-context
- @react-navigation/native-stack
- react-native-vector-icons
- axios
- redux
- react-redux
- redux-persist
- @react-native-community/async-storage
- @types/react-native-vector-icons
- @types/react-redux
- react-native-gesture-handler
- react-native-reanimated

Redux Yarn Installation
```
yarn add react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux react-native-gesture-handler react-native-reanimated
```

Redux NPM Installation
```
npm install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux react-native-gesture-handler react-native-reanimated
```

Redux Expo Installation
```
expo install react-native-screens react-native-safe-area-context @react-navigation native-stack react-native-vector-icons axios @types/react-native-vector-icons redux react-redux @react-native-community/async-storage @types/react-redux react-native-gesture-handler react-native-reanimated
```

Add Reanimated's Babel plugin to your babel.config.js:
```
  module.exports = {
    presets: [
      ...
    ],
    plugins: [
      ...
      'react-native-reanimated/plugin',
    ],
  };
```

for expo :
```
module.exports = function(api) {
  api.cache(true);
  return {
    presets: ['babel-preset-expo'],
    plugins: ['react-native-reanimated/plugin'],
  };
};
```

