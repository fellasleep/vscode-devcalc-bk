# DevCalc

Convert between `px` and `vw` in VSCode.

## Features

- Supports converting focused value.
- Supports converting all values of the focused/selected line(s).
- Supports ignoring smaller values.
- Supports `px` to `vw` autocompletion conversion.
- Supports `vw` to `px` line annotations.
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
- `decimalPlaces`: retain maximum number of decimal places.
- `ignoreSmallerValues`: ignore smaller values(n) (-n ≤ px ≤ n will be ignored).
- `convertRange`: convert by selected/focused line or word.
- `enableAutocompleteConversion`: typing `px` autocomplete conversion `vw`.
- `showLineAnnotations`: focus/select the line with `vw` show annotations.
- `removeLeadingZero`: remove leading zero (0.5vw to .5vw).

**Enjoy!**
