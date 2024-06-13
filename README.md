# This is an event emitter for user JavaScript

# 依赖项
没有依赖项。你只需要安装 npm，然后运行npm install即可使用

# 列子

```js

// 引入
import { EventEmitter } from 'yang-eventemitter';


const emitter = new EventEmitter();

// 注册
emitter.on('loginState', () => {
  console.log('Login successful!');
});

// 发射事件
emitter.emit('loginState');

```