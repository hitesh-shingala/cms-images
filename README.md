# Magento 2 CMS Page Header Image Module

This Magento 2 module allows store administrators to upload a **featured image** for each CMS page. The uploaded image will be automatically displayed as a **header/banner** on the corresponding CMS page on the frontend.

---

## 📦 Installation

Use Composer to install the module:

```bash
composer require hitesh-shingala/cms-images

After installation, enable the module and clear the cache:

php bin/magento module:enable Magemonkeys_CmsImage
php bin/magento setup:upgrade
php bin/magento cache:flush
