[](../README.md) / [Exports](../modules.md) / script_brush

# Class: script\_brush

## Table of contents

### Constructors

- [constructor](script_brush.md#constructor)

### Properties

- [on\_left\_click](script_brush.md#on_left_click)
- [on\_left\_hold](script_brush.md#on_left_hold)
- [on\_left\_release](script_brush.md#on_left_release)
- [on\_right\_click](script_brush.md#on_right_click)
- [on\_right\_hold](script_brush.md#on_right_hold)
- [on\_right\_release](script_brush.md#on_right_release)

### Methods

- [add\_int\_tag](script_brush.md#add_int_tag)
- [add\_real\_tag](script_brush.md#add_real_tag)
- [add\_string\_list\_tag](script_brush.md#add_string_list_tag)
- [add\_string\_tag](script_brush.md#add_string_tag)
- [get\_name](script_brush.md#get_name)
- [set\_name](script_brush.md#set_name)

## Constructors

### constructor

\+ **new script_brush**(): [*script\_brush*](script_brush.md)

**Returns:** [*script\_brush*](script_brush.md)

## Properties

### on\_left\_click

• **on\_left\_click**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:27

___

### on\_left\_hold

• **on\_left\_hold**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:28

___

### on\_left\_release

• **on\_left\_release**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:29

___

### on\_right\_click

• **on\_right\_click**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:31

___

### on\_right\_hold

• **on\_right\_hold**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:32

___

### on\_right\_release

• **on\_right\_release**: [*callback*](../modules.md#callback)<(`brush`: [*script\_brush*](script_brush.md), `event`: [*script\_brush\_event*](script_brush_event.md)) => *void*\>

Defined in: global.d.ts:33

## Methods

### add\_int\_tag

▸ **add_int_tag**(`item`: *string*, `low`: *number*, `high`: *number*, `def`: *number*): [*tag*](tag.md)<number\>

#### Parameters:

Name | Type |
:------ | :------ |
`item` | *string* |
`low` | *number* |
`high` | *number* |
`def` | *number* |

**Returns:** [*tag*](tag.md)<number\>

Defined in: global.d.ts:22

___

### add\_real\_tag

▸ **add_real_tag**(`item`: *string*, `low`: *number*, `high`: *number*, `def`: *number*): [*tag*](tag.md)<number\>

#### Parameters:

Name | Type |
:------ | :------ |
`item` | *string* |
`low` | *number* |
`high` | *number* |
`def` | *number* |

**Returns:** [*tag*](tag.md)<number\>

Defined in: global.d.ts:23

___

### add\_string\_list\_tag

▸ **add_string_list_tag**(`item`: *string*, ...`values`: *string*[]): [*tag*](tag.md)<string\>

#### Parameters:

Name | Type |
:------ | :------ |
`item` | *string* |
`...values` | *string*[] |

**Returns:** [*tag*](tag.md)<string\>

Defined in: global.d.ts:25

___

### add\_string\_tag

▸ **add_string_tag**(`item`: *string*, `def`: *string*): [*tag*](tag.md)<string\>

#### Parameters:

Name | Type |
:------ | :------ |
`item` | *string* |
`def` | *string* |

**Returns:** [*tag*](tag.md)<string\>

Defined in: global.d.ts:24

___

### get\_name

▸ **get_name**(): *string*

**Returns:** *string*

Defined in: global.d.ts:21

___

### set\_name

▸ **set_name**(`name`: *string*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`name` | *string* |

**Returns:** *void*

Defined in: global.d.ts:20
