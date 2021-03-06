---
title: WebBrowserControl.Move method (Access)
keywords: vbaac10.chm14387
f1_keywords:
- vbaac10.chm14387
ms.prod: access
api_name:
- Access.WebBrowserControl.Move
ms.assetid: ec60f843-6bbf-bf65-db6a-9097dd73fb98
ms.date: 06/08/2017
---


# WebBrowserControl.Move method (Access)

Moves the specified object to the coordinates specified by the argument values.


## Syntax

_expression_. `Move`( ` _Left_`, ` _Top_`, ` _Width_`, ` _Height_` )

_expression_ A variable that represents a [WebBrowserControl](Access.WebBrowserControl.md) object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Left_|Required|**Variant**||
| _Top_|Optional|**Variant**||
| _Width_|Optional|**Variant**||
| _Height_|Optional|**Variant**||

## Remarks

Only the  _Left_ argument is required. However, to specify any other arguments, you must specify all the arguments that precede it. For example, you cannot specify _Width_ without specifying _Left_ and _Top_. Any trailing arguments that are unspecified remain unchanged.

This method overrides the  **Moveable** property.

In Datasheet View or Print Preview, changes made using the  **Move** method are saved if the user explicitly saves the database, but Access does not prompt the user to save such changes.


## See also


[WebBrowserControl Object](Access.WebBrowserControl.md)

