---
title: "Product table/entity reference (Dynamics 365 Sales) | Microsoft Docs"
description: "Includes schema information and supported messages for the Product table/entity."
ms.date: 02/17/2023
ms.service: dynamics-365-sales
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "udaykirang"
ms.author: "udag"
search.audienceType: 
  - developer
---

# Product table/entity reference

> [!NOTE]
> Unsure about table vs. entity? See [Developers: Understand terminology in Microsoft Dataverse](/powerapps/developer/data-platform/understand-terminology).

Information about products and their pricing information.

**Added by**: Product Management Solution


## Messages

|Message|SDK Assembly|
|-|-|
|Associate|<xref:Microsoft.Xrm.Sdk.Messages.AssociateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Associate*>|
|CloneProduct|<xref:Microsoft.Crm.Sdk.Messages.CloneProductRequest>|
|Create|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Disassociate|<xref:Microsoft.Xrm.Sdk.Messages.DisassociateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Disassociate*>|
|PublishProductHierarchy|<xref:Microsoft.Crm.Sdk.Messages.PublishProductHierarchyRequest>|
|Retrieve|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RevertProduct|<xref:Microsoft.Crm.Sdk.Messages.RevertProductRequest>|
|SetState|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|Products|
|DisplayCollectionName|Products|
|DisplayName|Product|
|EntitySetName|products|
|IsBPFEntity|False|
|LogicalCollectionName|products|
|LogicalName|product|
|OwnershipType|OrganizationOwned|
|PrimaryIdAttribute|productid|
|PrimaryNameAttribute|name|
|SchemaName|Product|

