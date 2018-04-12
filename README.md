# Magento 2 WebAPI Logger (REST)

A Magento module for logging all REST API requests as text files in var/log/webapi_rest/ folder.

## Installation steps

1. Get the module via composer
   ```
   composer require "vladflonta/magento2-webapi-log":"~0"
   ```

   or via git
   ```
   git clone https://github.com/vladflonta/magento2-webapi-log app/code/VladFlonta/WebApiLog
   ```

2. Enable module

```
bin/magento module:enable VladFlonta_WebApiLog
bin/magento setup:upgrade
```

## License

This project is licensed under the [Open Software License (OSL 3.0)](http://opensource.org/licenses/osl-3.0.php)
