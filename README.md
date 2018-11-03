# aligner-php

[Aligner](https://github.com/adrianlee44/atom-aligner) add-on to support PHP.

## Supported operators
`=>`:
```php
array(
    key  => value,
    key2 => value2,
    key3 => value3,
)
```

`=`, `+=`, `-=`, etc:
```php
$a    = 2;
$bcd  = 3;
$bcd += 4;
```

`==` and `===`:
```php
echo (
    $a    == 1 ? 'one' :
    $a    == 2 ? 'two' :
    $abc  == 3 ? 'three' :
    $a   === 3 ? 'three' :
    $a    == 4 ? 'four' : 'other');
```

`,`:
```php
define( 'key',  'value' );
define( 'key2', 'value2' );
define( 'key3', 'value3' );
```

## Installation
Aligner must be installed along with this package. For more information, please check out [Aligner](https://github.com/adrianlee44/atom-aligner)

## Changelog
- 2018-11-03   v1.3.0   Add support for `,` and additional assignment operators
- 2017-09-10   v1.2.0   Add support for Blade
- 2017-05-13   v1.1.1   Fix config titles.
- 2017-05-13   v1.1.0   Add support for == and ===. Update documentation.
- 2015-05-13   v1.0.0   Initial release
