# React_Native Environment
Implement apps with the React Native
Windows - React Native Development
1. Node
2. Python
3. Android Studio
4. Java JDK

Java Script --> AOS, IOS(MacOS -> Xcode build tool)

### How To Install Node

- Node -> Java Script Runtime
  NVM (동일 PC에 다양한 Node 버전을 사용하기 위함)
- nvm-windows : https://github.com/coreybutler/nvm-windows/releases
-> nvm-setup.zip 다운로드 / 설치
    ```sh
    nvm install 10.16.2
    nvm use 10.16.2
    nvm list (설치되어 있는 Node 버전 확인)
    node -v
    npm -v
    ```

### How To Install Open JDK (Android 앱을 빌드하기 위해 필요한 JDK)
- https://www.azul.com/downloads/zulu-community/?version=java-8-lts&os=windows&architecture=x86-64-bit&package=jdk
Java 8, Windows, 64-bit, JDK 선택, msi 다운로드

### How To Install Python (React Native Build System은 Python에 의존)
- https://www.python.org/downloads/

### How To Install React Native CLI
- 설치를 위해 Node 패키지의 npm을 사용
    ```sh
    npm install -g react-native-cli (g는 전역으로 설치한다는 의미)
    react-native --version
    아래와 같이 출력
    react-native-cli: 2.0.1
    react-native: n/a - not inside a React Native project directory
    ```
    
### How To Install Android Studio
- https://developer.android.com/studio/index.html
-> SDK 설치 -> adb --version

### IDE 설치 (Java Script 개발 IDE / Visual Code)
- https://code.visualstudio.com/
