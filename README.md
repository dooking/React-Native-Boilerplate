# React-Native-Boilerplate

### 1. Homebrew 설치

- [Homebrew 설치 페이지](https://brew.sh/)
- Mac에서 필요한 패키지를 설치하고 관리하는 Mac 전용 패키지 관리자

```jsx
brew --version
```

### 2. Nodejs 설치

- [Nodejs 설치 페이지](https://nodejs.org/)
- Javascript의 런타임을 도와주는 프로그램

```jsx
brew install node
node --version
npm --version
```

### 3. Watchman 설치

- [Watchman 설치 페이지](https://facebook.github.io/watchman/)
- 특정 폴더나 파일을 감시하거나 변화가 생기면, 특정 동작을 실행하도록 설정하는 역할 담당
- RN에서는 소스코드의 추가, 변경을 감지하여 다시 빌드해줌

```jsx
brew install watchman
watchman --version
```

### 4. React Native CLI 설치

```jsx
npm install -g react-native-cli
react-native --version
```

### 5. Xcode 설치

- [Xcode 다운로드 링크](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
- RN IOS 앱을 개발하기 위해서는 개발 툴인 Xcode가 필요
- 설치 후, Command Line Tools 설정 필요!

    Xcode > preferences.. > Locations 에서, Comman Line Tools 최신 버젼 선택
    <img width="600" alt="스크린샷 2021-07-01 오전 11 34 34" src="https://user-images.githubusercontent.com/60457112/124056260-51431b00-da60-11eb-9668-0b8a564459fb.png">



### 6. Cocoapods 설치

- [Cocoapods 설치 링크](https://cocoapods.org/)

```jsx
sudo gem install cocoapods
pod --version
```

### 7. React-Native 프로젝트 생성

```jsx
npx react-native init TestApp
cd SampleApp
npm run ios // yarn ios , react-native run-ios
```
<div align="center">
<img width="200" alt="스크린샷 2021-06-30 오후 3 05 04" src="https://user-images.githubusercontent.com/60457112/124056286-57d19280-da60-11eb-9257-6157b6098a7a.png">
</div>
  
> 참고 자료

[https://dev-yakuza.posstree.com/ko/react-native/install-on-mac/](https://dev-yakuza.posstree.com/ko/react-native/install-on-mac/)
