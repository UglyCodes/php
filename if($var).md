```php
<?php

if ($var) {
    // do something with $var
}
```

Use instead:

```php
<?php

if (!empty($var)) {
    // do something with $var
}
```
