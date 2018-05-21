# Country-to-Locale

[![Downloads](https://img.shields.io/packagist/dt/peterkahl/country-to-locale.svg)](https://packagist.org/packages/peterkahl/country-to-locale)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![If this project has business value for you then don't hesitate to support me with a small donation.](https://img.shields.io/badge/Donations-via%20Paypal-blue.svg)](https://www.paypal.me/PeterK93)

Determine locale from 2-letter country code. (Can be used as language code.)

## Usage

```php
use peterkahl\locale\locale;

echo locale::country2locale('DE'); # 'de_DE'

echo locale::country2locale('CN'); # 'zh_CN'
```
