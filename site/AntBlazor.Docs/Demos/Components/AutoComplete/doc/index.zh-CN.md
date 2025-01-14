---
category: Components
type: 数据录入
title: AutoComplete
subtitle: 自动完成
cover: https://gw.alipayobjects.com/zos/alicdn/qtJm4yt45/AutoComplete.svg
---

输入框自动完成功能。

## 何时使用

需要自动完成时。

## API

### AutoComplete

| 参数 | 说明 | 类型 | 默认值 | 版本 |
| --- | --- | --- | --- | --- |
| `Backfill` | 使用键盘选择选项的时候把选中项回填到输入框中 | `boolean` | `false` |
| `Options` | 自动完成的数据源 | `AutocompleteDataSource` | - |
| `Disabled` | 是否禁用 | `bool` | - |
| `Placeholder` | 占位符文本 | `string` | - |
| `DefaultActiveFirstOption` | 是否默认高亮第一个选项。 | `boolean` | `true` |
| `Width` | 自定义宽度单位 px | `number` | auto |
| `OverlayClassName` | 下拉根元素的类名称 | `string` | - |
| `OverlayStyle` | 下拉根元素的样式 | `object` | - |
| `CompareWith` | `(o1: object, o2: object) => bool` | `(o1: object, o2: object) => o1===o2` |
| `PopupContainerSelector` | 菜单渲染父节点的选择器。默认渲染到 body 上，如果你遇到菜单滚动定位问题，试试修改为滚动的区域，并相对其定位。 | `string` | `'body'` |


### AutoCompleteOption

| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| `Value` | 绑定到触发元素 ngModel 的值 | `object` | - |
| `Label` | 填入触发元素显示的值 | `string` | - |
| `Disabled` | 禁用选项 | `boolean` | `false` |

