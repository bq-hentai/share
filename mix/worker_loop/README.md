# Worker Test

本栗子主要是测试在 `WebWorker` 中轮询请求的可靠性。

主进程中进行大运算（50亿），worker中是否能正常的按时发送请求呢？答案是可以的。

## 注意

发送时间最好使用抓包工具或者从服务端中看。
