BuddypressAddCustomField
========================

you can expand BuddyPress group pages with additional data.

### Usage

PHP
```PHP
  // write this in functions.php
  require_once "BP_group_extra_field.class.php";
```

Dislay Meta field
```PHP
   echo groups_get_groupmeta( bp_get_group_id(), 'field name');
```
