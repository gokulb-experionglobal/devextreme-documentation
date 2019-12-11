---
type: function(itemInfo)
---
---
##### notUsedInTheme

##### shortDescription
Specifies text for legend items.

##### param(itemInfo): Object
Information on a legend item.

##### field(itemInfo.start): Number
The start value of the group indicated by the legend item.

##### field(itemInfo.end): Number
The end value of the group indicated by the legend item.

##### field(itemInfo.index): Number
The index of the group indicated by the legend item.

##### field(itemInfo.color): String|undefined
The color of the legend item. This field is **undefined** if the [source](/api-reference/20%20Data%20Visualization%20Widgets/dxVectorMap/1%20Configuration/legends/source '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/legends/#source') is *'markerSizeGroups'*.

##### field(itemInfo.size): Number|undefined
The diameter of the legend item in pixels. This field is **undefined** if the [source](/api-reference/20%20Data%20Visualization%20Widgets/dxVectorMap/1%20Configuration/legends/source '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/legends/#source') is *'areaColorGroups'* or *'markerColorGroups'*.

##### return: String
Text for the legend item.

---
This option accepts a function that returns the text for a legend item. When implementing this function, you can access useful data on the legend item using the function's argument.