# ecommerce-modules

In root of magento2 repo, create folder:
```
mkdir app/code
```
Clone 3 modules in this git repo to app/code folder:
```
git clone https://github.com/shizuku-nem/ecommerce-modules.git app/code
```
Upgrade magento and chill with result:
```
php bin/magento setup:upgrade
```
```
php bin/magento module:enable Currency_CustomWidget News_CustomWidget Weather_CustomWidget
```

```
php bin/magento cache:flush
```

```
php bin/magento setup:di:compile
```
