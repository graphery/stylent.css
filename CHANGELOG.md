# stylent.css Change Log

## Version 1.1.1 (04/05/2022)

- Added `!important` to `display: none` on `.hidden` class.

## Version 1.1.0 (27/04/2022)

- Change `--st-font-size` value to `15px`.
- Added `min-height` on `html` and `body` with value `100vh`.
- Fixed `[type=summit]` with `[type=submit]`.
- Added `a.button` as button style.
- Change the `opacity` value to `0.5` in disabled buttons.
- Remove `margin-top` and `margin-bottom` on `img`.
- Change `width` value to `1200px` on `header` and `main`.

## Version 1.0.0 (17/01/2022)

- First estable version.
- Removed `--st-font-size-xs`.
- Changed `--st-font-size-s` value to `0.8em`.
- Removed `--st-space-l`, `--st-space-xl`, and `--st-space-xxl`.
- Added `--st-space-after`, `--st-space-before`, and `--st-gutter`.
- Normalized space before and after elements. 

## Version 0.2.3 (05/01/2022)

- Fixed `.no-dark` reference (it's removed from 0.2.0).

## Version 0.2.2 (01/01/2022)

- Changed the button opacity from 0.5 to 0.4
- Fixed error in minimized version.
- Fixed error with fieldset border.
- Fixed minor error in documentation.

## Version 0.2.1 (31/12/2021)

- recovered variables `--st-fore-color-dark`, `--st-bg-color-dark`, `--st-fore-color-alt-dark`, and
  `--st-bg-color-alt-dark`.
- Fixed `code` colors.
- Fixed style for visited anchor.

## Version 0.2.0 (30/12/2021)

- Changed `rem` to `em` in `--st-font-size-xs` and `--st-font-size-s`.
- Reduced font size for `l`, `xl`, `xxl`, and `xxxxl`.
- Remove color variables with name: `--st-black`, `--st-darkgray`, `--st-gray`, `--st-lightgray`, `--st-white`,
  `--st-blue`, `--st-red`, `--st-yellow`, `--st-green`, and `--st-violet`.
- Added the schema color variables: `--st-color-0`, `--st-color-1`, `--st-color-2`, `--st-color-3`, `--st-color-4`, 
  `--st-color-5`, `--st-color-6`, `--st-color-7`, `--st-color-8`, and `--st-color-9`.
- The different color variables are adjusted to follow the established color schema.
- Fixed the `.dark` style.
- Removed the `.no-dark` style.
- Added the `.light` style for force the light mode.
- Added smooth scroll.
- Change the style for hover and focus on buttons.

## Version 0.1.0 (12/12/2021)

- Added automatic dark mode support.
- Added `.dark` and `.no-dark` auxiliary class.
- Added custom css properties for dar mode.
- Fixed the fore color for `<code>`.
- Fixed the input focus color.
- Optimized the `line-height` management.

## Version 0.0.5 (10/12/2021)

- Remove space between nested list.
- added `display: flex` on all related classes.
- removed the `.flex` class, this attribute is now included in other classes and is not allowed to be used as a
  stand-alone class.
- Improved auxiliary class documentation.

## Version 0.0.4 (08/12/2021)

- Improved documentation.
- Added css variables for link styling and hover links.
- `label` is now shown as `inline-block`.
- Fixed a bug with disabled buttons and hover.
- Increased transparency when a button is disabled.

## Version 0.0.3 (07/12/2021)

- Changed the relative font size from `rem` to `em`.
- Added the `--st-space` variable and its relative size `-l`, `-xl`, and `-xxl`.
- Normalized `margin-top` and `margin-bottom` for every element.
- Normalized `gutter` space between rows and columns.
- Fixed an error with `line-height` in sub elements.
- Fixed an error with `font-size` in sub elements.
- Removed undocumented `samp` support.

## Version 0.0.2 (07/12/2021)

- Changed `.separated` to `.gutter`.
- Fixed `.gutter` with first column.
- Fixed `input type="image"` style.
- Fixed `input type="image"` example.
- Fixed `index.html` on mobile devices.

## Version 0.0.1 (06/12/2021)

- Initial version