# yii2_fecshop
fecshop for ecommerce  , online shop open source

========

> 项目已经开始
> Terry

1、安装Yii2
------------

安装这个扩展的首选方式是通过 [composer](http://getcomposer.org/download/).

我的安装路径是在 /www/web/develop/fecadmin 文件夹下面

执行

```
cd /www/web/develop
composer  require "fxp/composer-asset-plugin:~1.1.1"
composer create-project yiisoft/yii2-app-advanced fecadmin 2.0.7
cd fecadmin
./init

```



2、安装FecShop
------------

执行

```
cd /www/web/develop/fecshop
composer require --prefer-dist fancyecommerce/fecshop

```
或添加

```
"fancyecommerce/fecshop": "~1.0"
composer install
```

执行完上面，就安装完成了。