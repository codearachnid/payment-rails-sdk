# payment-rails-sdk

A simple curated collection of payment rails and their related SDKs for developers. Use these references at your own pleasure.

## Check Commerce

ACH, RTP, paper check, and IAT payments through the Check Commerce (OBP Link) API. Also covers stored consumers, recurring subscriptions, hosted payment pages, batch processing, and merchant boarding.

| Package | Use it for | Requires |
|---------|------------|----------|
| [check-commerce-php-sdk](https://github.com/codearachnid/check-commerce-php-sdk) | Any PHP app. Typed requests and responses, automatic token handling, safe retries, any PSR-18 client. | PHP 8.1+ |
| [check-commerce-laravel-sdk](https://github.com/codearachnid/check-commerce-laravel-sdk) | Laravel apps. Adds config, a facade, cache-backed tokens, and `CheckCommerce::fake()` for tests. | PHP 8.3+, Laravel 12 or 13 |

```bash
composer require codearachnid/check-commerce-php-sdk
composer require codearachnid/check-commerce-laravel-sdk
```

## Simply Connect

Nuvei's embedded checkout. Handles the server side of the payment flow: opening a session, verifying the result, receiving webhooks (DMNs), and settling, refunding, or voiding transactions.

| Package | Use it for | Requires |
|---------|------------|----------|
| [simply-connect-php-sdk](https://github.com/codearachnid/simply-connect-php-sdk) | Any PHP app. Handles checksums, credentials, and environment URLs. Built-in cURL client, or bring your own. | PHP 8.2+ |
| [simply-connect-laravel-sdk](https://github.com/codearachnid/simply-connect-laravel-sdk) | Laravel apps. Adds Livewire and Blade checkout components, a JS helper for Vue, React, and Inertia, verified webhooks, a facade, and test fakes. | PHP 8.2+, Laravel 11, 12, or 13 |

```bash
composer require codearachnid/simply-connect-php-sdk
composer require codearachnid/simply-connect-laravel-sdk
```

## License

See [LICENSE](LICENSE).

---

Curated by [Tim Wood](https://github.com/codearachnid), chief architect at [Always Curious](https://alwayscurious.co), a PHP and Laravel agency. When an integration needs more than an SDK, [we build those too](https://alwayscurious.co/services/service-integrations/).
