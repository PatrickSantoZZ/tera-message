TERA-Message
======

# 功能简介

为Proxy输出 彩色文本 提供便利

------

# 调用方式举例

const Message = require('../tera-message')

const MSG = new Message(mod)

var txt = "Hello"

# MSG.chat(txt)

- MSG.chat( MSG.BLU(txt) )    // /8 Proxy频道 蓝色文字

- MSG.chat( MSG.YEL(txt) )    // /8 Proxy频道 黄色文字

- MSG.chat( MSG.TIP(txt) )    // /8 Proxy频道 青色文字

- MSG.chat( MSG.RED(txt) )    // /8 Proxy频道 红色文字

- MSG.chat( MSG.GRY(txt) )    // /8 Proxy频道 灰色文字

- MSG.chat( MSG.PIK(txt) )    // /8 Proxy频道 粉色文字

- MSG.chat( MSG.clr(txt, 123456) )    // /8 Proxy频道 #123456号颜色 文字

# MSG.party(txt)              // (仅自己客户端可见) 队长通知

# MSG.raids(txt)              // (仅自己客户端可见) 团长通知

# MSG.alert(txt, type)        // (仅自己客户端可见) 屏中警告

type: 数字参数代表不同的样式

- 绿色 31 32 37 41 42 50 52 54 55 56 57 58 59 60 61 62 80 100	冒号68	旗子75

- 蓝色 43	冒号66 68 70 72	旗子76	瓶子101

- 红色 44 53 67 69 71 73	旗子77	瓶子102

- LEVEL UP 35
