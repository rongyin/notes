
### Comparable与Comparator的区别
* Comparable接口由待排序类在待排序类中定义，因为Comparable接口中唯一一个方法compareTo(T o) 隐含着比较的一个对象是自身。
* Comparator接口可作为定制排序在待排序类外定义，与待排序类无耦合。其中compare(T o1, T o2) 的输入值为待比较的两个对象。
***

### HTTP报文格式
#### 请求
##### 请求行
* 请求方法
* URL
* 协议版本
##### 请求头部
* Host
* User-Agent
* Connection
* Accept-Charset
* Accept-Encoding
* Accept-Language
##### 请求正文
可选部分
#### 响应
##### 状态行
* 协议版本
* 状态码
* 状态码描述
##### 响应头部
* Server
* Content-Type
* Content-Length
* Content-Charset
* Content-Encoding
* Content-Language
##### 响应正文
***
