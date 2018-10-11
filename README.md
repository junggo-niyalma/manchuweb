# manchuweb 满族空间
满族学习网站 ，采用满文竖版的方式，阅读方式为从上到下，从左到右
推荐用最新的chrome浏览器浏览，目前暂时主要支持PC版，移动版未做适配

基于laravel5.4

### 目前提供的功能
字典
划词，基于字典
短句
图书目录

# 网站地址
www.manchu.work 满族空间

#使用步骤
```bash
composer install
 
cp .env.example .env 


```

配置好数据库,更换用户名密码 .env
```bash
DB_CONNECTION=mysql #可能需要替换
DB_HOST=127.0.0.1 #待替换
DB_PORT=3306 #可能需要替换
DB_DATABASE=homestead #待替换
DB_USERNAME=homestead #待替换
DB_PASSWORD=secret #待替换
```

生成key
```bash
php artisan key:generate
```


生成数据库表
```bash
php artisan migrate
```
测试
```
php artisan serve
```

点击测试网址： 
127.0.0.1:8000

##其他：

