Libtextcat-Package
==================

TYPO3 Flow Package for PHP libtextcat support (language categorization)

```php
$textcat = new \Libtextcat\Textcat();
$language = $textcat->classify($string);
if ($language !== FALSE) {
	echo "Detected language $language;
}
```
