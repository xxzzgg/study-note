## 事件循环机制
### 执行顺序
1. nextTick队列
2. 其他微任务队列(nextTick执行完后-> promise)
3. times队列： setTimeout/setInterval
4. io队列
5. setImmediate(在times队列： setTimeout/setInterval队列)
6. close
### 注意点
1. Js是单线程,而这个线程中拥有唯一的一个事件循环
2. 一个线程中，事件循环是唯一的，但是任务队列可以拥有多个
3. 任务队列分为宏任务(macro-task)和微任务队列(micro-task)
4. 基本的

