# vue-ui

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 创建项目
```
npm install -g @vue/cli
# OR
yarn global add @vue/cli

vue create storybook-test

cd storybook-test

npx -p @storybook/cli sb init --type vue

npm install @storybook/vue --save-dev

{
  "scripts": {
    "storybook": "start-storybook"
  }
}


npm install -g commitizen

npm install cz-customizable --save-dev

 "config": {
    "commitizen": {
      "path": "./node_modules/cz-customizable"
    },
    "cz-customizable": {
      "config": "my.cz-config.js" // 这里的文件名可以自定义，但是改文件需要放置在项目的根目录下
    }
  }

```
