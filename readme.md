# dcat-admin-demo-laravel9

# Dcat Admin Demo for Laravel9

本项目是[Dcat Admin](https://github.com/jqhph/dcat-admin)的DEMO源码，在线预览[点击这里](http://103.39.211.179:8080/admin)。

感谢原作者的付出
适配了 laravel9 持续更新,其他没有变动

仓库地址

- Github [https://github.com/yexue666/dcat-admin-demo-laravel9](https://github.com/yexue666/dcat-admin-demo-laravel9)

## 安装

创建项目
```sh
git clone https://github.com/yexue666/dcat-admin-demo-laravel9 dcat-admin-demo
```

运行
```shell
composer install
```

安装完之后，复制一份`.env.example`文件并命名为`.env`，然后运行
```shell
php artisan key:generate
```

然后配置好数据库连接信息运行以下命令

> 这里会提示文件夹已存在，忽略即可。

```php
php artisan admin:install
```

最后运行`php artisan serve`。然后打开`http://localhost:8000/admin`即可访问，账号`admin`，密码`admin`。



