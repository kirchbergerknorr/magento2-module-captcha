# SNK Magento 2 Math Captcha

----

**Extension for Magento 2**

## Overview

----

The module adds a Math Captcha to standard Magento 2 captcha. 

Math Captcha is when the use needs to solve a simple math expression instead of entering lots of letters. 

## Requirements

----

Magento 2.3.*, PHP >7.1

## Installation

----

Install with composer:

 ```
 composer require snk/magento2-module-captcha
```

## Configuration

----

Go to `Stores->Configuration->Customer Configuration->Captcha`

* _Type_ - Choose either the default or math captcha type.
* _Allowed Math Signs_ - which math operations can be used. Division might sometimes be difficult, so consider excluding it.
* _Expression form_ - in which form the expression s shown.   
  Numbers: eg. `2+2=`  
  Words: eg. `two + two =`  
  Equation: eg. `2 + x = 4`
  
* _Label text_ - Text over the captcha with instructions for the user.

## Authors

----

Oleh Kravets <a href="mailto:oleh.kravets@snk.de">oleh.kravets@snk.de</a>

## Lisence

----

MIT