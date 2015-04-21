---
title: Telerik.Web.UI.GridUserActionEventArgs
page_title: Client-side API Reference
description: Client-side API Reference
---

# Telerik.Web.UI.GridUserActionEventArgs : Sys.CancelEventArgs

## Methods

###  get_actionName

Returns the name of the initiated action.

#### Parameters

#### Returns

`String` 

###  get_newPageIndex

Returns the argument of the action. The name of the method depends on the action. For PageSize changing it is called get_newPageSize.

#### Parameters

#### Returns

`Number` 

###  get_tableView

Returns the owner TableView object.

#### Parameters

#### Returns

`Telerik.Web.UI.GridTableView` 

###  set_newPageIndex

Sets the argument of the action. The name of the method depends on the action. For PageSize changing it is called set_newPageSize.

#### Parameters

##### value `Number`

#### Returns

`None` 


