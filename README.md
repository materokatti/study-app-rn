# study-app-rn

## Library

- [React Navigation Library](https://reactnavigation.org/docs/)
- [MobX](https://mobx.js.org/)
- [react-native-sqlite-storage](https://github.com/andpor/react-native-sqlite-storage)

## Trouble Shooting

- If you suspect a Pod install related error, clear your cache with the code below. (24.02.17)
  ```
  pod cache clean --all
  cd ios
  rm -rf Pods
  rm Podfile.lock
  pod install
  cd ..
  ```
