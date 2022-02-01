# btpanel-v7.7.0
btpanel-v7.7.0-backup  官方原版v7.7.0版本面板备份

**Centos/Ubuntu/Debian安装命令 独立运行环境 (py3.7)**

```css
curl -sSO https://raw.githubusercontent.com/prajna0/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```
**7.7.0版本去除登录框的命令**

```javascript
sed -i "s|if (bind_user == 'True') {|if (bind_user == 'REMOVED') {|g" /www/server/panel/BTPanel/static/js/index.js
```
```css
rm -rf /www/server/panel/data/bind.pl
```
