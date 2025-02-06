## 1.5 Create interactive controls/widgets based on a11y best practices

### General
- [ ] Understand native HTML widgets should be used instead of custom WAI-ARIA widgets whenever possible
- [ ] Become familiar with the keyboard interaction model for ARIA custom widgets
  - In many widgets, the keyboard interaction model is to tab to the widget as a
whole, or the active/selected element within the widget, then use the arrow keys
to navigate within the widget. The tab key is generally not used for navigation
within the widget. Other keystrokes may be recommended for certain widgets.
- [ ] Understand ARIA roles, states, and properties that may be used to communicate to a screenreader with what is occuring in the interface (for complex web applications or dynamic content)
- [ ] Read through [Code Library of a11y Examples: ARIA widgets (Deque University)](https://dequeuniversity.com/library/aria/)

### Roles
- [ ] When a custom role is assigned to an element, the custom role completely overrides the native role
  -  For example, `<li role=”button”>` will be treated as a
button by the accessibility API, not like a list item.
- [ ] Understand when creating ARIA widgets, some roles have required parent/child roles, and some roles have required attributes (semantic structure)
- [ ] Understand roles to describe the type of widget presented - e.g. "menu", "treeitem", "slider", "progressbar"
- [ ] Understand roles to describe structure of the web page - e.g. headings, regions, tables 
- [ ] Understand that the `application` role should be used sparingly, if at all, since it overrides many AT keystrokes 
- [ ] Go through [WAS Certification Prep - Role Requirements sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=2129291334#gid=2129291334)

### Properties
- [ ] Understand properties to describe widget state - e.g. "checked" for checkbox, "expanded" for menu
- [ ] Understand properties to define live regions that are likely to get updates (e.g. stock quotes), as well as an interruption policy for those updates - e.g. criticals updates in an alert dialog box, incidental updates within the page
