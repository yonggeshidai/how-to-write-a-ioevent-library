# 什么是IO事件驱动库
如果读者有做过服务端开发的话，应该都听说过 `Libevent` 和 `Libuv` 等IO事件驱动函数库，著名的缓存服务器 `memcached` 就是使用了 `Libevent` 作为IO事件驱动的，而 `Libuv` 则是由 `node.js` 的作者编写的一个IO事件驱动函数库，作为 `node.js` 异步的核心模块。
