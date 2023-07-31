variables start with a $ in php

```php
    $txt="Hello";

    $x=5;
    $y=7;
    echo $x + $y;
```

string  values

```php
    echo strlen("Hello World!"); //returns length of the string
    echo strrev("Hello World!"); //returns the string reversed
```

logic in strings

```php
    $oldtxt = "Hello World!";
    $newtxt = str_replace("World","Dolly",$oldtxt);
```