# Chosen

Fork of http://harvesthq.github.io/chosen/, includes support for dropdowns with checkboxes, and deselecting items in the dropdown without closing the it.

- Currently only jQuery support: 1.4+

For **documentation**, usage, and examples, see:
http://harvesthq.github.io/chosen/

Added following features in this fork:

- Checkboxes in dropdown
- Choice to not hide dropdown contents when selecting/deselecting
- Support deselecting items through dropdown

### Package managers

Chosen-noterik is available through [npm](https://www.npmjs.com).

To install with npm:

```
npm install chosen-noterik
```

### Usage

Example of using newly added features:
```
jQuery('.chosen').chosen({
  show_checkboxes: true, //Will show checkboxes in dropdown
  hide_results_on_select: false, //Will keep the dropdown open when selecting an option
  hide_results_on_deselect: false, //Will keep the dropdown open when deselecting an option
  allow_dropdown_item_deselect: true //Allows support for deselecting items through dropdown
});
```
