ddv-url
===================

Installation - 安装
------------

```bash
composer require ddvphp/ddv-url
```

Usage - 使用
-----

### 1、`urlEncode`

```php

\DdvPhp\DdvUrl::urlEncode();

```

### 1、`urlEncodeExceptSlash`

> 在uri编码中不能对'/'编码

```php

\DdvPhp\DdvUrl::urlEncodeExceptSlash();

```

### 2、`urlDecode`

```php

\DdvPhp\DdvUrl::urlDecode();

```
