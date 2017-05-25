CONTENTS OF THIS FILE
---------------------

  * Introduction
  * Requirements
  * Installation
  * Configuration
  * Troubleshooting
  * Maintainers

INTRODUCTION
-----------
  * This module is the light weight module to expose Drupal node as JSON
 This module provides a URL that responds with a JSON representation of a
 given node with the content type "page" also authenticated with Site API Key
 and a node id (nid) of an appropriate node are present,
 otherwise it will respond with "access denied"
  * Get the JSON value by Enabling this light weight module
  [base_url]/page_json/%/%
  ARG1 = Content type machine name
  ARG2 = Node ID

 Example:
  [base_url]/page_json/page/1 = "page" is content type name and '1' is nid
  or
  [base_url]/page_json/article/2 = "article" is content type name and "2" is nid
  To represent a given node with the content type "page"

  Note:
  For the Give Senario Please use the below URL:
  [base_url]/page_json/page/[nid] to get the JSON of type only "page"

REQUIREMENTS
------------
  This project does not require any support modules

INSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-8
   for further information.

CONFIGURATION
-------------
 * Configure the Site API Key in the following link Configuration » Basic Site Configuration </br>
 [base_url]/admin/config/system/site-information and fill the field Site API Key

TROUBLESHOOTING
---------------
 * If the menu URL does not display, check the following:
  - Clear the drupal cache if the menu is not displayed

MAINTAINERS
-----------
Current maintainers:
Devaraj johnson https://github.com/devarajjohnson23
