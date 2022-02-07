# Notifications

## Live Regions

Live regions will announce themselves even then the tab is not active
+ Is this true? <-- will need to test


## Location
Toasts should inject into the DOM at a consistent location
+ Adding toast in multiple locations (top left -vs- bottom right) breaks the WCAG consistently rule
  + Familiarity
  + [See here for more details](https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-functionality.html)


## Focus / Priority



Toasts outside of focus traps
+ Like modals
+ Put right at the top or the bottom of the DOM tree



Time to keep open
+ Cognitive issues take long
+ might not be in view when zoomed



aria-live="polite" role="status"
aria-live="assertive" role="alert"




store list of previos toast notificaitons




interaction
+ Focus traps
+ getting to Interaction
+ where to focus back to after clicking CTA?
+ Live region, reading out CTA with no context it is interactable


Adjusting time
+ https://www.w3.org/WAI/WCAG21/Understanding/timing-adjustable.html