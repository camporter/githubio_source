---
title: "getFtpAttributes"
description: "This method returns your login credentials to the CDN FTP server (ftp.cdnlayer.service.softlayer.com server). You must h... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_ContentDelivery_Account"
aliases:
    - "/reference/services/softlayer_network_contentdelivery_account/getFtpAttributes"
---
# [SoftLayer_Network_ContentDelivery_Account](/reference/services/SoftLayer_Network_ContentDelivery_Account)::getFtpAttributes

Returns CDN FTP login credentials


## Overview 
This method returns your login credentials to the CDN FTP server (ftp.cdnlayer.service.softlayer.com server). You must have CDN_FILE_MANAGE privilege. Refer to the service overview of [[SoftLayer_Network_ContentDelivery_Account::createFtpUser|createFtpUser]] method for more information on the CDN FTP server. 

If you want to download raw log files, prefix the username with "LOGS-" (without quotes) when logging in. SoftLayer designed CDN accounts so they can have multiple CDN FTP users. However, this method returns the default CDN FTP user information: multi user support may be implemented in the future. 

-----

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Network_ContentDelivery_AccountInitParameters


### Return Values
* <a href='/reference/datatypes/SoftLayer_Container_Network_Authentication_Data'>SoftLayer_Container_Network_Authentication_Data </a>


### Associated Methods

*  [SoftLayer_Network_ContentDelivery_Account::createFtpUser](/reference/services/SoftLayer_Network_ContentDelivery_Account/createFtpUser )
*  [SoftLayer_Network_ContentDelivery_Account::setFtpPassword](/reference/services/SoftLayer_Network_ContentDelivery_Account/setFtpPassword )



### Error Handling

* SoftLayer_Exception_Public 

> Throws an exception if a user does not have CDN_FILE_MANAGE privilege. 

* SoftLayer_Exception_Public 

> Throws an exception if a CDN account is disabled. 



