---
type: eventType
---
---
##### notUsedInTheme

##### shortDescription
Fires when the selection state of a node has been changed.

##### param(e): object
Information about the event.

##### field(e.component): object
The widget's instance.

##### field(e.element): object
The widget's container.

##### field(e.node): dxtreemapnode
The node whose selection state has been changed.

---
When implementing a handling function, use the object passed to it as its parameter. Among the fields of this object, you can find the node whose selection state has been changed.

To identify whether the node was selected or deselected, call its [isSelected()](/api-reference/20%20Data%20Visualization%20Widgets/dxTreeMap/6%20Node/3%20Methods/isSelected().md '/Documentation/ApiReference/Data_Visualization_Widgets/dxTreeMap/Node/Methods/#isSelected') method. To identify whether the node is a single tile or a group of tiles, call its [isLeaf()](/api-reference/20%20Data%20Visualization%20Widgets/dxTreeMap/6%20Node/3%20Methods/isLeaf().md '/Documentation/ApiReference/Data_Visualization_Widgets/dxTreeMap/Node/Methods/#isLeaf') method. Other accessible fields and methods of a node are described in the [Node](/api-reference/20%20Data%20Visualization%20Widgets/dxTreeMap/6%20Node '/Documentation/ApiReference/Data_Visualization_Widgets/dxTreeMap/Node/') section.

#####See Also#####
#include common-link-handleevents