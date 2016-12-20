[comment]: # (Name:WorkflowActivities)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# WorkflowActivities

Contains methods that encapsulate Project Server workflow activities and methods, for use with version 4 of Windows Workflow Foundation (WF4).



## Syntax

### CSOM

```C#
Class WorkflowActivities 
```
### JSOM

```
PS.WorkflowActivities
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[CheckInWithJobId(Guid projId, Guid jobId, Boolean force)](#CheckInWithJobId_Guid_projId,_Guid_jobId,_Boolean_force_)|||&#x2713;|void||
|[CreateProjectFromListItem(Guid webId, Guid listId, Integer itemId, Guid eptId)](#CreateProjectFromListItem_Guid_webId,_Guid_listId,_Integer_itemId,_Guid_eptId_)|&#x2713;|&#x2713;|&#x2713;|Guid|Creates a project from a SharePoint list item, where the project uses the specified enterprise project type (EPT).|
|[EnterProjectStage(Guid projectId, Guid stageId)](#EnterProjectStage_Guid_projectId,_Guid_stageId_)|&#x2713;|&#x2713;|&#x2713;|void|Attempts to enter the specified workflow stage for the project.|
|[LeaveProjectStage(Guid projectId)](#LeaveProjectStage_Guid_projectId_)|&#x2713;|&#x2713;|&#x2713;|void|Sets the project complete and leaves the current workflow stage.|
|[PublishSummaryWithJobId(Guid projId, Guid jobId)](#PublishSummaryWithJobId_Guid_projId,_Guid_jobId_)|||&#x2713;|void||
|[PublishWithJobId(Guid projectId, Guid jobId)](#PublishWithJobId_Guid_projectId,_Guid_jobId_)|||&#x2713;|void||
|[ReadBooleanProperty(Guid projectId, String propertyId)](#ReadBooleanProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Reads the value of the specified project property by using the SharePoint SPFieldType.Boolean type.|
|[ReadCurrencyProperty(Guid projectId, String propertyId)](#ReadCurrencyProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|Double|Reads the value of of the specified project property by using the SharePoint SPFieldType.Currency type.|
|[ReadDateTimeProperty(Guid projectId, String propertyId)](#ReadDateTimeProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|DateTime|Reads the value of of the specified project property by using the SharePoint SPFieldType.DateTime type.|
|[ReadGuidProperty(Guid projectId, String propertyId)](#ReadGuidProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|Guid|Reads the value of of the specified project property by using the SharePoint SPFieldType.Guid type.|
|[ReadIntegerProperty(Guid projectId, String propertyId)](#ReadIntegerProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|Integer|Reads the value of of the specified project property by using the SharePoint SPFieldType.Integer type.|
|[ReadNumberProperty(Guid projectId, String propertyId)](#ReadNumberProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|Double|Reads the value of of the specified project property by using the SharePoint SPFieldType.Number type.|
|[ReadProjectProperty(Guid projectId, String propertyId)](#ReadProjectProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|String|Reads the String value of of the specified project property.|
|[ReadTextProperty(Guid projectId, String propertyId)](#ReadTextProperty_Guid_projectId,_String_propertyId_)|&#x2713;|&#x2713;|&#x2713;|String|Reads the value of of the specified project property by using the SharePoint SPFieldType.Text type.|
|[ReadyToLeaveProjectStage(Guid projectId)](#ReadyToLeaveProjectStage_Guid_projectId_)|&#x2713;|&#x2713;|&#x2713;|[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)|Checks whether the current workflow stage requirements are satisfied.|
|[UpdateBooleanProperty(Guid projectId, String propertyId, Boolean value)](#UpdateBooleanProperty_Guid_projectId,_String_propertyId,_Boolean_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of the specified project property by using the SharePoint SPFieldType.Boolean type.|
|[UpdateCurrencyProperty(Guid projectId, String propertyId, Double value)](#UpdateCurrencyProperty_Guid_projectId,_String_propertyId,_Double_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.Currency type.|
|[UpdateDateTimeProperty(Guid projectId, String propertyId, DateTime value)](#UpdateDateTimeProperty_Guid_projectId,_String_propertyId,_DateTime_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.DateTime type.|
|[UpdateGuidProperty(Guid projectId, String propertyId, Guid value)](#UpdateGuidProperty_Guid_projectId,_String_propertyId,_Guid_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.Guid type.|
|[UpdateIdeaListItemStatus(Guid projectId, String status)](#UpdateIdeaListItemStatus_Guid_projectId,_String_status_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the  **Status** column in the SharePoint project idea list with a status string.|
|[UpdateIntegerProperty(Guid projectId, String propertyId, Integer value)](#UpdateIntegerProperty_Guid_projectId,_String_propertyId,_Integer_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.Integer type.|
|[UpdateNumberProperty(Guid projectId, String propertyId, Double value)](#UpdateNumberProperty_Guid_projectId,_String_propertyId,_Double_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.Number type.|
|[UpdateProjectStageStatus(Guid projectId, Guid stageId, String statusInformation, [UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md) stageStatusValue, Boolean append)](#UpdateProjectStageStatus_Guid_projectId,_Guid_stageId,_String_statusInformation,_[UpdateProjectStageStatusFieldValue]_UpdateProjectStageStatusFieldValue.md__stageStatusValue,_Boolean_append_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the status value and the status information for a Project Server workflow stage.|
|[UpdateTextProperty(Guid projectId, String propertyId, String value)](#UpdateTextProperty_Guid_projectId,_String_propertyId,_String_value_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the value of of the specified project property by using the SharePoint SPFieldType.Text type.|



## Method Details


### <a id="CheckInWithJobId_Guid_projId,_Guid_jobId,_Boolean_force_"></a>CheckInWithJobId(Guid projId, Guid jobId, Boolean force)
 


#### Syntax

```
void CheckInWithJobId(Guid projId, Guid jobId, Boolean force)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projId| Guid | 
|jobId| Guid | 
|force| Boolean | 


