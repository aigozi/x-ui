
# 功能介绍

- 系统状态监控
- 支持单端口多用户、多协议，网页可视化操作
- 支持的协议：vmess、vless、trojan、shadowsocks、shadowsocks 2022、dokodemo-door、socks、http
- 支持配置更多传输配置：http、tcp、ws、grpc、kcp、quic
- 流量统计，限制流量，限制到期时间，一键重置与设备监控
- 可自定义 xray 配置模板
- 支持 https 访问面板（自备域名 + ssl 证书）
- 支持一键SSL证书申请且自动续签
- Telegram bot通知、控制功能
- 更多高级配置项，详见面板 

:bulb:具体**使用、配置细节以及问题排查**请点击这里:point_right:[WIKI](https://github.com/FranzKafkaYu/x-ui/wiki):point_left:  
 Specific **Usages、Configurations and Debug** please refer to [WIKI](https://github.com/FranzKafkaYu/x-ui/wiki)    
# 一键安装
在安装前请确保你的系统支持`bash`环境,且系统网络正常  

&#x26A1;从原版升级也可使用该命令，数据不会丢失&#x26A1;

```
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/x-ui/master/install.sh)
```    
For English Users,please use the following command to install English supported version:  
```
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/x-ui/master/install_en.sh)
```
如需安装指定的版本,可以在上述命令中指定版本号,如指定版本为`0.3.4.4`,安装命令如下：    
```
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/x-ui/master/install.sh) 0.3.4.4   
```




# 快捷方式
安装成功后，通过键入`x-ui`进入控制选项菜单，目前菜单内容：
```
  x-ui 面板管理脚本
  0. 退出脚本
————————————————
  1. 安装 x-ui
  2. 更新 x-ui
  3. 卸载 x-ui
————————————————
  4. 重置用户名密码
  5. 重置面板设置
  6. 设置面板端口
  7. 查看当前面板设置
————————————————
  8. 启动 x-ui
  9. 停止 x-ui
  10. 重启 x-ui
  11. 查看 x-ui 状态
  12. 查看 x-ui 日志
————————————————
  13. 设置 x-ui 开机自启
  14. 取消 x-ui 开机自启
————————————————
  15. 一键安装 bbr (最新内核)
  16. 一键申请SSL证书(acme申请)
 
面板状态: 已运行
是否开机自启: 是
xray 状态: 运行

请输入选择 [0-16]: 
```
