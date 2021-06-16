事件循环机制
执行顺序
nextTick队列
其他微任务队列(nextTick执行完后-> promise)
times队列： setTimeout/setInterval
io队列
setImmediate(在times队列： setTimeout/setInterval队列)
close
注意点
Js是单线程,而这个线程中拥有唯一的一个事件循环
一个线程中，事件循环是唯一的，但是任务队列可以拥有多个
任务队列分为宏任务(macro-task)和微任务队列(micro-task)
基本的