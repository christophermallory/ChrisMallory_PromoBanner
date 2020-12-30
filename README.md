# ChrisMallory_PromoBanner
```chrismallory/module-promobanner```

## Description
This module adds the ability to display a simple promotional banner throughout your website. It also includes the ability to customize the styles of the promotional banner.

### Screenshots
#### Mobile
![Mobile Screenshot](https://i.postimg.cc/RZYKhpbX/mobile.png)

#### Desktop
![Desktop Screenshot](https://i.postimg.cc/VkvXYP4J/desktop.png)

## Installation

### Using Composer (Recommended)
 - Install the module composer by running `composer require chrismallory/module-promobanner`
 - Enable the module by running `php bin/magento module:enable ChrisMallory_PromoBanner`
 - apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`

### Manual File Transfer
- Clone or unzip this repository to `app/code/ChrisMallory`
- Enable the module by running `php bin/magento module:enable ChrisMallory_PromoBanner`
- Apply database updates by running `php bin/magento setup:upgrade`
- Flush the cache by running `php bin/magento cache:flush`

## Configuration
This module adds a new section in the general tab of your store's configuration. 

### How to Configure
To access this module's configuration, navigate to `Stores > Settings > Configuration`

In the configuration menu click on Header under the General tab.

![General Tab Header Section](https://i.postimg.cc/1Xxf1LXN/Screen-Shot-2020-12-30-at-10-08-09-AM.png)

The Promotional Banner settings will now be displayed. Make your desired changes then click save.

![Promotional Banner Settings](https://i.postimg.cc/63p8hdSy/Screen-Shot-2020-12-30-at-10-00-28-AM.png)

### Settings Explanation

#### Enable
This setting will enable or disable the display of the banner. By default, the banner is disabled.

#### Banner Message
Here you will enter the text shown on the banner. This field is required to be filled out when the banner is enabled. Otherwise, the banner will just display a bar along the bottom of the site header. There is no default for this setting.

*This message will wrap on the frontend when the view is smaller so be careful to not make the message too long so that it doesn't take up too much real estate on mobile.*

#### Banner Link
When filled out, the link entered here will be used when a user clicks on the banner. If no link is provided, the banner will not be clickable. There is no default for this setting.

#### Use Custom Styles
When set to "Yes" you will be able to change the styles used in the banner to better fit your store or promotion. When this is set to "No" the default styles will be used. By default, this is set to no.

#### Background
Here you can enter your preferred banner background color by either using the dropdown color picker that is activated when this field is active or by entering a valid CSS color value. This field will also accept all valid inputs for the [CSS background property](https://www.w3schools.com/cssref/css3_pr_background.asp) to allow for more advanced backgrounds like gradients, opacity, or even images. This setting defaults to #e22626 if not entered and is only shown when the use custom styles setting is set to "Yes".

*Color Picker*

![Background & Font Color Picker](https://i.postimg.cc/mkchvTT4/Screen-Shot-2020-12-30-at-10-02-38-AM.png)

#### Font Size
Enter the font size you'd like your banners message to be. This field will also accept all valid inputs for the [CSS font-size property](https://www.w3schools.com/cssref/css3_pr_font_font-size.asp). This setting defaults to 16px if not entered and is only shown when the use custom styles setting is set to "Yes".

#### Font Color
Here you can enter your preferred banner message font color by either using the dropdown color picker that is activated when this field is active or by entering a valid CSS color value. This field will also accept all valid inputs for the [CSS color property](https://www.w3schools.com/cssref/css3_pr_text_color.asp) to allow for more advanced colors such as gradients and opacity. This setting defaults to #ffffff if not entered and is only shown when the use custom styles setting is set to "Yes".

*Color Picker*

![Background & Font Color Picker](https://i.postimg.cc/mkchvTT4/Screen-Shot-2020-12-30-at-10-02-38-AM.png)

#### Font Weight
The font weight sets how thick or thin characters in text should be displayed. This can be set between 100 and 900 by the hundreds (100, 200, 300, 400, etc). This field will also accept all valid inputs for the [CSS font-weight property](https://www.w3schools.com/cssref/css3_pr_font_weight.asp).  This setting defaults to 600 if not entered and is only shown when the use custom styles setting is set to "Yes".

*Not all font weights are supported by all fonts*

## Compatibility
This module has been tested and validated to work on Magento versions 2.3 and higher.

This module uses a ViewModel and should be compatible with versions 2.2 and higher but has not been tested on versions lower than 2.3.

## Bugs & Issues
If you find a bug or issue please create a new issue [here](https://github.com/christophermallory/ChrisMallory_PromoBanner/issues) and include as much detail and context as possible including screenshots.

## License
This module is licensed under the Open Software License V3.0 which you can refer to [here](LICENSE.txt).
