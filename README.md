# React Native Technical Interview

Wolox's base project for the React Native's team technical interview

Updated by: [Djmaam](https://marcosarrieta.dev).

### Objective

Build an app to display a list of books retrieved from the mocked API.  
You must follow the instructions that have been shared to you to solve the exercise.

### Good luck!

![Splash Screen](./src/Assets/WBooks/Splash.jpg)
![Login Screen](./src/Assets/WBooks/Login.jpg)
![Library Screen](./src/Assets/WBooks/Library.jpg)
![BookDetails Screen](./src/Assets/WBooks/Book-Details.jpg)
![Wishlist Screen](./src/Assets/WBooks/Wishlist.jpg)
![Settings Screen](./src/Assets/WBooks/Settings.jpg)

### Setting up Environtment

To run the Local_API:

```shell
    npm install -g json-server
    json-server --watch db.json
```

Create or copy the file ./src/Configs/env.example.json to ./src/Configs/env.json.

Next, to start the app in Android run:

```shell
    cd android && ./gradlew clean && cd ..
    yarn android
    adb reverse tcp:3000 tcp:3000
```

To run in iOS:

```shell
    yarn ios
```

A list of the avaliable npm commands:

- Start development server: `yarn start`
- Run the Android app: `yarn android`
- Run the iOS app: `yarn ios`

The app environment configuration can be found in `./src/Configs/env.example.js`

## <a name="topic-about"></a> About

This project is maintained and it was written by [Wolox](http://www.wolox.com.ar).

![Wolox](https://raw.githubusercontent.com/Wolox/press-kit/master/logos/logo_banner.png)

## <a name="topic-license"></a> License

This project is available under the MIT [license](https://raw.githubusercontent.com/Wolox/wolmo-core-android/master/LICENSE.md).

    Copyright (c) Wolox S.A

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
