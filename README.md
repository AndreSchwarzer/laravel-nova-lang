<p align="center"><img alt="Laraflash" src="logo.png" width="450"></p>

<p align="center">This package provides the language support for <b>Laravel Nova</b>.</p>

<p align="center">Feel free to submit your language or update an existing one by sending a PR to help other people.</p>

## Installation

```bash
composer require coderello/laravel-nova-lang
```

## Usage

Publish translations for one language:
```bash
php artisan nova-lang:publish de
```

Publish translations for multiple languages:
```bash
php artisan nova-lang:publish de,ru
```

Publish translations with overriding of existing ones:
```bash
php artisan nova-lang:publish de,ru --force
```

## Available Languages

| Language | Code | Status | Thanks to |
| --- | --- | --- | --- |
| English | en | completed | [taylorotwell](https://github.com/taylorotwell) |
| Russian | ru | completed | [hivokas](https://github.com/hivokas) |
| German | de | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Dutch | nl | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Turkish | tr | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Ukrainian | uk | completed | [coderello](https://github.com/coderello) |
| Arabic | ar | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Spanish | es | completed | [ajmariduena](https://github.com/ajmariduena) |
| French | fr | completed | [Marceau Ka](https://github.com/MarceauKa) |
| Polish | pl | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Polish | pl | machine translation, needs verification | [coderello](https://github.com/coderello) |
| Chinese (Simplified) | zh-CN | completed | [jcc](https://github.com/jcc) |
| Romanian | ro | completed | [BTeodorWork](https://github.com/BTeodorWork) |
| Chinese | cn | completed | [Pierolin](https://github.com/Pierolin) |
| Chinese (Taiwan) | zh-TW | completed | [CasperLaiTW](https://github.com/CasperLaiTW) |
| Georgian | ka | completed | [akalongman](https://github.com/akalongman) |
