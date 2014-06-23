---
layout: default
---

# Function ifElse

Execute a conditional expression.


## Syntax

```js
math.ifElse(condition, trueExpr, falseExpr)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`condition` | Number &#124; Boolean &#124; String &#124; Complex &#124; BigNumber &#124; Unit |  The conditional expression
`trueExpr` | * | The true expression
`falseExpr` | * | The false expression

### Returns

Type | Description
---- | -----------
* | The evaluated return expression


## Examples

```js
var math = mathjs();

math.ifElse(true, 'yes', 'no');           // returns 'yes'
```




<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->