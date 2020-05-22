# High-available-technology
负载均衡与反向代理
为什么要使用Nginx？
  假设某台服务器重启或者出现故障，DNS会有一定的缓存时间，故障后切换时间长，且没有对后端服务进行心跳检查和失败重试机制
  可以考虑选用HaProxy和Nginx

