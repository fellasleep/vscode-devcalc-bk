# DevCalc

Convert between `px` and `vw` in vscode.

## Features

- Supports converting focused value.
- Supports converting all values of the focused/selected line(s).
- Supports ignoring smaller values.
- Supports `px` to `vw` autocompletion.
- Supports `vw` to `px` annotations.
- Supports `vw` to `px` hover message.
- Supports quick update `screen width`.

## Usage

- Press `Alt+Z` to convert.
- Type `px` to autocomplete the conversion to `vw`.
- Hover `vw` to display `px` of the current screen width conversion.
- Focus/select the line with `vw` show annotations.
- Click status bar to update `screen width`.

## Settings

- `screenWidth`: set screen width.
- `maximumNumberOfDecimalPlaces`: retain maximum number of decimal places.
- `ignoreSmallerValues`: ignore smaller values (-2 <= px <= 2 will be ignored).
- `convertRange`: convert by selected/focused line or word.
- `autoCompletion`: type in `px` for quick conversions.
- `showLineAnnotations`: focus/select the line with `vw` show annotations.
- `removeLeadingZero`: remove leading zero (0.5vw to .5vw).
- `notifyWhenNoChanges`: notify when there is no value to convert.

**Enjoy!**
