# Country-to-Locale
Determine locale from 2-letter country code. (Can be used as language code.)

## Usage

```php
require __DIR__.'/locale.class.php';

echo locale::country2locale('DE'); # 'de_DE'

echo locale::country2locale('CN'); # 'zh_CN'
```
