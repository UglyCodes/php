```php
<?php

if ($var) {
    // do something with $var
}
```

This code above produces a `PHP Notice: Undefined variable: var`

Use instead:

```php
<?php

if (!empty($var)) {
    // do something with $var
}
```
