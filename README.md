打开谷歌浏览器(chrome)
F12打开控制台，依次输入以下代码：

``` javaScript
// 打开一个WebSocket:
var ws = new WebSocket('ws://localhost:3000/test');
// 响应onmessage事件:
ws.onmessage = function(msg) { console.log(msg); };
// 给服务器发送一个字符串:
ws.send('Hello!');
```

[教程地址](https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000/0014727922914053479c966220f47da91991fa9c27ac3ea000)