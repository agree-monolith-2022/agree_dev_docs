### 简易服务注册和发现


#### 配置说明
+ ##### discovery.fail-over=true
  故障自动恢复，默认开启。  
  开启后如果服务发生中断，则在下一个心跳探测中重新注入服务；否则服务永久被剔除，直至服务重启。