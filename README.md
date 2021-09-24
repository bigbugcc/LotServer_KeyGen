# LotServer_KeyGen
- 支持php8.0(修改了语法)   
  
- 许可证有效期到2099年(可自行修改)  

Usage:  
- cli:
````
cd LotServer_KeyGen  

# 自行替换 00:00:00:00:00:00 网卡mac地址
php keygen.php 00:00:00:00:00:00 1 

# 替换LotServer证书文件
cp out.lic /appex/etc/apx.lic 

# 查看激活信息
/appex/bin/lotServer.sh status
````
  - web:
  ```
  http://example.com/keygen.php?ver=1&mac=00:00:00:00:00:00
  ```
