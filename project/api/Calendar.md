[comment]: # (Name:Calendar)
[comment]: # (Name:Microsoft.ProjectServer.Calendar)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>Calendar class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a Project service calendar.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class Calendar 
```
### JSOM

```javascript
PS.Calendar
```
### REST Interface

Supported.

```
PS.Calendar

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Calendars('{calendarid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="BaseCalendarExceptions"></a>BaseCalendarExceptions|&#x2713;|&#x2713;|&#x2713;|[CalendarExceptionCollection](CalendarExceptionCollection.md)|Gets the collection of exceptions to base calendars.|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the calendar was created.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the calendar.|
|<a name="IsStandardCalendar"></a>IsStandardCalendar|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the calendar is Gregorian.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the calendar was modified.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the calendar.|
|<a name="OriginalId"></a>OriginalId|||&#x2713;|Guid|The Id of the calendar that this calendar was copied from.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[CopyTo(String name)](#CopyTo_String_name_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Makes a copy of the calendar and gives the copy a new name.|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the calendar object.|

<br/>
#### Method Details

#### <a name="CopyTo_String_name_"></a>CopyTo(String name)

Makes a copy of the calendar and gives the copy a new name.

##### Syntax

```
Calendar CopyTo(String name)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|name| String | The name of the new calendar.


##### Return Value

[Calendar](Calendar.md)

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the calendar object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[CalendarCollection](CalendarCollection.md)<br/>
[CalendarCreationInformation](CalendarCreationInformation.md)<br/>
[CalendarException](CalendarException.md)<br/>
[DraftProject](DraftProject.md)<br/>
[DraftTask](DraftTask.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
