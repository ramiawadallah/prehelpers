# prehelpers


```
$ composer require rami-awadallah/prehelpers
```

Once you've run `composer update` you'll need to register the **service provider** in your `config/app.php` file.

```php
'providers' => [
    Ramiawadallah\Prehelpers\PrehelpersServiceProvider::class
]
```

### Usage

#### Configuring Presenters

There's several ways to configure your presenters. First, you can utilize the configuration file, which can be published using the following command:

```
$ php artisan vendor:publish --provider="Ramiawadallah\Prehelpers\PrehelpersServiceProvider"
```