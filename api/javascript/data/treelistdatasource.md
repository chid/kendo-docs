---
title: TreeListDataSource
page_title: API Reference for Kendo UI TreeListDataSource
description: Learn more about the configuration of Kendo UI TreeListDataSource, methods and events.
---

# kendo.data.TreeListDataSource

The data source used by the [kendo.ui.TreeList](/api/web/TreeList) widget.
Inherits from [kendo.data.DataSource](/api/framework/datasource). The TreeListDataSource contains instances of the
[kendo.data.kendo.data.TreeListModel](/api/framework/treelistmodel) class.


## Configuration

See the [DataSource configuration](/api/framework/datasource#configuration) for all inherited configuration options.

### schema `Object`

The schema configuration of the TreeListDataSource.

### schema.model `Object`

The model configuration of the TreeListDataSource. See [kendo.data.TreeListModel](/api/framework/kendo.data.TreeListModel#configuration) for more info.

## Methods

See the [DataSource methods](/api/framework/datasource#methods) for all inherited methods.

### load

Loads the child nodes for model.

#### Parameters

##### model `kendo.data.TreeListModel`

The model that must be loaded.

### childNodes

Child nodes for model.

#### Parameters

##### model `kendo.data.TreeListModel`

The model whose children must be returned.

#### Returns

`Array` of the child items.

### rootNodes

Return all root nodes.

#### Returns

`Array` of the root items.

### parentNode

The parent of given node.

#### Parameters

##### model `kendo.data.TreeListModel`

The model whose parent must be returned.

#### Returns

`kendo.data.TreeListModel` parent of the node.

### level

The hierarchical level of the node.

#### Parameters

##### model `kendo.data.TreeListModel`

The model whose level must be calculated.

#### Returns

`Number` the hierachy level of the node.
