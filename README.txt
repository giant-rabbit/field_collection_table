-- SUMMARY --

The Field Collection Table module adds a widget and field formatter
for Field Collection Items to display them in a table.

 * For a full description of the module, visit the project page:
   https://drupal.org/project/field_collection_table

 * To submit bug reports and feature suggestions, or to track changes:
   https://drupal.org/project/issues/field_collection_table


-- REQUIREMENTS --

Field collection (https://drupal.org/project/field_collection)


-- INSTALLATION --

Install as you would normally install a contributed Drupal module. Visit:
https://drupal.org/documentation/install/modules-themes/modules-7
for further information.


-- CONFIGURATION --

* The module provides a field formatter and an input widget for field collection
  items. Configuration is found here.


-- CUSTOMIZATION --

* To display field labels inline (ex. small screen and the table breaks),
  the data-title attribute can be used in a pseudo element.

  For example:
  @media (max-width: 700px) {
      .field-collection-table-view td:before {
          content: attr(data-title)": ";
      }
  }

  For compatibility, see: http://caniuse.com/#feat=css-gencontent


-- CONTACT --

Current maintainers:
* Kevin Einarsson (kevineinarsson) - http://drupal.org/u/kevineinarsson
* Kristoffer Wiklund (kristofferwiklund) - http://drupal.org/u/kristofferwiklund
