[](README.md) / Exports

# 

## Table of contents

### Classes

- [chunk](classes/chunk.md)
- [chunk\_iterator](classes/chunk_iterator.md)
- [image](classes/image.md)
- [model](classes/model.md)
- [model\_iterator](classes/model_iterator.md)
- [noisemap](classes/noisemap.md)
- [random](classes/random.md)
- [script\_brush](classes/script_brush.md)
- [script\_brush\_event](classes/script_brush_event.md)
- [selection](classes/selection.md)
- [tag](classes/tag.md)
- [tex](classes/tex.md)
- [tex\_iterator](classes/tex_iterator.md)
- [vector\_3d](classes/vector_3d.md)
- [vert](classes/vert.md)
- [vert\_iterator](classes/vert_iterator.md)

### Type aliases

- [brush\_callback](modules.md#brush_callback)
- [callback](modules.md#callback)

### Functions

- [abs](modules.md#abs)
- [acos](modules.md#acos)
- [acosh](modules.md#acosh)
- [add\_m2](modules.md#add_m2)
- [add\_wmo](modules.md#add_wmo)
- [append\_file](modules.md#append_file)
- [asin](modules.md#asin)
- [asinh](modules.md#asinh)
- [atan](modules.md#atan)
- [atanh](modules.md#atanh)
- [brush](modules.md#brush)
- [cam\_pitch](modules.md#cam_pitch)
- [cam\_yaw](modules.md#cam_yaw)
- [camera\_pos](modules.md#camera_pos)
- [cbrt](modules.md#cbrt)
- [ceil](modules.md#ceil)
- [cos](modules.md#cos)
- [cosh](modules.md#cosh)
- [create\_image](modules.md#create_image)
- [dist\_2d](modules.md#dist_2d)
- [dist\_2d\_compare](modules.md#dist_2d_compare)
- [exp](modules.md#exp)
- [floor](modules.md#floor)
- [get\_area\_id](modules.md#get_area_id)
- [get\_map\_id](modules.md#get_map_id)
- [holding\_alt](modules.md#holding_alt)
- [holding\_ctrl](modules.md#holding_ctrl)
- [holding\_left\_mouse](modules.md#holding_left_mouse)
- [holding\_right\_mouse](modules.md#holding_right_mouse)
- [holding\_shift](modules.md#holding_shift)
- [holding\_space](modules.md#holding_space)
- [lerp](modules.md#lerp)
- [load\_png](modules.md#load_png)
- [log](modules.md#log)
- [log10](modules.md#log10)
- [make\_noise](modules.md#make_noise)
- [path\_exists](modules.md#path_exists)
- [pow](modules.md#pow)
- [print](modules.md#print)
- [random\_from\_seed](modules.md#random_from_seed)
- [random\_from\_time](modules.md#random_from_time)
- [read\_file](modules.md#read_file)
- [rotate\_2d](modules.md#rotate_2d)
- [round](modules.md#round)
- [select\_between](modules.md#select_between)
- [select\_origin](modules.md#select_origin)
- [sin](modules.md#sin)
- [sinh](modules.md#sinh)
- [sqrt](modules.md#sqrt)
- [tan](modules.md#tan)
- [tanh](modules.md#tanh)
- [write\_file](modules.md#write_file)

## Type aliases

### brush\_callback

Ƭ **brush\_callback**: [*callback*](modules.md#callback)<(`brush`: [*script\_brush*](classes/script_brush.md), `event`: [*script\_brush\_event*](classes/script_brush_event.md)) => *void*\>

Defined in: global.d.ts:3

___

### callback

Ƭ **callback**<T\>: T \| *undefined*

#### Type parameters:

Name |
:------ |
`T` |

Defined in: global.d.ts:1

## Functions

### abs

▸ **abs**(`arg`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`arg` | *number* |

**Returns:** *any*

Defined in: global.d.ts:128

___

### acos

▸ **acos**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:121

___

### acosh

▸ **acosh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:115

___

### add\_m2

▸ **add_m2**(`filename`: *string*, `pos`: [*vector\_3d*](classes/vector_3d.md), `scale`: *number*, `rotation`: [*vector\_3d*](classes/vector_3d.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`filename` | *string* |
`pos` | [*vector\_3d*](classes/vector_3d.md) |
`scale` | *number* |
`rotation` | [*vector\_3d*](classes/vector_3d.md) |

**Returns:** *void*

Defined in: global.d.ts:65

___

### add\_wmo

▸ **add_wmo**(`filename`: *string*, `pos`: [*vector\_3d*](classes/vector_3d.md), `rot`: [*vector\_3d*](classes/vector_3d.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`filename` | *string* |
`pos` | [*vector\_3d*](classes/vector_3d.md) |
`rot` | [*vector\_3d*](classes/vector_3d.md) |

**Returns:** *void*

Defined in: global.d.ts:71

___

### append\_file

▸ **append_file**(`file`: *string*, `content`: *string*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`file` | *string* |
`content` | *string* |

**Returns:** *void*

Defined in: global.d.ts:60

___

### asin

▸ **asin**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:122

___

### asinh

▸ **asinh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:116

___

### atan

▸ **atan**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:123

___

### atanh

▸ **atanh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:117

___

### brush

▸ **brush**(`name`: *string*): [*script\_brush*](classes/script_brush.md)

#### Parameters:

Name | Type |
:------ | :------ |
`name` | *string* |

**Returns:** [*script\_brush*](classes/script_brush.md)

Defined in: global.d.ts:35

___

### cam\_pitch

▸ **cam_pitch**(): *number*

**Returns:** *number*

Defined in: global.d.ts:79

___

### cam\_yaw

▸ **cam_yaw**(): *number*

**Returns:** *number*

Defined in: global.d.ts:80

___

### camera\_pos

▸ **camera_pos**(): [*vector\_3d*](classes/vector_3d.md)

**Returns:** [*vector\_3d*](classes/vector_3d.md)

Defined in: global.d.ts:64

___

### cbrt

▸ **cbrt**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:114

___

### ceil

▸ **ceil**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:111

___

### cos

▸ **cos**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:124

___

### cosh

▸ **cosh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:118

___

### create\_image

▸ **create_image**(`width`: *number*, `height`: *number*): [*image*](classes/image.md)

#### Parameters:

Name | Type |
:------ | :------ |
`width` | *number* |
`height` | *number* |

**Returns:** [*image*](classes/image.md)

Defined in: global.d.ts:104

___

### dist\_2d

▸ **dist_2d**(`from`: [*vector\_3d*](classes/vector_3d.md), `to`: [*vector\_3d*](classes/vector_3d.md)): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`from` | [*vector\_3d*](classes/vector_3d.md) |
`to` | [*vector\_3d*](classes/vector_3d.md) |

**Returns:** *any*

Defined in: global.d.ts:131

___

### dist\_2d\_compare

▸ **dist_2d_compare**(`from`: [*vector\_3d*](classes/vector_3d.md), `to`: [*vector\_3d*](classes/vector_3d.md), `dist`: *number*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`from` | [*vector\_3d*](classes/vector_3d.md) |
`to` | [*vector\_3d*](classes/vector_3d.md) |
`dist` | *number* |

**Returns:** *number*

Defined in: global.d.ts:132

___

### exp

▸ **exp**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:113

___

### floor

▸ **floor**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:112

___

### get\_area\_id

▸ **get_area_id**(): *number*

**Returns:** *number*

Defined in: global.d.ts:77

___

### get\_map\_id

▸ **get_map_id**(): *number*

**Returns:** *number*

Defined in: global.d.ts:76

___

### holding\_alt

▸ **holding_alt**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:81

___

### holding\_ctrl

▸ **holding_ctrl**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:83

___

### holding\_left\_mouse

▸ **holding_left_mouse**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:85

___

### holding\_right\_mouse

▸ **holding_right_mouse**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:86

___

### holding\_shift

▸ **holding_shift**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:82

___

### holding\_space

▸ **holding_space**(): *boolean*

**Returns:** *boolean*

Defined in: global.d.ts:84

___

### lerp

▸ **lerp**(`from`: *number*, `to`: *number*, `amount`: *number*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`from` | *number* |
`to` | *number* |
`amount` | *number* |

**Returns:** *number*

Defined in: global.d.ts:130

___

### load\_png

▸ **load_png**(`path`: *string*): [*image*](classes/image.md)

#### Parameters:

Name | Type |
:------ | :------ |
`path` | *string* |

**Returns:** [*image*](classes/image.md)

Defined in: global.d.ts:105

___

### log

▸ **log**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:110

___

### log10

▸ **log10**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:109

___

### make\_noise

▸ **make_noise**(`start_x`: *number*, `start_y`: *number*, `width`: *number*, `height`: *number*, `frequency`: *number*, `algorithm`: *string*, `seed`: *string*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`start_x` | *number* |
`start_y` | *number* |
`width` | *number* |
`height` | *number* |
`frequency` | *number* |
`algorithm` | *string* |
`seed` | *string* |

**Returns:** *any*

Defined in: global.d.ts:162

___

### path\_exists

▸ **path_exists**(`path`: *string*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`path` | *string* |

**Returns:** *boolean*

Defined in: global.d.ts:62

___

### pow

▸ **pow**(`a1`: *number*, `a2`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a1` | *number* |
`a2` | *number* |

**Returns:** *any*

Defined in: global.d.ts:108

___

### print

▸ **print**(): *void*

**Returns:** *void*

Defined in: ../../../../../../../../Users/bwobwo2/AppData/Roaming/npm/node_modules/typescript/lib/lib.dom.d.ts:19523

▸ **print**(...`args`: *any*[]): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | *any*[] |

**Returns:** *any*

Defined in: global.d.ts:87

___

### random\_from\_seed

▸ **random_from_seed**(`seed`: *string*): [*random*](classes/random.md)

#### Parameters:

Name | Type |
:------ | :------ |
`seed` | *string* |

**Returns:** [*random*](classes/random.md)

Defined in: global.d.ts:169

___

### random\_from\_time

▸ **random_from_time**(): [*random*](classes/random.md)

**Returns:** [*random*](classes/random.md)

Defined in: global.d.ts:170

___

### read\_file

▸ **read_file**(`file`: *string*): *string*

#### Parameters:

Name | Type |
:------ | :------ |
`file` | *string* |

**Returns:** *string*

Defined in: global.d.ts:61

___

### rotate\_2d

▸ **rotate_2d**(`point`: [*vector\_3d*](classes/vector_3d.md), `origin`: [*vector\_3d*](classes/vector_3d.md), `angle`: *number*): [*vector\_3d*](classes/vector_3d.md)

#### Parameters:

Name | Type |
:------ | :------ |
`point` | [*vector\_3d*](classes/vector_3d.md) |
`origin` | [*vector\_3d*](classes/vector_3d.md) |
`angle` | *number* |

**Returns:** [*vector\_3d*](classes/vector_3d.md)

Defined in: global.d.ts:133

___

### round

▸ **round**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:107

___

### select\_between

▸ **select_between**(`point1`: [*vector\_3d*](classes/vector_3d.md), `point2`: [*vector\_3d*](classes/vector_3d.md)): [*selection*](classes/selection.md)

#### Parameters:

Name | Type |
:------ | :------ |
`point1` | [*vector\_3d*](classes/vector_3d.md) |
`point2` | [*vector\_3d*](classes/vector_3d.md) |

**Returns:** [*selection*](classes/selection.md)

Defined in: global.d.ts:188

___

### select\_origin

▸ **select_origin**(`origin`: [*vector\_3d*](classes/vector_3d.md), `xRadius`: *number*, `zRadius`: *number*): [*selection*](classes/selection.md)

#### Parameters:

Name | Type |
:------ | :------ |
`origin` | [*vector\_3d*](classes/vector_3d.md) |
`xRadius` | *number* |
`zRadius` | *number* |

**Returns:** [*selection*](classes/selection.md)

Defined in: global.d.ts:189

___

### sin

▸ **sin**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:125

___

### sinh

▸ **sinh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:119

___

### sqrt

▸ **sqrt**(`arg`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`arg` | *number* |

**Returns:** *any*

Defined in: global.d.ts:127

___

### tan

▸ **tan**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:126

___

### tanh

▸ **tanh**(`a`: *number*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | *number* |

**Returns:** *any*

Defined in: global.d.ts:120

___

### write\_file

▸ **write_file**(`file`: *string*, `content`: *string*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`file` | *string* |
`content` | *string* |

**Returns:** *void*

Defined in: global.d.ts:59
