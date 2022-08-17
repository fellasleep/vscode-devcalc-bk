# DevCalc

在 VSCode 中 `px` 和 `vw` 之间相互转换。

## 特性

- 支持转换已聚焦的值。
- 支持转换已聚焦/选定行中的所有值。
- 支持忽略较小的值。
- 支持 `px` 到 `vw` 自动完成转换。
- 支持 `vw` 到 `px` 行注释。
- 支持 `vw` 到 `px` 悬停消息。
- 支持快速更新屏幕宽度。
- 支持修改状态栏外观。

## 用法

- 按下 `Alt` + `Z` 进行转换。
- 按下 `Alt` + `Q` 或点击状态栏更新屏幕宽度。
- 键入 `px` 时自动补全 `vw` 的转换结果。
- 悬停 `vw` 显示当前屏幕宽度转换来的 `px`。
- 聚焦/选择带有 `vw` 的行显示 `px` 注释。

## 快捷键

| 命令                        | 描述                     | 按键         |
| :-------------------------- | :---------------------- | :---------- |
| `devcalc.px2vw`             | 转换 `px` 到 `vw`        |             |
| `devcalc.vw2px`             | 转换 `vw` 到 `px`        |             |
| `devcalc.px2vw2px`          | `px` 和 `vw` 之间相互转换 | `Alt` + `Z` |
| `devcalc.updateScreenWidth` | 更新屏幕/设计宽度         | `Alt` + `Q` |

> 你可以进入键盘快捷键设置中重新定义它们。

## 配置

| 名字                                   | 描述                                              | 默认值 |
| :------------------------------------- | :----------------------------------------------- | :------ |
| `devcalc.screenWidth`                  | 设置屏幕/设计宽度                                  | `1920`  |
| `devcalc.decimalPlaces`                | 保留最大小数位数                                   | `6`     |
| `devcalc.ignoreSmallerValues`          | 转换时忽略较小的数值(n) (-n ≤ `px` ≤ n 将不会被转换) | `2`     |
| `devcalc.convertRange`                 | 转换选区/已聚焦的 `word` 或 `line`                 | `word`  |
| `devcalc.enableAutocompleteConversion` | 键入 `px` 时自动补全 `vw` 的转换结果                | `true`  |
| `devcalc.showLineAnnotations`          | 聚焦/选择带有 `vw` 的行显示 `px` 注释               | `true`  |
| `devcalc.removeLeadingZero`            | 删除前导零 (0.5px → .5px)                          | `true`  |
| `devcalc.statusBarAppearance`          | 设置状态栏外观，文本或图标 + `screenWidth`          | `text`  |
| `devcalc.statusBarPosition`            | 设置状态栏位置，`left` 或 `right`                  | `right` |
| `devcalc.statusBarPriority`            | 设置状态栏优先级，数字越大越靠左                    | `0`     |

# DevCalc

Convert between `px` and `vw` in VSCode.

## Features

- Supports converting focused value.
- Supports converting all values of the focused/selected line(s).
- Supports ignoring smaller values.
- Supports `px` to `vw` autocompletion conversion.
- Supports `vw` to `px` line annotations.
- Supports `vw` to `px` hover message.
- Supports quick update screen width.
- Supports modifying status bar appearance.

## Usage

- Press `Alt` + `Z` to convert.
- Press `Alt` + `Q` or click status bar to update screen width.
- Type `px` to autocomplete the conversion to `vw`.
- Hover `vw` to display `px` of the current screen width conversion.
- Focus/select the line with `vw` show annotations.

## Shortcuts

| Command                     | Description                   | Key         |
| :-------------------------- | :---------------------------- | :---------- |
| `devcalc.px2vw`             | convert `px` to `vw`          |             |
| `devcalc.vw2px`             | convert `vw` to `px`          |             |
| `devcalc.px2vw2px`          | convert between `px` and `vw` | `Alt` + `Z` |
| `devcalc.updateScreenWidth` | update screen/design width    | `Alt` + `Q` |
> You can go to Keyboard Shortcuts to redefine them.

## Configuration

| Name                                   | Description                                             | Default |
| :------------------------------------- | :------------------------------------------------------ | :------ |
| `devcalc.screenWidth`                  | setup screen/design width                               | `1920`  |
| `devcalc.decimalPlaces`                | retain maximum number of decimal places                 | `6`     |
| `devcalc.ignoreSmallerValues`          | ignore smaller values(n) (n ≤ `px` ≤ n will be ignored) | `2`     |
| `devcalc.convertRange`                 | convert by selected/focused word or line                | `word`  |
| `devcalc.enableAutocompleteConversion` | typing `px` autocomplete conversion `vw`                | `true`  |
| `devcalc.showLineAnnotations`          | focus/select the line with `vw` show annotations        | `true`  |
| `devcalc.removeLeadingZero`            | remove leading zero (0.5vw → .5vw)                      | `true`  |
| `devcalc.statusBarAppearance`          | setup status bar appearance text/icon + `screenWidth`   | `text`  |
| `devcalc.statusBarPosition`            | setup status bar position `left` or `right`             | `right` |
| `devcalc.statusBarPriority`            | setup status bar priority, larger value, more to left   | `0`     |

**Enjoy!**
