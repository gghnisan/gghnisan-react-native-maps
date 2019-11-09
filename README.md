# react-native-maps [![npm version](https://img.shields.io/npm/v/react-native-maps.svg?style=flat)](https://www.npmjs.com/package/@gghnisan/react-native-maps)

React Native Map components for iOS + Android
### Headers added (only Android)
```
The following files have been modified:

1. com.airbnb.android.react.maps.AirMapUrlTile
2. com.airbnb.android.react.maps.AirMapUrlTileManager
2. lib.components.MapUrlTile.js
2. index.d.ts
```
### How to use
For example, 

```jsx
<MapUrlTile 
  urlTemplate={'http://yourServerWithMaps.org/{z}/{x}/{y}.png'}
  headers={
    {
      Authorization: 'Basic xxxxxtokenxxxxx'
    }
  } 
/>
```

## Installation

## The current version of react-native-maps is compatible only with 0.60.+ react-native versions

```
npm install @gghnisan/react-native-maps

npm link @gghnisan/react-native-maps
```

## Other information

#### See 
#### https://github.com/react-native-community/react-native-maps


