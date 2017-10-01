---
title: AdGroupCriterionEditorialStatus Value Set
ms.service: bing-ads-campaign-management
ms.topic: article
author: eric-urban
ms.author: eur
---
# AdGroupCriterionEditorialStatus Value Set
Defines the editorial review status values of an ad group criterion.

## Syntax
```xml
<xs:simpleType name="AdGroupCriterionEditorialStatus" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:restriction base="xs:string">
    <xs:enumeration value="Active" />
    <xs:enumeration value="Disapproved" />
    <xs:enumeration value="Inactive" />
    <xs:enumeration value="ActiveLimited" />
  </xs:restriction>
</xs:simpleType>
```

## <a name="values"></a>Values

|Value|Description|
|-----------|---------------|
|<a name="active"></a>Active|The criterion passed editorial review.|
|<a name="activelimited"></a>ActiveLimited|The criterion passed editorial review in one or more markets, and one or more elements of the criterion is undergoing editorial review in another market. For example the criterion passed editorial review for Canada and is still pending review in the United States.|
|<a name="disapproved"></a>Disapproved|The criterion failed editorial review.|
|<a name="inactive"></a>Inactive|The criterion is undergoing editorial review.|

## Requirements
Service: [CampaignManagementService.svc v11](https://campaign.api.bingads.microsoft.com/Api/Advertiser/CampaignManagement/v11/CampaignManagementService.svc)  
Namespace: https://bingads.microsoft.com/CampaignManagement/v11  

## Used By
[BiddableAdGroupCriterion](biddableadgroupcriterion.md)  