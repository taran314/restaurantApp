# Restaurant search app
To run the app:
- Clone the repo
- run `npm i` to install dependencies
- run `npm run ios` for native ios app, if you have Expo
- otherwise, run `npm run web` for web version.

## Notes

- Created app files using `npx expo-cli init food --npm`
- React navigator (version 4.x)
  - first arg is an object containing routes
  - second arg is configurations for navigator

- expo/vector-icons library https://github.com/expo/vector-icons
- styling a search bar
- axios vs fetch
  - baseURL

- useEffect hook
  - useEffect( function, []) --> empty array means to run function once
  - can put a value in the array, runs whenever value is changed

- ScrollView: vertical scrolling if goes beyond the screen
- flex:1 to most parent view --> fill up the screen.

- Empty elements <> and </>, implicit flex: 1

- withNavigations - weird how it works
- Passing information in navigate (second arg)
- navigation.getParam('id');