# xcrud

xcrud 是一个基于 element-ui & Vue 实现快速增删改查的组件，通过 json 配置表单，摆脱繁琐的变量和 html

## Install

```bash
npm install xcrud -S
# or
yarn add xcrud -S
```

## Getting started

```js
import Vue from "vue";
import App from "./App.vue";
import router from "./router";

import Element from "element-ui";
import "element-ui/lib/theme-chalk/index.css";
import Xcrud from "xcrud";

Vue.use(Element);
Vue.use(Xcrud, {
  // your global theme config
});

new Vue({
    router,
    render: h => h(App)
}).$mount("#app");
```

## Development

```bash
# develop
yarn dev
```

## Build

```bash
# build for production npm package
yarn build
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, charles
