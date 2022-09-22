<p align="center"><img src="/art/socialcard.png" alt="Social Card of Laravel Nice Error Pages"></p>

Back with the release of Laravel 5.7, [Steve Schoger](https://twitter.com/steveschoger) created illustrations for the common error pages like 403, 404, 500, and 503. Each one was included in the core as an SVG.

This package allows to use them on Laravel 6,7,8 & 9 🚀

Add package to your Laravel project:
```
composer require charrua/laravel-nice-error-pages
```

Publish vendor files:
```
php artisan vendor:publish --provider="Charrua\Errors\ErrorsServiceProvider"
```

This will create a folder in `public/svg` with the illustrations and another folder in `views/errors` with blade error pages. You can customize them as you want.

Enjoy 🤗

*Note: This package is a fork of [laravelcollective/errors](https://github.com/LaravelCollective/errors). Originally created by [Matt Lantz](https://twitter.com/Mattylantz).*