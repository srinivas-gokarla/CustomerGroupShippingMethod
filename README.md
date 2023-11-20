<h1 align="center">GroupedCustomerGroupShippingMethod-magento 2</h1>

<div align="center">
  <img src="https://img.shields.io/badge/magento-2.X-brightgreen.svg?logo=magento&longCache=true" alt="Supported Magento Versions" />

## Table of contents
<div align="left">


- [Usage](#usage)
- [Installation](#installation)
- [Credits](#credits)

## Usage

In default magento there is a default feature where product prices
can be set to customer groups. so basically if a customer is
associated with a general customer group and they can have their
own product price however there is no option for setting a
different shipping prices based on the customer group.
<h3>Solution</h3>
So here is the solution where you can add shipping price
for selected customer group from settings.

<br>
<img src="https://imgur.com/XxzIZUc.png" />

<img src="https://imgur.com/LbDHhxU.png" />
<img src="https://imgur.com/KInf7Zq.png" />


## Installation

**Using Composer**

* composer require srinivas/module-customergroupshippingmethod
* bin/magento setup:upgrade
* bin/magento setup:di:compile

**_or_**

* Click Code dropdown in githb & Download
* Unzip the file
* Create Directory(s) as app/code/Srinivas/CustomerGroupShippingMethod
* copy all above files and paste inside the folder CustomerGroupShippingMethod
* bin/magento setup:upgrade
* bin/magento setup:di:compile

## Credits

### Srinivas Gokarla

My name is Srinivas Gokarla and I'm the creator of this repo. I'm a Magento 2 Developer.
- <a href="https://www.linkedin.com/in/srinivas-gokarla-4a4a31226/" target="_blank">🔗 Connect with me on LinkedIn</a>
- <a href="mailto:gokarlasrinivas99@gmail.com">💌 Contact me</a>