<a name="writable-attributes"></a>

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [CurrentCost](#BKMK_CurrentCost)
- [DefaultUoMId](#BKMK_DefaultUoMId)
- [DefaultUoMScheduleId](#BKMK_DefaultUoMScheduleId)
- [Description](#BKMK_Description)
- [DMTImportState](#BKMK_DMTImportState)
- [EntityImage](#BKMK_EntityImage)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsKit](#BKMK_IsKit)
- [IsReparented](#BKMK_IsReparented)
- [IsStockItem](#BKMK_IsStockItem)
- [msdyn_gdproptout](#BKMK_msdyn_gdproptout)
- [Name](#BKMK_Name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [ParentProductId](#BKMK_ParentProductId)
- [Price](#BKMK_Price)
- [PriceLevelId](#BKMK_PriceLevelId)
- [ProcessId](#BKMK_ProcessId)
- [ProductId](#BKMK_ProductId)
- [ProductNumber](#BKMK_ProductNumber)
- [ProductStructure](#BKMK_ProductStructure)
- [ProductTypeCode](#BKMK_ProductTypeCode)
- [ProductUrl](#BKMK_ProductUrl)
- [QuantityDecimal](#BKMK_QuantityDecimal)
- [QuantityOnHand](#BKMK_QuantityOnHand)
- [Size](#BKMK_Size)
- [StageId](#BKMK_StageId)
- [StandardCost](#BKMK_StandardCost)
- [StateCode](#BKMK_StateCode)
- [StatusCode](#BKMK_StatusCode)
- [StockVolume](#BKMK_StockVolume)
- [StockWeight](#BKMK_StockWeight)
- [SubjectId](#BKMK_SubjectId)
- [SupplierName](#BKMK_SupplierName)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
- [TraversedPath](#BKMK_TraversedPath)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)
- [ValidFromDate](#BKMK_ValidFromDate)
- [ValidToDate](#BKMK_ValidToDate)
- [VendorID](#BKMK_VendorID)
- [VendorName](#BKMK_VendorName)
- [VendorPartNumber](#BKMK_VendorPartNumber)


### <a name="BKMK_CurrentCost"></a> CurrentCost

|Property|Value|
|--------|-----|
|Description|Current cost for the product item. Used in price calculations.|
|DisplayName|Current Cost|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|currentcost|
|MaxValue|1000000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_DefaultUoMId"></a> DefaultUoMId

|Property|Value|
|--------|-----|
|Description|Default unit for the product.|
|DisplayName|Default Unit|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|defaultuomid|
|RequiredLevel|ApplicationRequired|
|Targets|uom|
|Type|Lookup|


### <a name="BKMK_DefaultUoMScheduleId"></a> DefaultUoMScheduleId

|Property|Value|
|--------|-----|
|Description|Default unit group for the product.|
|DisplayName|Unit Group|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|defaultuomscheduleid|
|RequiredLevel|ApplicationRequired|
|Targets|uomschedule|
|Type|Lookup|


### <a name="BKMK_Description"></a> Description

|Property|Value|
|--------|-----|
|Description|Description of the product.|
|DisplayName|Description|
|Format|TextArea|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|description|
|MaxLength|2000|
|RequiredLevel|None|
|Type|Memo|


### <a name="BKMK_DMTImportState"></a> DMTImportState

|Property|Value|
|--------|-----|
|Description|Internal Use Only|
|DisplayName|Internal Use Only|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|dmtimportstate|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_EntityImage"></a> EntityImage

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Shows the default image for the record.|
|DisplayName|Entity Image|
|IsPrimaryImage|True|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|entityimage|
|MaxHeight|144|
|MaxWidth|144|
|RequiredLevel|None|
|Type|Image|


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_IsKit"></a> IsKit

|Property|Value|
|--------|-----|
|Description|Information that specifies whether the product is a kit.|
|DisplayName|Is Kit|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|iskit|
|RequiredLevel|None|
|Type|Boolean|

#### IsKit Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_IsReparented"></a> IsReparented

**Added by**: Product Management Patch Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Is Reparented|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|isreparented|
|RequiredLevel|None|
|Type|Boolean|

#### IsReparented Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_IsStockItem"></a> IsStockItem

|Property|Value|
|--------|-----|
|Description|Information about whether the product is a stock item.|
|DisplayName|Stock Item|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|isstockitem|
|RequiredLevel|None|
|Type|Boolean|

#### IsStockItem Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_msdyn_gdproptout"></a> msdyn_gdproptout

**Added by**: Predictive Opportunity Scoring Solution

|Property|Value|
|--------|-----|
|Description|Describes whether product is opted out or not|
|DisplayName|GDPR Optout|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_gdproptout|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_gdproptout Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_Name"></a> Name

|Property|Value|
|--------|-----|
|Description|Name of the product.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|True|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ParentProductId"></a> ParentProductId

|Property|Value|
|--------|-----|
|Description|Specifies the parent product family hierarchy.|
|DisplayName|Parent|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|parentproductid|
|RequiredLevel|None|
|Targets|product|
|Type|Lookup|


### <a name="BKMK_Price"></a> Price

|Property|Value|
|--------|-----|
|Description|List price for the product item. Used in price calculations.|
|DisplayName|List Price|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|price|
|MaxValue|1000000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_PriceLevelId"></a> PriceLevelId

|Property|Value|
|--------|-----|
|Description|Select the default price list for the product.|
|DisplayName|Default Price List|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|pricelevelid|
|RequiredLevel|Recommended|
|Targets|pricelevel|
|Type|Lookup|


### <a name="BKMK_ProcessId"></a> ProcessId

|Property|Value|
|--------|-----|
|Description|Contains the id of the process associated with the entity.|
|DisplayName|Process Id|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|processid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_ProductId"></a> ProductId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the product.|
|DisplayName|Product|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|productid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ProductNumber"></a> ProductNumber

|Property|Value|
|--------|-----|
|Description|User-defined product ID.|
|DisplayName|Product ID|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|productnumber|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ProductStructure"></a> ProductStructure

|Property|Value|
|--------|-----|
|Description|Product Structure.|
|DisplayName|Product Structure|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|productstructure|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### ProductStructure Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Product||
|2|Product Family||
|3|Product Bundle||



### <a name="BKMK_ProductTypeCode"></a> ProductTypeCode

|Property|Value|
|--------|-----|
|Description|Type of product.|
|DisplayName|Product Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|producttypecode|
|RequiredLevel|None|
|Type|Picklist|

#### ProductTypeCode Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Sales Inventory||
|2|Miscellaneous Charges||
|3|Services||
|4|Flat Fees||



### <a name="BKMK_ProductUrl"></a> ProductUrl

|Property|Value|
|--------|-----|
|Description|URL for the Website associated with the product.|
|DisplayName|URL|
|FormatName|Url|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|producturl|
|MaxLength|255|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_QuantityDecimal"></a> QuantityDecimal

|Property|Value|
|--------|-----|
|Description|Number of decimal places that can be used in monetary amounts for the product.|
|DisplayName|Decimals Supported|
|Format|None|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|quantitydecimal|
|MaxValue|5|
|MinValue|0|
|RequiredLevel|ApplicationRequired|
|Type|Integer|


### <a name="BKMK_QuantityOnHand"></a> QuantityOnHand

|Property|Value|
|--------|-----|
|Description|Quantity of the product in stock.|
|DisplayName|Quantity On Hand|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|quantityonhand|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|RequiredLevel|None|
|Type|Decimal|


### <a name="BKMK_Size"></a> Size

|Property|Value|
|--------|-----|
|Description|Product size.|
|DisplayName|Size|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|size|
|MaxLength|200|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_StageId"></a> StageId

|Property|Value|
|--------|-----|
|Description|Contains the id of the stage where the entity is located.|
|DisplayName|(Deprecated) Stage Id|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|stageid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_StandardCost"></a> StandardCost

|Property|Value|
|--------|-----|
|Description|Standard cost for the product item. Used in price calculations.|
|DisplayName|Standard Cost|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|standardcost|
|MaxValue|1000000000000|
|MinValue|0|
|Precision|2|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_StateCode"></a> StateCode

|Property|Value|
|--------|-----|
|Description|Status of the product.|
|DisplayName|Status|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### StateCode Choices/Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Active|1|Active|
|1|Retired|2|Inactive|
|2|Draft|0|Draft|
|3|Under Revision|3|Under Revision|



### <a name="BKMK_StatusCode"></a> StatusCode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the product.|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### StatusCode Choices/Options

|Value|Label|State|
|-----|-----|-----|
|0|Draft|2|
|1|Active|0|
|2|Retired|1|
|3|Under Revision|3|



### <a name="BKMK_StockVolume"></a> StockVolume

|Property|Value|
|--------|-----|
|Description|Stock volume of the product.|
|DisplayName|Stock Volume|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|stockvolume|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|RequiredLevel|None|
|Type|Decimal|


### <a name="BKMK_StockWeight"></a> StockWeight

|Property|Value|
|--------|-----|
|Description|Stock weight of the product.|
|DisplayName|Stock Weight|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|stockweight|
|MaxValue|1000000000|
|MinValue|0|
|Precision|2|
|RequiredLevel|None|
|Type|Decimal|


### <a name="BKMK_SubjectId"></a> SubjectId

|Property|Value|
|--------|-----|
|Description|Select a category for the product.|
|DisplayName|Subject|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|subjectid|
|RequiredLevel|None|
|Targets|subject|
|Type|Lookup|


### <a name="BKMK_SupplierName"></a> SupplierName

|Property|Value|
|--------|-----|
|Description|Name of the product's supplier.|
|DisplayName|Supplier Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|suppliername|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_TransactionCurrencyId"></a> TransactionCurrencyId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the currency associated with the product.|
|DisplayName|Currency|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|transactioncurrencyid|
|RequiredLevel|None|
|Targets|transactioncurrency|
|Type|Lookup|


### <a name="BKMK_TraversedPath"></a> TraversedPath

|Property|Value|
|--------|-----|
|Description|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|
|DisplayName|(Deprecated) Traversed Path|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|traversedpath|
|MaxLength|1250|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_ValidFromDate"></a> ValidFromDate

|Property|Value|
|--------|-----|
|DateTimeBehavior|DateOnly|
|Description|Date from which this product is valid.|
|DisplayName|Valid From|
|Format|DateOnly|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|validfromdate|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ValidToDate"></a> ValidToDate

|Property|Value|
|--------|-----|
|DateTimeBehavior|DateOnly|
|Description|Date to which this product is valid.|
|DisplayName|Valid To|
|Format|DateOnly|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|validtodate|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_VendorID"></a> VendorID

|Property|Value|
|--------|-----|
|Description|Unique identifier of vendor supplying the product.|
|DisplayName|Vendor ID|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|vendorid|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_VendorName"></a> VendorName

|Property|Value|
|--------|-----|
|Description|Name of the product vendor.|
|DisplayName|Vendor|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|vendorname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_VendorPartNumber"></a> VendorPartNumber

|Property|Value|
|--------|-----|
|Description|Unique part identifier in vendor catalog of this product.|
|DisplayName|Vendor Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|vendorpartnumber|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|

<a name="read-only-attributes"></a>

## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByExternalParty](#BKMK_CreatedByExternalParty)
- [CreatedByExternalPartyName](#BKMK_CreatedByExternalPartyName)
- [CreatedByExternalPartyYomiName](#BKMK_CreatedByExternalPartyYomiName)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [CurrentCost_Base](#BKMK_CurrentCost_Base)
- [DefaultUoMIdName](#BKMK_DefaultUoMIdName)
- [DefaultUoMScheduleIdName](#BKMK_DefaultUoMScheduleIdName)
- [EntityImage_Timestamp](#BKMK_EntityImage_Timestamp)
- [EntityImage_URL](#BKMK_EntityImage_URL)
- [EntityImageId](#BKMK_EntityImageId)
- [ExchangeRate](#BKMK_ExchangeRate)
- [HierarchyPath](#BKMK_HierarchyPath)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByExternalParty](#BKMK_ModifiedByExternalParty)
- [ModifiedByExternalPartyName](#BKMK_ModifiedByExternalPartyName)
- [ModifiedByExternalPartyYomiName](#BKMK_ModifiedByExternalPartyYomiName)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [OrganizationId](#BKMK_OrganizationId)
- [OrganizationIdName](#BKMK_OrganizationIdName)
- [ParentProductIdName](#BKMK_ParentProductIdName)
- [Price_Base](#BKMK_Price_Base)
- [PriceLevelIdName](#BKMK_PriceLevelIdName)
- [StandardCost_Base](#BKMK_StandardCost_Base)
- [SubjectIdName](#BKMK_SubjectIdName)
- [TransactionCurrencyIdName](#BKMK_TransactionCurrencyIdName)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the product.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByExternalParty"></a> CreatedByExternalParty

|Property|Value|
|--------|-----|
|Description|Shows the external party who created the record.|
|DisplayName|Created By (External Party)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdbyexternalparty|
|RequiredLevel|None|
|Targets|externalparty|
|Type|Lookup|


### <a name="BKMK_CreatedByExternalPartyName"></a> CreatedByExternalPartyName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyexternalpartyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByExternalPartyYomiName"></a> CreatedByExternalPartyYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyexternalpartyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByName"></a> CreatedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the product.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CurrentCost_Base"></a> CurrentCost_Base

|Property|Value|
|--------|-----|
|Description|Value of the Current Cost in base currency.|
|DisplayName|Current Cost (Base)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|currentcost_base|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_DefaultUoMIdName"></a> DefaultUoMIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|defaultuomidname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_DefaultUoMScheduleIdName"></a> DefaultUoMScheduleIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|defaultuomscheduleidname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_EntityImage_Timestamp"></a> EntityImage_Timestamp

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|entityimage_timestamp|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|


### <a name="BKMK_EntityImage_URL"></a> EntityImage_URL

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Url|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|entityimage_url|
|MaxLength|200|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_EntityImageId"></a> EntityImageId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|entityimageid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_ExchangeRate"></a> ExchangeRate

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Exchange rate for the currency associated with the product with respect to the base currency.|
|DisplayName|Exchange Rate|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|exchangerate|
|MaxValue|100000000000|
|MinValue|0.000000000001|
|Precision|12|
|RequiredLevel|None|
|Type|Decimal|


### <a name="BKMK_HierarchyPath"></a> HierarchyPath

|Property|Value|
|--------|-----|
|Description|Hierarchy path of the product.|
|DisplayName|Hierarchy Path|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|hierarchypath|
|MaxLength|450|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who last modified the product.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByExternalParty"></a> ModifiedByExternalParty

|Property|Value|
|--------|-----|
|Description|Shows the external party who modified the record.|
|DisplayName|Modified By (External Party)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedbyexternalparty|
|RequiredLevel|None|
|Targets|externalparty|
|Type|Lookup|


### <a name="BKMK_ModifiedByExternalPartyName"></a> ModifiedByExternalPartyName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyexternalpartyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByExternalPartyYomiName"></a> ModifiedByExternalPartyYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyexternalpartyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who last modified the product.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|--------|-----|
|Description|Unique identifier for the organization|
|DisplayName|Organization Id|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|organizationid|
|RequiredLevel|SystemRequired|
|Targets|organization|
|Type|Lookup|


### <a name="BKMK_OrganizationIdName"></a> OrganizationIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|organizationidname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ParentProductIdName"></a> ParentProductIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|parentproductidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_Price_Base"></a> Price_Base

|Property|Value|
|--------|-----|
|Description|Value of the List Price in base currency.|
|DisplayName|List Price (Base)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|price_base|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_PriceLevelIdName"></a> PriceLevelIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|pricelevelidname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_StandardCost_Base"></a> StandardCost_Base

|Property|Value|
|--------|-----|
|Description|Value of the Standard Cost in base currency.|
|DisplayName|Standard Cost (Base)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|standardcost_base|
|MaxValue|922337203685477|
|MinValue|-922337203685477|
|Precision|4|
|PrecisionSource|1|
|RequiredLevel|None|
|Type|Money|


### <a name="BKMK_SubjectIdName"></a> SubjectIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|subjectidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_TransactionCurrencyIdName"></a> TransactionCurrencyIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|transactioncurrencyidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [product_parent_product](#BKMK_product_parent_product)
- [Product_ProductAssociation_AssocProd](#BKMK_Product_ProductAssociation_AssocProd)
- [Product_ProductAssociation_Prod](#BKMK_Product_ProductAssociation_Prod)
- [product_ProductSubstitute_substitutedproductid](#BKMK_product_ProductSubstitute_substitutedproductid)
- [product_ProductSubstitute_productid](#BKMK_product_ProductSubstitute_productid)
- [product_price_levels](#BKMK_product_price_levels)
- [opportunity_products](#BKMK_opportunity_products)
- [product_invoice_details](#BKMK_product_invoice_details)
- [product_order_details](#BKMK_product_order_details)
- [product_quote_details](#BKMK_product_quote_details)


### <a name="BKMK_product_parent_product"></a> product_parent_product

Same as the [product_parent_product](product.md#BKMK_product_parent_product) many-to-one relationship for the [product](product.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|product|
|ReferencingAttribute|parentproductid|
|IsHierarchical|True|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_parent_product|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_Product_ProductAssociation_AssocProd"></a> Product_ProductAssociation_AssocProd

Same as the [Product_ProductAssociation_AssocProd](productassociation.md#BKMK_Product_ProductAssociation_AssocProd) many-to-one relationship for the [productassociation](productassociation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|productassociation|
|ReferencingAttribute|associatedproduct|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|Product_ProductAssociation_AssocProd|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Restrict<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_Product_ProductAssociation_Prod"></a> Product_ProductAssociation_Prod

Same as the [Product_ProductAssociation_Prod](productassociation.md#BKMK_Product_ProductAssociation_Prod) many-to-one relationship for the [productassociation](productassociation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|productassociation|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|Product_ProductAssociation_Prod|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_ProductSubstitute_substitutedproductid"></a> product_ProductSubstitute_substitutedproductid

Same as the [product_ProductSubstitute_substitutedproductid](productsubstitute.md#BKMK_product_ProductSubstitute_substitutedproductid) many-to-one relationship for the [productsubstitute](productsubstitute.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|productsubstitute|
|ReferencingAttribute|substitutedproductid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_ProductSubstitute_substitutedproductid|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_ProductSubstitute_productid"></a> product_ProductSubstitute_productid

Same as the [product_ProductSubstitute_productid](productsubstitute.md#BKMK_product_ProductSubstitute_productid) many-to-one relationship for the [productsubstitute](productsubstitute.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|productsubstitute|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_ProductSubstitute_productid|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_price_levels"></a> product_price_levels

Same as the [product_price_levels](productpricelevel.md#BKMK_product_price_levels) many-to-one relationship for the [productpricelevel](productpricelevel.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|productpricelevel|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|product_price_levels|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_opportunity_products"></a> opportunity_products

**Added by**: Sales Solution

Same as the [opportunity_products](opportunityproduct.md#BKMK_opportunity_products) many-to-one relationship for the [opportunityproduct](opportunityproduct.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|opportunityproduct|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|opportunity_products|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Restrict<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_invoice_details"></a> product_invoice_details

**Added by**: Sales Solution

Same as the [product_invoice_details](invoicedetail.md#BKMK_product_invoice_details) many-to-one relationship for the [invoicedetail](invoicedetail.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|invoicedetail|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_invoice_details|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Restrict<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_order_details"></a> product_order_details

**Added by**: Sales Solution

Same as the [product_order_details](salesorderdetail.md#BKMK_product_order_details) many-to-one relationship for the [salesorderdetail](salesorderdetail.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|salesorderdetail|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_order_details|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Restrict<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_product_quote_details"></a> product_quote_details

**Added by**: Sales Solution

Same as the [product_quote_details](quotedetail.md#BKMK_product_quote_details) many-to-one relationship for the [quotedetail](quotedetail.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|quotedetail|
|ReferencingAttribute|productid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|product_quote_details|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Restrict<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related table. Listed by **SchemaName**.

- [price_level_products](#BKMK_price_level_products)
- [product_parent_product](#BKMK_product_parent_product)
- [unit_of_measurement_products](#BKMK_unit_of_measurement_products)
- [unit_of_measurement_schedule_products](#BKMK_unit_of_measurement_schedule_products)


### <a name="BKMK_price_level_products"></a> price_level_products

See the [price_level_products](pricelevel.md#BKMK_price_level_products) one-to-many relationship for the [pricelevel](pricelevel.md) table/entity.

### <a name="BKMK_product_parent_product"></a> product_parent_product

See the [product_parent_product](product.md#BKMK_product_parent_product) one-to-many relationship for the [product](product.md) table/entity.

### <a name="BKMK_unit_of_measurement_products"></a> unit_of_measurement_products

See the [unit_of_measurement_products](uom.md#BKMK_unit_of_measurement_products) one-to-many relationship for the [uom](uom.md) table/entity.

### <a name="BKMK_unit_of_measurement_schedule_products"></a> unit_of_measurement_schedule_products

See the [unit_of_measurement_schedule_products](uomschedule.md#BKMK_unit_of_measurement_schedule_products) one-to-many relationship for the [uomschedule](uomschedule.md) table/entity.
<a name="manytomany"></a>

## Many-To-Many Relationships

Relationship details provided where the Product table is the first table in the relationship. Listed by **SchemaName**.

- [campaignproduct_association](#BKMK_campaignproduct_association)
- [leadproduct_association](#BKMK_leadproduct_association)
- [productsalesliterature_association](#BKMK_productsalesliterature_association)
- [competitorproduct_association](#BKMK_competitorproduct_association)


### <a name="BKMK_campaignproduct_association"></a> campaignproduct_association

See the [campaignproduct_association](campaign.md#BKMK_campaignproduct_association) many-to-many relationship for the [campaign](campaign.md) table/entity.

### <a name="BKMK_leadproduct_association"></a> leadproduct_association

See the [leadproduct_association](lead.md#BKMK_leadproduct_association) many-to-many relationship for the [lead](lead.md) table/entity.

### <a name="BKMK_productsalesliterature_association"></a> productsalesliterature_association

IntersectEntityName: productsalesliterature<br />
#### Table 1

|Property|Value|
|--------|-----|
|IntersectAttribute|productid|
|IsCustomizable|False|
|LogicalName|product|
|NavigationPropertyName|productsalesliterature_association|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |

#### Table 2

|Property|Value|
|--------|-----|
|LogicalName|salesliterature|
|IntersectAttribute|salesliteratureid|
|NavigationPropertyName|productsalesliterature_association|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |


### <a name="BKMK_competitorproduct_association"></a> competitorproduct_association

See the [competitorproduct_association](competitor.md#BKMK_competitorproduct_association) many-to-many relationship for the [competitor](competitor.md) table/entity.

### See also

[About the table reference](../about-entity-reference.md)<br />
[Web API Reference](/power-apps/developer/data-platform/webapi/reference/entitytypes)<br />
