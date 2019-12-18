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
## Where are the files containing JavaScript, HTML, and PHP located?

view/frontend/web/js
view/frontend/requirejs-config.js
view/frontend/layout
view/frontend/templates

---
## How can you identify the files responsible for some functionality?

Look in the coorosponding functional area. Example: Controller files will be in /Controller 

--- 

## Which configuration files are important in the development cycle?

module.xml
acl.xml
config.xml
crontab.xml
di.xml
email_templates.xml
events.xml
indexer.xml
adminhtml/menu.xml
mview.xml
[area]/routes.xml
adminhtml/system.xml
view.xml
webapi.xml
widget.xml

---

## How do you identify the configuration scope for a given variable? 


---
## How do native Magento scopes (for example, price or inventory) affect development and decision-making processes?  


---


