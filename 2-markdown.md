# id: 2
# lang: php
# tags: if, empty

This code above produces a PHP Notice: `Undefined variable: var`

#bad
```php
if ($var) {
    // do something with $var
}
```

Use instead:

#good
```php
if (!empty($var)) {
    // do something with $var
}
```
