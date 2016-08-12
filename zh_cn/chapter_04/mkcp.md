# mKCP 协议

mKCP 是流式传输协议，由 [KCP 协议](https://github.com/skywind3000/kcp)修改而来，可以按顺序传输任意的数据流。

## 版本
mKCP 没有版本号，不保证版本之间兼容性。

## 依赖
### 底层协议
mKCP 是一个基于 UDP 的协议，所有通讯使用 UDP 传输。

### 函数
* fnv: [FNV-1a](https://en.wikipedia.org/wiki/Fowler%E2%80%93Noll%E2%80%93Vo_hash_function) 哈希函数
  * 输入参数为任意长度的字符串；
  * 输入出一个 32 位无符号整数；

## 通讯过程