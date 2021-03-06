[comment]: # (Name:StatusAssignmentCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.StatusAssignmentCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusAssignmentCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [StatusAssignment](StatusAssignment.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusAssignmentCreationInformation 
```

### JSOM

```javascript
PS.StatusAssignmentCreationInformation
```
### REST Interface

Supported.

```
PS.StatusAssignmentCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Comment':'value', 
		'Id':'value', 
		'ProjectId':'value', 
		'Task':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Comment"></a>Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the comment for the status submission.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the status assignment.|
|<a name="ProjectId"></a>ProjectId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project that contains the status assignment.|
|<a name="Task"></a>Task|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StatusTaskCreationInformation](StatusTaskCreationInformation.md)|Gets or sets the task parameters for the status assignment.|

## <a name="seeAlso"></a>See Also

[StatusAssignment](StatusAssignment.md)<br/>
[StatusAssignmentCollection](StatusAssignmentCollection.md)<br/>
