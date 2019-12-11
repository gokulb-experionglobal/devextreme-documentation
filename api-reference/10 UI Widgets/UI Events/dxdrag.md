---
module: events/drag
type: eventType
---
---
##### shortDescription
Raised when the drag gesture has been performed.

##### param(event): jQuery.event
The standard jQuery event argument. The following fields are added to existing fields of this argument object. For the information on event handler arguments, refer to the [UI Events introduction](/api-reference/10%20UI%20Widgets/UI%20Events '/Documentation/ApiReference/UI_Widgets/UI_Events/').

##### field(event.offset): number
Indicates which distance has been passed during the dragging gesture, measured as a ratio to the target element's width.

##### field(event.cancel): boolean
Indicates whether to prevent the drag gesture. Set this field to true to cancel the gesture.

---