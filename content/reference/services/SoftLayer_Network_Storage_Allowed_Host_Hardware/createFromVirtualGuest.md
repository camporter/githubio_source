---
title: "createFromVirtualGuest"
description: "This method is used to create a new SoftLayer_Network_Storage_Allowed_Host using an existing SoftLayer_Virtual_Guest obj... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Allowed_Host_Hardware"
aliases:
    - "/reference/services/softlayer_network_storage_allowed_host_hardware/createFromVirtualGuest"
---
# [SoftLayer_Network_Storage_Allowed_Host_Hardware](/reference/services/SoftLayer_Network_Storage_Allowed_Host_Hardware)::createFromVirtualGuest

Creates and returns a new SoftLayer_Network_Storage_Allowed_Host.


## Overview 
This method is used to create a new SoftLayer_Network_Storage_Allowed_Host using an existing SoftLayer_Virtual_Guest object's id. 

-----

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|virtualGuestId| integer| The ID of the SoftLayer_Virtual_Guest object to create a SoftLayer_Network_Storage_Allowed_Host object for.|
|iqn| string| The IQN to use when creating the SoftLayer_Network_Storage_Allowed_Host object, provide an empty string to have one generated automatically.|


### Required Headers
* authenticate


### Optional Headers
* SoftLayer_Network_Storage_Allowed_Host_HardwareObjectMask
* SoftLayer_ObjectMask

### Return Values
* <a href='/reference/datatypes/SoftLayer_Network_Storage_Allowed_Host_Hardware'>SoftLayer_Network_Storage_Allowed_Host_Hardware </a>




