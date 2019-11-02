## 配置

* CPU: 英特尔（Intel）i7 8700
* 主板: 技嘉（GIGABYTE）B360 M AORUS PRO “小雕”

## Notice

* 声卡驱动使用VoodooHDA，需删除kexts下的AppleHDA驱动。
* 可以使用系统自带更新，但首次重启前，kexts中的驱动需要如下处理:  
kexts中保存了两个文件夹:  
Other: 当前生效的驱动  
Other_update_use: 备份的原始的驱动，用于升级时候用  
**更新时要把Other备份，并把Other_update_use更名为Other。**
