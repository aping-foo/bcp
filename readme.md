BCP是基于TCP实现的用户层传输协议。特性如下：
   1. 基于连接
   2. 可靠，低延时
   3. 以数据包为单位，没有流
 
  <h3>BCP vs. TCP</h3>
 
  BCP和普通TCP功能相似，重新实现了TCP的包确认重发机制。
 
      当网络条件不好，丢包频繁，TCP重传间隔时间会变得很长，从而基本不可用。
 
  BCP和TCP都属于面向连接会话的协议。
     
      但另一方面，BCP数据不是TCP那样的流，而以[[Packet]]为单位。
      
 解决闪断丢包
      