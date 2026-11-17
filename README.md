# react-native-screens: RTL header inset on Android

Screenshots for my comment on [software-mansion/react-native-screens#3896](https://github.com/software-mansion/react-native-screens/pull/3896) (issue #3438).

Blank Expo SDK 58 app, react-native-screens 4.30.1, React Native 0.88.1, New Architecture, Android 14 phone, forced RTL.

| File | What it shows |
| --- | --- |
| `before-centered-title.png` | 4.30.1: a centered custom title is squeezed into a narrow column |
| `pr3896-headerLeft-custom-title.png` | with #3896: a header with `headerLeft`, a custom title and `headerRight` is blank |
| `fix-centered-title.png` | `toolbar.width - it.right`: centered custom title |
| `fix-headerLeft-custom-title.png` | `toolbar.width - it.right`: `headerLeft` + custom title + `headerRight` |
