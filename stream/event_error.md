<!-- YAML
added: v0.9.4
-->

* {Error}

当写入数据出错或使用管道出错时，触发 `'error'` 事件。
监听器回调函数被调用时会传入一个 `Error` 参数。

但触发 `'error'` 事件时，流还未被关闭。

