# Simple Calculator
Make a package with Laravel - Simple Calculator

## Installation
composer require kulikode/kalkulator
1. Install the package via composer:

```sh
composer require kulikode/kalkulator
```

## Usage

```php
use Kulikode\Kalkulator\BasicCalculator;

```

To calculate simple add and multiply:

```php
$array = [2, 89, 99, 150, 89, 64, 39];
$result = \Kulikode\Kalkulator\BasicCalculator::add($array)
$result = \Kulikode\Kalkulator\BasicCalculator::multiply($array)
```

To calculate advanced add and multiply:

```php
$number = rand(10, 100);
$binary = \Kulikode\Kalkulator\AdvanceCalculator::decimalToBinary($number)
$hex    = \Kulikode\Kalkulator\AdvanceCalculator::binaryToDecimal($number)
```
## Support Kulikode-dev

[<img src="https://api.typedream.com/v0/document/public/7ca75252-2895-4260-b592-d3721a624d54_karyakarsa-logo_png.png" width="128">](https://karyakarsa.com/kulikode/support)
[<img src="http://trakteer.id/images/mix/navbar-logo-lite.png" width="120">](https://trakteer.id/kulikode/tip)

## License

[MIT](LICENSE)
