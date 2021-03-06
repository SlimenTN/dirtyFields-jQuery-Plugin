## BASICS
**********

dirtyFields is a jQuery plugin that makes a user aware of which form elements have been updated on an HTML form and can reset the form values back to their previous state.

The main website for the plugin (which includes documentation, demos, and a download file) is currently at:

https://bcswartz.github.io/dirtyFields-jQuery-Plugin/


## CHANGE LOG
*******************

### Version 1.2 (January 2013):
---

* Added two new public functions:
  * getDirtyFieldNames() returns an array of all currently dirty fields
  * updateFormState() checks the clean/dirty state of all form fields in the specified container.
		
* Made two changes to how the CSS class denoting a dirty/changed form is applied:
  * Added a new configuration option ("self") to apply the class to the actual form element.
  * Split the single option for applying a style to a changed text input and select drop-down into two separate options for granular control (if you used the textboxSelectContext option with a previous version of the plugin, you will need to update your code).
		
* Added three new configuration options to control plugin behavior:
  * The denoteDirtyFields option controls whether or not the dirty CSS class is applied to the form elements that are dirty/changed.
  * The exclusionClass option specifies the name of the CSS class that, when applied to a form field, will exclude that field from being processed by the plugin.
  * The ignoreCaseClass option specifies the name of the CSS class tha, when applied to a form field, will instruct the plugin to do a case-insensitive evaluation of the current and original states of the field.


All version 1.2 changes were implemented in response to code suggestions made a team of developers: Pawar Aishwarya, Gadkari Amit, and Naik Pankaj. 
		

### Version 1.1 (November 2011):
---

* Updated the plugin to be compatible with update to attr() function introduced in  jQuery 1.6.
