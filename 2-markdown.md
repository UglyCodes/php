# id: 2
# lang: php
# tags: if, empty
This code above produces a PHP Notice: `Undefined variable: var`

```php bad
if ($var) {
    // do something with $var
}
```

Use instead:

```php good
if (!empty($var)) {
    // do something with $var
}
```
