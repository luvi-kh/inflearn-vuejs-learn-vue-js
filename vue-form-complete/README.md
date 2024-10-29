# vue-form

## Project setup
```
vue create vue-form

npm install
```

### ESLint 에러 화면에 표시하지 않도록 설정
```
1. 프로젝트 폴더에 `vue.config.js` 파일 생성

2. `vue.config.js` 파일에 아래 내용 입력

module.exports = {
  devServer: {
    overlay: false
  }
}


3. 파일 저장

4. `Ctrl + C`로 서버 종료 후 `npm run serve`로 다시 실행

5. 결과 확인
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
