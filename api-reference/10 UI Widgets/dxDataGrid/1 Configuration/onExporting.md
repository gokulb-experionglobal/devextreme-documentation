---
EventForAction: ..\4 Events\exporting.md
default: null
type: function(e)
---
---
##### shortDescription
A handler for the [exporting](/api-reference/10%20UI%20Widgets/dxDataGrid/4%20Events/exporting.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Events/#exporting') event.

##### param(e): Object
Information about the event.

##### field(e.component): Object
The widget [instance](/api-reference/10%20UI%20Widgets/Component/3%20Methods/instance().md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Methods/#instance').

##### field(e.element): jQuery
The widget's container.

##### field(e.model): Object
Data that is available for binding against the element. Available only in the Knockout approach.

##### field(e.fileName): String
The name of the file to which grid data is about to be exported.

##### field(e.cancel): Boolean
Indicates whether or not to cancel exporting.

---
Assign a function to perform a custom action before exporting grid data.

#####See Also#####
- [Client-Side Exporting - Events](/concepts/05%20Widgets/DataGrid/70%20Client-Side%20Exporting/10%20Events.md '/Documentation/Guide/Widgets/DataGrid/Client-Side_Exporting/#Events')
- [export](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/export '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/export/') - configures client-side exporting.
- [customizeExportData](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/customizeExportData.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#customizeExportData') - customizes grid columns and data before exporting.
- [onExported](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/onExported.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onExported') - allows you to notify an end user when exporting is completed.
- [onFileSaving](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/onFileSaving.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onFileSaving') - allows you to access exported data and/or prevent it from being saved into a file on the user's local storage.