---
type: eventType
---
---
##### shortDescription
Fires after a menu item is rendered.

##### param(e): object
Provides function parameters.

##### field(e.component): object
Provides access to the widget's instance.

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

---
Instead, you can use the [onMenuItemRendered](/api-reference/10%20UI%20Widgets/dxSlideOut/1%20Configuration/onMenuItemRendered.md '/Documentation/ApiReference/UI_Widgets/dxSlideOut/Configuration/#onMenuItemRendered') option to handle the event.

#####See Also#####
#include common-link-handleevents