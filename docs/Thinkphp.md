
xsIdea 1.0.0.20241024
===============

### ThinkPHP 8.0 安装
- 安装
~~~
composer create-project topthink/think xs-idea-php
~~~
- 更新
~~~
composer update topthink/framework
~~~
- 运行
~~~
php think run -H www.xsidea.com -p 80
~~~
- 版本
~~~
php think version
~~~
- 模式扩展
~~~
composer require topthink/think-multi-app topthink/think-captcha topthink/think-view topthink/think-image firebase/php-jwt phpmailer/phpmailer
~~~

### ThinkPHP 8.0 快速生成
* 生成控制器
```
php think make:controller platform@Index --api  // 平台
php think make:controller admin@Index --api     // 后台
php think make:controller api@Index --api       // 台
```
* 生成应用
```
php think build admin                           // 生成应用
```
* 生成模型
```
php think make:model common@Admin                // 生成模型
```
* 生成中间件
```
php think make:middleware admin@Auth
```
* 清除缓存并删除空目录
```
php think clear --dir                           // 清除缓存并删除空目录
```



### 常用代码
```
define('DS',DIRECTORY_SEPARATOR);
```


### 文档
[完全开发手册](https://doc.thinkphp.cn)



