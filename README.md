<p align="center">
    <a href="https://smartarget.com" target="_blank">
        <img src="https://smartarget.com/logo.png" width="250px" alt="Monsieur Biz logo" />
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://smartarget.com/agence-web-experte-sylius" target="_blank">
        <img src="https://demo.sylius.com/assets/shop/img/logo.png" width="200px" alt="Sylius logo" />
    </a>
</p>

<h1 align="center">Alert Message</h1>

[![Alert Message Plugin license](https://img.shields.io/github/license/smartarget/SyliusSmartargetWhatsappContactUsPlugin?public)](https://github.com/smartarget/SyliusSmartargetWhatsappContactUsPlugin/blob/master/LICENSE.txt)
![Tests](https://github.com/smartarget/SyliusSmartargetWhatsappContactUsPlugin/workflows/Tests/badge.svg)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/smartarget/SyliusSmartargetWhatsappContactUsPlugin/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/smartarget/SyliusSmartargetWhatsappContactUsPlugin/?branch=master)

This plugins allows you to add simple messages on your shop.  
The messages can be different for logged-in customers.

The message is displayed just after the opening `body`. You can change the HTML template directly in the admin panel.  
By default it'll use the Semantic UI classes.

![](screenshot.png) 

## Installation

**Beware!**

> This installation instruction assumes that you're using Symfony Flex.

1. Require the plugin using composer

    ```bash
    composer require smartarget/sylius-smartarget-whatsapp-contact-us-plugin
    ```

2. Generate & Run Doctrine migrations

    ```
    ./bin/console doctrine:migration:diff
    ./bin/console doctrine:migration:migrate
    ```

## How it works

You just have to go in the Alert Messages section in your admin panel and add new message(s)!

## Examples

You could use this plugin to:

- Tell your customer how you are dealing with an epidemic outbreak.
- Make a legal announcement.
- Give all your logged-in customers a very attractive coupon code.

Being able to add a well seen message on your shop can be useful.

## Testing

See [TESTING.md](TESTING.md).

## Contributing

You can open an issue or a Pull Request if you want! 😘    
Thank you!
