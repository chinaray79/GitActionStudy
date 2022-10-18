# 目标与定位
1、定义一个UbuntuAction，获得设备配置信息，包含 `df -h; ls ; uname -a  ; cat /etc/issue` 命令
2、将获得的配置信息写到一个文本当中去，使用 
``` bash
df -h| tee -a infors.txt; ls| tee -a infors.txt ; uname -a  | tee -a infors.txt; cat /etc/issue| tee -a infors.txt
```
3、将写入的文本呢，保存一下。 
验证保存的过程。
