# php_-
run.php里面的代码
php多进程只能在cli模式下运行
父进程创建出来的子进程pid是连续的，创建一定数量的进程，让每个进程处理不同的任务：比如可以读取数据库的一大批数据，通过id来分批给不同的子进程处理。
多进程编程的时候主要是注意并发，不能让不同的进程处理同一个任务。
另外，对于多进程处理数据，网上还有的解决方案是通过redis的队列，没有具体实践过。

function.php
php的一些常用方法：日期相关函数，过滤html标签，字符串处理相关，加密解密相关
