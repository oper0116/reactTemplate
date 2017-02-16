React Template 업데이트 내역
================

## 사용법

```
git clone https://github.com/oper0116/reactTemplate.git
```

## 설치 **
```
npm install
```

** 개발모드 시작 **
```
npm start
```

Open http://localhost:8080 in your browser.

Static files are served from the `public` folder, project JavaScript files are bundled from the `app` folder.

** 빌드 - Production **
```
npm run build
```

This will generate a minimized bundle.js file on the `public` folder.


### Missing Features

This boilerplate focuses solely on transforming and bundling javascript files - all other static files are served directly from the public folder without any processing. While useful for learning React, this setup doesn't use Webpack and Babel in their full capabilities - which include transforming and bundling projects assets (such as stylesheets), modularizing CSS, hot reloading and etc. Please refer to [Pro React Appendix A](http://www.pro-react.com/materials/) to learn more about Webpack. If you are looking for a feature-rich bootstrap for React, take a look at [React App Advanced Boilerplate](//github.com/pro-react/react-app-advanced-boilerplate).


### Dependencies

* React & React-DOM
* Webpack & webpack-dev-server
* Babel Core
* Babel Loader (With "es2015" and "react" presets)
