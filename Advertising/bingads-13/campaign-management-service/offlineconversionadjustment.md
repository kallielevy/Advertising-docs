---
title: OfflineConversionAdjustment Data Object - Campaign Management
ms.service: bing-ads-campaign-management-service
ms.topic: article
author: eric-urban
ms.author: eur
description: Reserved.
---
# OfflineConversionAdjustment Data Object - Campaign Management
Reserved.

## Syntax
```xml
<xs:complexType name="OfflineConversionAdjustment" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:sequence>
    <xs:element minOccurs="0" name="AdjustmentCurrencyCode" nillable="true" type="xs:string" />
    <xs:element minOccurs="0" name="AdjustmentTime" type="xs:dateTime" />
    <xs:element minOccurs="0" name="AdjustmentType" nillable="true" type="xs:string" />
    <xs:element minOccurs="0" name="AdjustmentValue" nillable="true" type="xs:double" />
    <xs:element minOccurs="0" name="ConversionName" nillable="true" type="xs:string" />
    <xs:element minOccurs="0" name="ConversionTime" type="xs:dateTime" />
    <xs:element minOccurs="0" name="MicrosoftClickId" nillable="true" type="xs:string" />
  </xs:sequence>
</xs:complexType>
```

## <a name="elements"></a>Elements

The [OfflineConversionAdjustment](offlineconversionadjustment.md) object has the following elements: [AdjustmentCurrencyCode](#adjustmentcurrencycode), [AdjustmentTime](#adjustmenttime), [AdjustmentType](#adjustmenttype), [AdjustmentValue](#adjustmentvalue), [ConversionName](#conversionname), [ConversionTime](#conversiontime), [MicrosoftClickId](#microsoftclickid).

|Element|Description|Data Type|
|-----------|---------------|-------------|
|<a name="adjustmentcurrencycode"></a>AdjustmentCurrencyCode|Reserved.|**string**|
|<a name="adjustmenttime"></a>AdjustmentTime|Reserved.|**dateTime**|
|<a name="adjustmenttype"></a>AdjustmentType|Reserved.|**string**|
|<a name="adjustmentvalue"></a>AdjustmentValue|Reserved.|**double**|
|<a name="conversionname"></a>ConversionName|Reserved.|**string**|
|<a name="conversiontime"></a>ConversionTime|Reserved.|**dateTime**|
|<a name="microsoftclickid"></a>MicrosoftClickId|Reserved.|**string**|

## Requirements
Service: [CampaignManagementService.svc v13](https://campaign.api.bingads.microsoft.com/Api/Advertiser/CampaignManagement/v13/CampaignManagementService.svc)  
Namespace: https\://bingads.microsoft.com/CampaignManagement/v13  

## Used By
[ApplyOfflineConversionAdjustments](applyofflineconversionadjustments.md)  
