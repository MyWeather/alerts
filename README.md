MyWeather Alerts
==================

MyWeather Alerts was created by, and is maintained by [Tyler Youschak](http://tjyouschak.me). MyWeather Alerts uses [MyWeather.Today](https://developer.forecast.io/)'s alert API. As for now, api calls are free because it is in beta.

## Requirements
Before installing Alerts, you need to make sure you have `cURL` installed on your server! Chances are this will already be completed!

## Installation

To get the latest version of MyWeather Alerts, simply add the following line to the require block of your `composer.json` file:

```
"myweather/alerts": "~1.0@dev"
```

You'll then need to run `composer install` or `composer update` to download it and have the autoloader updated.

If you're using Laravel 5, then you can register our service provider. Open up `config/app.php` and add the following to the `providers` array.

* `'MyWeather\AlertsServiceProvider'`


## Usage

Docs will come soon...

## Contribute
Have an idea of a new data selector that should be added? Or do you have an idea that will make this package even better? Open an issue report, and we'll have a gander!