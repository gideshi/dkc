# php-fpm

## 配置文件

1. php.ini

你也可以下载匹配所使 PHP 版本的 `php.ini`，然后更新它来使用，例如：
```
curl -sS https://raw.githubusercontent.com/php/php-src/php-7.1.19/php.ini-production -o php.ini
```

当前项目中 `php.ini` 修改的配置项有:

```
date.timezone = PRC

expose_php = Off
```
