### Topic
  * 防火墙
  * Proxy
  * VPN
### Firewall
#### firewall 分类
* packet 过滤器,工作在OSI layer3,采用routing机制。针对packet header操作。
* 应用层防火墙，对数据进行操作。
#### firewall结构
* 单机式
* 网关式 /DMZ和Reverse Proxy.
* 通透式（brige)
#### Netfilter
* Filter机制
#### Iptables
* Iptables指令＝命令参数＋规则语法
* #iptables -t filter -A INPUT 2 -p tcp -j ACCEPT
* 操作netfilter 表（数据库）filter/nat/mangle/raw的增A/I删D/F改R/P查L.
* 规则语法
* 以filter机制构建单机防火墙步骤：
  * 提出安全需求，把规则写下来
  * 把规则翻译成iptables语法
  * 先拒绝所有连接，再逐一开放对外提供的服务。
  * 测试防火墙规则的正确性。（外访内，内访外，两个方向）
  
