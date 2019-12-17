# Magento 2 Associate Developer Study Guide

# 1 Magento Architecture and Customization Techniques

---

## 1.1 What are the 5 areas of Magento Architecture?

adminhtml, frontend, base,
webapi_rest, webapi_soap and cron.

---

## 1.2 What are the significant steps to add a new module? 

Add Vendor_Module folders to the app/code or vendor dir
Run bin/magento setup:upgrade

---

## 1.3 What are the necessary files to bootstrap a Module?

registration.php, etc/module.xml and optional composer.json

---

## 1.4 What are the different Composer package types? 

module, theme, language or package.

---

## 1.5 When would you place a module in the app/code folder versus another location? 

When you need the module to override and existing module in vendor folder

---

## 1.6 When would you place a module in the vendor folder versus another location? 


When you need a module to be updated through composer.

---

# Describe the Magento directory structure

## What are the naming conventions, and how are namespaces established?

short answer: MAGIC!

There are many naming conventions in Magento. Such as TitleCase for PHP classes and Observers. snake_case for event
names. Module names should follow Vendor_Module. PHP namespaces are established by Vendor\Module. 
--- 

## How can you identify the files responsible for some functionality?

Look in the coorosponding 

--- 


