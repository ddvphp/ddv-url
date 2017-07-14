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

### 2、`urlEncodeExceptSlash`

> 在uri编码中不能对'/'编码

```php

\DdvPhp\DdvUrl::urlEncodeExceptSlash();

```

### 3、`urlDecode`

```php

\DdvPhp\DdvUrl::urlDecode();

```

### 4、`parse` url解码[parse_url]

```php

\DdvPhp\DdvUrl::parse();

```

### 5、`build` url编码[http_build_url]

```php

\DdvPhp\DdvUrl::build();

```

### 6、`parseQuery` query解码[parse_str]

```php

\DdvPhp\DdvUrl::parseQuery();

```

### 7、`buildQuery` query编码[http_build_query]

```php

\DdvPhp\DdvUrl::buildQuery();

```

### 8、`formatPath` path格式化，去除多余/

```php

\DdvPhp\DdvUrl::formatPath();

```
