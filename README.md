# Webp
Magento2 module for converting images to webp format

<sup>It's a metapackage for the [original repository](https://github.com/swissup/module-webp).</sup>

### Installation

Run the following commands:
```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/webp --prefer-source
bin/magento module:enable Swissup_Core Swissup_Webp
bin/magento setup:upgrade
bin/magento setup:di:compile
```

