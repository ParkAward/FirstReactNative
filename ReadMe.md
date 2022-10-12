# Expo 활용 경험

1. Web을 테스트 환경을 구성하기 위해선

```bash
yarn add
@expo/webpack-config@^0.17.0
react-native-web@~0.18.7
react-dom@18.0.0
```

이 필요함

2. Window OS에서 Android 테스트 환경을 구서하기 위해선

   1. Android Studio 다운로드
   2. Setting에 Adb 주소를 환경변수 ANDROID_HOME 설정(필요 없을 수도?)
   3. 안드로이드 에뮬레이터를 구동시킨다.
