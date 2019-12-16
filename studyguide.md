# What are the 5 areas of Magento Architecture?

adminhtml, frontend, base,
webapi_rest, webapi_soap and cron.

---

# What are the significant steps to add a new module? 

Add Vendor_Module folders to the app/code or vendor dir
Run bin/magento setup:upgrade

---

# What are the necessary files to bootstrap a Module?

registration.php, etc/module.xml and optional composer.json

---

# What are the different Composer package types? 

module, theme, language or package.

---

# When would you place a module in the app/code folder versus another location? 

When you need the module to override and existing module in vendor folder

---

# When would you place a module in the vendor folder versus another location? 

When you need a module to be updated through composer.

---