#### Return Value

void

### <a id="CreateProjectFromListItem_Guid_webId,_Guid_listId,_Integer_itemId,_Guid_eptId_"></a>CreateProjectFromListItem(Guid webId, Guid listId, Integer itemId, Guid eptId)
 
Creates a project from a SharePoint list item, where the project uses the specified enterprise project type (EPT).

#### Syntax

```
Guid CreateProjectFromListItem(Guid webId, Guid listId, Int32 itemId, Guid eptId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|webId| Guid |  that contains the list.
|listId| Guid |  that contains the project item.
|itemId| Integer |  within the list.
|eptId| Guid | The GUID of the EPT.


#### Return Value

Guid

### <a id="EnterProjectStage_Guid_projectId,_Guid_stageId_"></a>EnterProjectStage(Guid projectId, Guid stageId)
 
Attempts to enter the specified workflow stage for the project.

#### Syntax

```
void EnterProjectStage(Guid projectId, Guid stageId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|stageId| Guid | The GUID of the workflow stage.


#### Return Value

void

### <a id="LeaveProjectStage_Guid_projectId_"></a>LeaveProjectStage(Guid projectId)
 
Sets the project complete and leaves the current workflow stage.

#### Syntax

```
void LeaveProjectStage(Guid projectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.


#### Return Value

void

### <a id="PublishSummaryWithJobId_Guid_projId,_Guid_jobId_"></a>PublishSummaryWithJobId(Guid projId, Guid jobId)
 


#### Syntax

```
void PublishSummaryWithJobId(Guid projId, Guid jobId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projId| Guid | 
|jobId| Guid | 


#### Return Value

void

### <a id="PublishWithJobId_Guid_projectId,_Guid_jobId_"></a>PublishWithJobId(Guid projectId, Guid jobId)
 


#### Syntax

```
void PublishWithJobId(Guid projectId, Guid jobId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | 
|jobId| Guid | 


#### Return Value

void

### <a id="ReadBooleanProperty_Guid_projectId,_String_propertyId_"></a>ReadBooleanProperty(Guid projectId, String propertyId)
 
Reads the value of the specified project property by using the SharePoint SPFieldType.Boolean type.

#### Syntax

```
Boolean ReadBooleanProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

Boolean

### <a id="ReadCurrencyProperty_Guid_projectId,_String_propertyId_"></a>ReadCurrencyProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.Currency type.

#### Syntax

```
Double ReadCurrencyProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

Double

### <a id="ReadDateTimeProperty_Guid_projectId,_String_propertyId_"></a>ReadDateTimeProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.DateTime type.

#### Syntax

```
DateTime ReadDateTimeProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

DateTime

### <a id="ReadGuidProperty_Guid_projectId,_String_propertyId_"></a>ReadGuidProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.Guid type.

#### Syntax

```
Guid ReadGuidProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

Guid

### <a id="ReadIntegerProperty_Guid_projectId,_String_propertyId_"></a>ReadIntegerProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.Integer type.

#### Syntax

```
Integer ReadIntegerProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

Integer

### <a id="ReadNumberProperty_Guid_projectId,_String_propertyId_"></a>ReadNumberProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.Number type.

#### Syntax

```
Double ReadNumberProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

Double

### <a id="ReadProjectProperty_Guid_projectId,_String_propertyId_"></a>ReadProjectProperty(Guid projectId, String propertyId)
 
Reads the String value of of the specified project property.

#### Syntax

```
String ReadProjectProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

String

### <a id="ReadTextProperty_Guid_projectId,_String_propertyId_"></a>ReadTextProperty(Guid projectId, String propertyId)
 
Reads the value of of the specified project property by using the SharePoint SPFieldType.Text type.

#### Syntax

```
String ReadTextProperty(Guid projectId, String propertyId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.


#### Return Value

String

### <a id="ReadyToLeaveProjectStage_Guid_projectId_"></a>ReadyToLeaveProjectStage(Guid projectId)
 
Checks whether the current workflow stage requirements are satisfied.

#### Syntax

```
ReadyToLeaveProjectStageValue ReadyToLeaveProjectStage(Guid projectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.


#### Return Value

[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)

### <a id="UpdateBooleanProperty_Guid_projectId,_String_propertyId,_Boolean_value_"></a>UpdateBooleanProperty(Guid projectId, String propertyId, Boolean value)
 
Updates the value of the specified project property by using the SharePoint SPFieldType.Boolean type.

#### Syntax

```
void UpdateBooleanProperty(Guid projectId, String propertyId, Boolean value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| Boolean | The Boolean value to update.


#### Return Value

void

### <a id="UpdateCurrencyProperty_Guid_projectId,_String_propertyId,_Double_value_"></a>UpdateCurrencyProperty(Guid projectId, String propertyId, Double value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.Currency type.

#### Syntax

```
void UpdateCurrencyProperty(Guid projectId, String propertyId, Double value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| Double | The Currency value to update.


#### Return Value

void

### <a id="UpdateDateTimeProperty_Guid_projectId,_String_propertyId,_DateTime_value_"></a>UpdateDateTimeProperty(Guid projectId, String propertyId, DateTime value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.DateTime type.

#### Syntax

```
void UpdateDateTimeProperty(Guid projectId, String propertyId, DateTime value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| DateTime | The DateTime value to update.


#### Return Value

void

### <a id="UpdateGuidProperty_Guid_projectId,_String_propertyId,_Guid_value_"></a>UpdateGuidProperty(Guid projectId, String propertyId, Guid value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.Guid type.

#### Syntax

```
void UpdateGuidProperty(Guid projectId, String propertyId, Guid value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| Guid | The Guid value to update.


#### Return Value

void

### <a id="UpdateIdeaListItemStatus_Guid_projectId,_String_status_"></a>UpdateIdeaListItemStatus(Guid projectId, String status)
 
Updates the  **Status** column in the SharePoint project idea list with a status string.

#### Syntax

```
void UpdateIdeaListItemStatus(Guid projectId, String status)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|status| String | The status message to write to the idea status column.


#### Return Value

void

### <a id="UpdateIntegerProperty_Guid_projectId,_String_propertyId,_Integer_value_"></a>UpdateIntegerProperty(Guid projectId, String propertyId, Integer value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.Integer type.

#### Syntax

```
void UpdateIntegerProperty(Guid projectId, String propertyId, Int32 value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| Integer | The Integer value to update.


#### Return Value

void

### <a id="UpdateNumberProperty_Guid_projectId,_String_propertyId,_Double_value_"></a>UpdateNumberProperty(Guid projectId, String propertyId, Double value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.Number type.

#### Syntax

```
void UpdateNumberProperty(Guid projectId, String propertyId, Double value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| Double | The Number value to update.


#### Return Value

void

### <a id="UpdateProjectStageStatus_Guid_projectId,_Guid_stageId,_String_statusInformation,_[UpdateProjectStageStatusFieldValue]_UpdateProjectStageStatusFieldValue.md__stageStatusValue,_Boolean_append_"></a>UpdateProjectStageStatus(Guid projectId, Guid stageId, String statusInformation, [UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md) stageStatusValue, Boolean append)
 
Updates the status value and the status information for a Project Server workflow stage.

#### Syntax

```
void UpdateProjectStageStatus(Guid projectId, Guid stageId, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|stageId| Guid | The GUID of the workflow stage.
|statusInformation| String | The status information value to update.
|stageStatusValue| [UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md) |  enumeration.
|append| Boolean | True if the information text is appended;false if the information text is replaced.


#### Return Value

void

### <a id="UpdateTextProperty_Guid_projectId,_String_propertyId,_String_value_"></a>UpdateTextProperty(Guid projectId, String propertyId, String value)
 
Updates the value of of the specified project property by using the SharePoint SPFieldType.Text type.

#### Syntax

```
void UpdateTextProperty(Guid projectId, String propertyId, String value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|projectId| Guid | The GUID of the project.
|propertyId| String | The GUID of the property to read.
|value| String | The Text value to update.


#### Return Value

void


## See Also