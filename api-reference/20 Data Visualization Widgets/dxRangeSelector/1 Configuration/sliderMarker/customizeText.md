---
type: function(scaleValue)
---
---
##### notUsedInTheme

##### shortDescription
Specifies a callback function that returns the text to be displayed by slider markers.

##### param(scaleValue): Object
Defines a scale value.

##### field(scaleValue.value): Date|Number
Specifies the scale value that is currently selected.

##### field(scaleValue.valueText): String
Specifies the currently selected scale value with applied [formatting](/api-reference/20%20Data%20Visualization%20Widgets/dxRangeSelector/1%20Configuration/sliderMarker/format.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxRangeSelector/Configuration/sliderMarker#format').

##### return: String
The text to be displayed by a slider marker.

---
When implementing a callback function for this property, use the value displayed in a slider marker. This value can be accessed using the fields of the object that is passed as the function's parameter. Alternatively, you can use the **this** object within the function. This object has the same structure as the object passed as a parameter.

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/Range_Selector/CustomFormatting/jQuery/Light/"
}