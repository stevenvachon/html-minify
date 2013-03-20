# HTML Minify

## FAQ & Changelog

[http://wordpress.org/extend/plugins/wp-html-compression/](http://wordpress.org/extend/plugins/wp-html-compression/)

## Example Usage

### Inline HTML

```php
<?php require_once 'html-minify.php'; ?>
<html>
…
</html>
```

### External HTML

```php
<?php

require_once 'html-minify.php';

echo file_get_contents('markup.html');

?>
```

## License

This plugin is dual licensed under the MIT and GPL licenses.