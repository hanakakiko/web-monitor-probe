# web-monitor-probe
probe of web-monitor

web-monitor里创建新探针时会用ssh将本代码拉取到探针服务器上并启动。
本代码主要功能：
1. 定时拉取新任务
2. 定时运行任务
3. 将任务执行结果存回数据库
4. 定时发送心跳并告知槽位剩余情况
