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

## License

[MIT](LICENSE)
