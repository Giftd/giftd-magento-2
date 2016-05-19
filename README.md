Requirements
------------
* Magento version 2.0.x.

Installation
------------
1. [Download archive with module](https://github.com/Giftd/giftd-magento-2/) from repository.
2. Upload archive contents to magento root directory. Replace existing files if neccessary.
3. Run commands for enable module:

    bin/magento module:enable Giftd_Platform
    bin/magento setup:upgrade

Configuration
-------------
1. Go to your admin panel. Menu: "Stores" > "Configuration".
2. Select configurable website in store switcher.
3. You will see configuration section "GIFTD" in left menu. Expand it.
4. Click on "Module settings" under "GIFTD" section.
5. Enter API Key and User ID. Save configuration.