# hellovf

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



-----

nodejs의 경우 firebase에서 10.x까지만 지원하여 해당 버전으로 설치해야한다.

nodejs, yarn, vue-cli, firebase-tools 순으로 설치했음.

package.json에 firebase:* 명령어들을 추가중.

firebase의 deploy 대상 파일은 public -> dist로 변경.

deploy는 yarn build 후 떨어지는 dist의 내용을 deploy한다.

API 구성을 위한 express 적용중.
