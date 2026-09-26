![LaravelLux HTML](laravellux-banner.png)

[![Tests](https://github.com/laravellux/html/actions/workflows/tests.yml/badge.svg)](https://github.com/laravellux/html/actions/workflows/tests.yml)
[![Total Downloads](https://poser.pugx.org/LaravelLux/html/downloads)](https://packagist.org/packages/LaravelLux/html)
[![Latest Stable Version](https://poser.pugx.org/LaravelLux/html/v/stable.svg)](https://packagist.org/packages/LaravelLux/html)
[![Latest Unstable Version](https://poser.pugx.org/LaravelLux/html/v/unstable.svg)](https://packagist.org/packages/LaravelLux/html)
[![License](https://poser.pugx.org/LaravelLux/html/license.svg)](https://packagist.org/packages/LaravelLux/html)

> :warning: **Important Update**: The `laravellux/html` package has replaced the `laravelcollective/html` package. Please replace all references of `Collective\Html` in your project with `LaravelLux\Html`. For the majority of applications, no other changes should be necessary, and your project should continue to work as expected. However, always ensure to thoroughly test your project after this update to avoid unexpected issues. Thank you for your understanding.

Official documentation for Forms & Html for The Laravel Framework can be found at the [Laravel Lux by WebSE](https://website.com.se/) website.

## Supported versions

The 7.x release accepts PHP 8.0 or newer and Laravel 6 through 13, where those versions' own dependencies allow the combination. We maintain compatibility with older versions in the package constraints and test it in CI. See the [PHP support schedule](https://www.php.net/supported-versions.php) and [Laravel support policy](https://laravel.com/framework/docs/releases) for upstream security support dates.

Button labels are HTML-escaped by default. For trusted HTML markup, pass `false` as the third argument to `Form::button($label, $options, false)`.
