# bagisto-us-tax-rates

This package helps you update your Bagisto tax rates with US tax rates by zip code.

## Usage

Save this to packages/Vendor/USTaxRates.

Go here: https://www.avalara.com/taxrates/en/state-rates.html - and download the appropriate states' tax rates.  Save the csv files to the /Data directory.

Then do:
```php artisan db:seed --class="Vendor\USTaxRates\Database\Seeders\USATaxRatesSeeder"```