## What is it
为vue提供的仿原生ios message弹窗钻进

## 安装
```js
npm install songhao-vue-messagebox --save
```
## demo 演示
```js
git clone https://github.com/songhaoreact/vue-better-messagebox.git
cd vue-better-messagebox
npm install
npm run dev
```
## 使用
vue main.js 入口文件
```javascript
import {Alert, Confirm, Toast} from 'songhao-vue-messagebox'
// // 样式文件
import 'songhao-vue-messagebox/style.css'

// 使用该插件

Vue.use(Alert)
Vue.use(Confirm)
Vue.use(Toast)

```

## 使用
```javascript
    this.$alert('title', {
        title: '提示',
        btn: {
            text: '确定'
        }
    })
    .then(()=>{
        this.$toast('你点击了确定');
    })
// 更简单的弹窗
    this.$alert('title', {
        title: '提示',
        btn: {
            text: '确定'
        }
    })

// 其他弹窗和方式和上面一样
```
## 效果图

![image](https://github.com/songhaoreact/vue-better-messagebox/blob/master/demo.gif)






