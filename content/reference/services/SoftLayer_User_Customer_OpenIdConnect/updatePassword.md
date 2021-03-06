---
title: "updatePassword"
description: "<strong>This method is deprecated.  Please see documentation for initiatePortalPasswordChange</strong> Update a user's p... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
aliases:
    - "/reference/services/softlayer_user_customer_openidconnect/updatePassword"
---
# [SoftLayer_User_Customer_OpenIdConnect](/reference/services/SoftLayer_User_Customer_OpenIdConnect)::updatePassword

Update a user's portal password


## Overview 
<strong>This method is deprecated.  Please see documentation for initiatePortalPasswordChange</strong> Update a user's password on the SoftLayer customer portal. As with forum passwords, user portal passwords must match the following restrictions. Portal passwords must... 
* ...be over eight characters long.
* ...be under twenty characters long.
* ...contain at least one uppercase letter
* ...contain at least one lowercase letter
* ...contain at least one number
* ...contain one of the special characters _ - | @ . , ? / ! ~ # $ % ^ & * ( ) { } [ ] \ + =
* ...not match your username
* ...not match your forum password
Finally, users can only update their own password. An account's master user can update any of their account users' passwords. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|password| string| Your new portal password|


### Required Headers
* authenticate
* SoftLayer_User_Customer_OpenIdConnectInitParameters

### Optional Headers

### Return Values
boolean

### External Links


* [The SoftLayer Customer Portal](https://manage.softlayer.com)



### associatedMethods

*  [SoftLayer_User_Customer::updateForumPassword](/reference/services/SoftLayer_User_Customer/updateForumPassword )

