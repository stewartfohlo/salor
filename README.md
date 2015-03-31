# Salor Retail

Salor Retail is an extremely innovative Point of Sale system. It has been conceived to provide you with all the features that standard, currently available, POS systems  have, but with the possibility of extending and expanding features as your business and technology grows.

Salor Retail is a Ruby-on-Rails based Point of Sale system that is intended for standalone or web deployment. It can be deployed like any standard Rails application, and will work in all modern browsers.

To facilitate desktop deployment, all the components for Salor Retail are packaged as Debian .deb packages and can easily be installed on any Debian based distribution.

For more information please study our [documentation page](http://documentation.thebigrede.net/retail).


## Main features

* Convenient and easy-to-use JS-based POS interface which has been optimized in real stores around the world
* Stock management including stock transactions
* Stock management for piece-package-container unit relationships
* Shipments tracking including stock transactions
* Track Coupons and Gift Cards
* Customer Database and Loyalty Card/Point System
* Sell Items and Item Groups
* Purchase Items from Customers
* Sell variable-priced lottery products and pay out lottery wins
* Timed Discounts on Location of Item, Category, or by SKU
* Generate Barcodes, Labels and Stickers
* Interface with thermal printers, or sticky label printers
* Dynamic payment methods
* Multi-lane, Multi-user, Multi-device
* Change money calculation
* Weighing and price-per-weight
* Buttons on the POS Screen for adding items without SKU
* Flexible Invoice and delivery note generation
* Scale to just about any size without much issue.
* Integration with the woocommerce webstore plugin for Wordpress
* etc.

For more information please study our [documentation page](http://documentation.thebigrede.net/retail).

## Technology

Salor's Feature set is above and beyond practically every other Point of Sale system out there. Salor Retail is intrinsically networked, it is meant to be installed as a server and be accessed by clients. The location of the central server is arbitrary, it can be next to the screen, in the building, or in another country. 

## I18n Support

The user interface of Salor Retail has already been translated into French, Spanish, German, Greek, Russian, Chinese, Finnish and Polish.

## Development Installation

Clone the repository

    cd salor-retail/salor-retail
    bundle install

Copy `config/database.yml.template` to `config/database.yml` and specify database name and database user.

    rake db:create
    rake db:migrate
    rake db:seed
    rails s

Then browse to `http://localhost:3000`. The default password is 000.

For production installations see our page [http:/documentation.thebigrede.net/retail/installation.html](http:/documentation.thebigrede.net/retail/installation.html).


## Demo

[http://srdemo1.salorpos.com](http://srdemo1.salorpos.com)

Log in with the password for the English user interface: 000
