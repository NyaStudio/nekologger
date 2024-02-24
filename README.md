## NekoLogger
A Simple Node.JS Logger based on Chalk Module

## 依赖
chalk@4.1.0  
反正不是 ESM 版本的就行  

moment-timezone

## 使用
目前有以下五个类: `info`, `ok`, `warn`, `err`, `ing`  
我定义的寓意是：信息，成功，警告，错误，进行中  
您可以根据您的理解来使用这些颜色  

基本使用：
```
logger.<type>(msg, who);
```

示例：
```
const logger = require('nekologger');

logger.info('这是一条信息', '发出者');
```

输出：
```
[2024-02-22 23:41:06] [发出者] [INFO] 这是一条消息
```

## 后记
这玩意是给我自己用的，今后大概不会维护，当个乐子看就行了
