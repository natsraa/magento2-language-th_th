# magento2-language-th_th
Thai language, Thai translation


## Run the following command lines
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy en_US
php bin/magento setup:static-content:deploy th_TH
php bin/magento cache:flush

# Go to the Magento Admin - Stores - Configuration - General - General - Locale Options

=> Set the Locale to Thai (Thailand), then press the "Save Config" button.

# Go to Account Setting, set the Interface Locale to ไทย (ไทย) / Thai (Thaoland), then press the "Save Account" button.

=> Run the command line: php bin/magento cache:flush

Test and see the results.
