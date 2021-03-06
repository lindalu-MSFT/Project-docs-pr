[comment]: # (Name:PublishedTaskCollection)
[comment]: # (Name:Microsoft.ProjectServer.PublishedTaskCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTaskCollection class

inherits members from [ClientObjectCollection<PublishedTask>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of tasks in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PublishedTaskCollection 
```

### JSOM

```javascript
PS.PublishedTaskCollection
```

### REST Interface

Supported.

```
PS.PublishedTaskCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/Tasks
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedTaskId}&#39;](#&#39;{PublishedTaskId}&#39;)|||&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the specified PublishedTaskId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the Id value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedTaskId}&#39;"></a>&#39;{PublishedTaskId}&#39;

Gets a [PublishedTask](PublishedTask.md) from the collection with the specified PublishedTaskId.

##### Syntax

```
PublishedTask http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/Tasks('{PublishedTaskId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedTaskId|String|the id of the PublishedTask|

##### Return Value

[PublishedTask](PublishedTask.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [PublishedTask](PublishedTask.md) from the collection with the Guid value.

##### Syntax

```
PublishedTask GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedTask](PublishedTask.md)|

##### Return Value

[PublishedTask](PublishedTask.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [PublishedTask](PublishedTask.md) from the collection with the Id value.

##### Syntax

```
PublishedTask GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedTask](PublishedTask.md).|

##### Return Value
[PublishedTask](PublishedTask.md)<br />
The task in the published project.

## <a name="seeAlso"></a>See Also

[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
