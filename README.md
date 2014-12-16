# GB/T 2260

The latest GB/T 2260 codes. Updated at 2013, published at 2014.

## Installation

Install with Packagist:
```
    $ composer install cn/gb2260
```

### .data

Get data of GB/T 2260-2013.

```php
var_dump(GB2260::getData());
```

### .parse(code)

Parse a code, and get the city name of that code.

```php
GB2260::parse(420822);
// => '湖北省 荆门市 沙洋县'
```

## License

WTFPL

