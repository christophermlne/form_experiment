form_experiment
===============

learning to code a drupal module

update:
- used hook_schema in the .install file to define a table that is created automatically when the module is enabled, and destroyed when the module is uninstalled
- disabling the module will leave the data intact. uninstalling will destroy it.
