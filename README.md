<p align="center">
    <a href="https://www.avored.com/" target="_blank"><img src="logo.svg" height="86" alt="AvoRed"></a>
</p>

<p align="center">
    <a href="https://circleci.com/gh/avored/framework/tree/master"><img src="https://circleci.com/gh/avored/framework/tree/master.svg?style=shield" alt="CircleCI"></a>
    <a href="https://packagist.org/packages/avored/framework"><img src="https://poser.pugx.org/avored/framework/downloads" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/avored/framework"><img src="https://poser.pugx.org/avored/framework/v/stable" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/avored/framework"><img src="https://poser.pugx.org/avored/framework/license" alt="License"></a>
</p>


# Core package for avored shopping cart
AvoRed Framework contains the core features for the AvoRed E-commerce for Laravel. It is the base behind the AvoRed and Laravel Ecommerce.

#### Installation
The AvoRed E-commerce framework is provided as a composer package, so it makes installation of AvoRed as easy as:

     composer require avored/framework

At this stage we hav been using version 5.8 of the Laravel framework. If you are using an older version, let us know at our [Discussion Forum](https://www.avored.com/discussion). We can test if it works and add support for that version too.

Once this is finished, you will need to run a few commands to finish up and then you are ready to roll.

#### Publish the Files
Publish the AvoRed E-commerce framework config file and assets (JS/CSS and Images):

    php artisan vendor:publish --provider="AvoRed\Framework\AvoRedProvider"

Once all the files are published, we can run the command to install the required database tables.

    php artisan avored:install

We are almost there. Now create your Administrator Account by running:

    php artisan avored:admin:make


That's It. 

Now visit:

    yoursiteurl.com/admin
