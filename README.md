# AdvancedImportExport

<h2>Composer Installation Instructions</h2>
Configure composer to search for new repository
<pre>
composer config repositories.IFlairTech/AdvancedImportExport vcs https://github.com/IFlairTech/AdvancedImportExport
</pre>
Then, install module as below:
<pre>  
  composer require iFlair/advancedimportexport
</pre>
Then, enable module and install in Magento:
<pre>
php bin/magento module:enable IFlair_AdvancedImportExport
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
php bin/magento cache:clean
</pre>
