# 更新
- deploy.py line506 不更新系统的软件包 (该条应该可以不更改)
- 胡乱添加一些中文注释
- 预先设定问题和答案 (Ubuntu16.04程序测试通过)
- 一定要输入邮箱，否则可能出错(会无法获得证书)
 
- 修复locale语言环境配置问题（部分ubuntu16.04下更新证书会失败）  
sudo /usr/share/locales/install-language-pack en_US.UTF-8  
sudo apt-get install language-pack-zh-hant-base language-pack-zh-hans-base  

