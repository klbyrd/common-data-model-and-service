---
title: ProgramVersion - Common Data Model | Microsoft Docs
description: The master list of all program versions defined by the institution.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Program Version

The master list of all program versions defined by the institution.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/ProgramVersion.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/education/higherEducation/ProgramVersion  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[programVersionId](#programVersionId)|Unique identifier for entity instances|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[stateCode](#stateCode)|Status of the Program Version|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[stateCode_display](#stateCode_display)||<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[statusCode](#statusCode)|Reason for the status of the Program Version|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[statusCode_display](#statusCode_display)||<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[name](#name)|Program Version Name|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[code](#code)|Abbreviated code for the program version.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[externalIdentifier](#externalIdentifier)|External Identifier|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[externalSourceSystem](#externalSourceSystem)|External Source System|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[externalSourceSystem_display](#externalSourceSystem_display)||<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[programId](#programId)|Lookup to the program.|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|
|[programLevelId](#programLevelId)|Link to Program Level entity|<a href="ProgramVersion.md" target="_blank">higherEducation/ProgramVersion</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#programVersionId name="programVersionId">programVersionId</a>

Unique identifier for entity instances  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Program Version</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>mshied_programversionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Program Version  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Program Version</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Program Version  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Program Version</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Program Version Name  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Program Version Name</td></tr><tr><td>description</td><td>Program Version Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_name</td></tr></table>

### <a href=#code name="code">code</a>

Abbreviated code for the program version.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Abbreviated code for the program version.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_code</td></tr></table>

### <a href=#externalIdentifier name="externalIdentifier">externalIdentifier</a>

External Identifier  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Identifier</td></tr><tr><td>description</td><td>External Identifier</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_externalidentifier</td></tr></table>

### <a href=#externalSourceSystem name="externalSourceSystem">externalSourceSystem</a>

External Source System  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Source System</td></tr><tr><td>description</td><td>External Source System</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_externalsourcesystem</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>System 1</td><td>494280000</td></tr><tr><td>en</td><td>System 2</td><td>494280001</td></tr><tr><td>en</td><td>System 3</td><td>494280002</td></tr></table></td></tr></table>

### <a href=#externalSourceSystem_display name="externalSourceSystem_display">externalSourceSystem_display</a>

First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#programId name="programId">programId</a>

Lookup to the program.  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Program</td></tr><tr><td>description</td><td>Lookup to the program.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_programid</td></tr></table>

### <a href=#programLevelId name="programLevelId">programLevelId</a>

Link to Program Level entity  
First included in: higherEducation/ProgramVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Program Level</td></tr><tr><td>description</td><td>Link to Program Level entity</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_programlevelid</td></tr></table>