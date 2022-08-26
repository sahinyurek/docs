---
hide:
  - toc
---

# Objects lists

<img src="../images/cases_list.png" alt="objects list" width="1500" height="1000"/>

In TheHive, most of the objects are displayed as lists: `Cases`, `Alerts`, `Observables`, `Tasks`, `Users` ...

Every list benefit of the same capabilities, and some has specific features.


## Switches

<img src="../images/list_switches.png" alt="objects list" width="1500" height="1000"/>

Switches button (surrended in red on the top-right corner in the screenshot above) allows an analyst to:

1. Activate auto-refresh of the list
2. Open list statistics pane
3. Open filter bar*. Every objects fields (and meta-fields) are filterable.

!!! note "Pro tip"
    *You can use Quick Filters to apply predefined filters to the list

## Views

<img src="../images/views_1.png" alt="objects list" width="1500" height="1000"/>

An analyst can save a filter set he defined. This filter set is named a `view`. These `views` are saved at the `user` level.

Click on the "default" button (surrounded by red in the above screenshot) to open the `views` drop-down menu.

### Save a view

Once the desired filter(s) applied on the list, click on the "default" button (surrended in red in the above screenshot) to open the `views` drop-down menu. 

Click on "Save view as", then a drawer will ask you to provide a name for this view and confirm your choice.

### Open a view

Open the `view`drop-down menu, then click on a previously saved `view`. The predefined filters saved in the `view` will be applied to the list.


### Manage views

An analyst can delete undesired `views` she/he previously saved. 

Open the `view`drop-down menu, then click on `Manage views`. 

A drawer appear with the list of saved views. Use the actions button to delete the undesired `view`. 

<img src="../images/manage_view.png" alt="objects list" width="1500" height="1000"/>

# Columns

Informations displayed by list columns depends on the object type.

<img src="../images/columns.png" alt="objects list" width="1500" height="1000"/>

List columns has various features:

1. Select listed objects: allows analyst to select all* listed objects to run bulk actions
2. Sort listed objects: clicking the double arrows allows analyst to sort (ascending or descending) the listed objects.
3. Hide/Display information: clicking the three dots allows analyst to hide or display specific information (eg: `customFields`, number of `ttps` or `created date`)

*Individual boxes exists allowing you to cherry pick objects from the list.

# Actions

List of objects allows to run actions. Available actions differs regarding the type of object listed (`Cases`, `Observables`, `Tasks`, ...)

## Bulk actions

Bulk mode allows to run actions to one or multiple `Cases`. 

Check one or multiple `Cases` box(es) to make the bulk action bar appear on top of the list, near the Quick Filters:

<img src="../images/bulk_edit_actions.png" alt="objects list" width="1500" height="1000"/>

1. Open the bulk edit menu
2. Flag/Unflag selected objects
3. Close/Reopen selected objects
4. Delete selected objects

### Bulk edit menu

<img src="../images/bulk_edit_menu.png" alt="objects list" width="500" height="500"/>

Allows to edit all selected objects. Possible options depend of the object type. For a `Case`:

* TLP
* PAP
* Severity
* Add Tags
* Remove Tags
* Status

## Single object actions

<img src="../images/unique_action_list.png" alt="objects list" width="1500" height="1000"/>

Actions can be run on a single object. Possible options depend of the object type. For a `Case`:

* Flag case
* Close case
* Reponders (allows analyst to trigger `responders` on a case from the list)

