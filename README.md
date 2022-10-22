# lospec2css

Simple script for converting a color palette from [Lospec](https://lospec.com/palette-list) into a CSS file containing the palette as variables.

*You will need to rename the colors afterwards, but that's much faster than copying all the hex values in.*

## Usage

1. `pip install lospec2css`
2. `python lospec2css.py input output`

## Example

```txt
# Input: halloween-candy.hex
# https://lospec.com/palette-list/halloween-candy
001122
221155
771188
cc2222
cc8811
44cc44
ddee55
eeddff
```

```css
/* Output: theme.css */
:root {
    --color-0: #001122;
    --color-1: #221155;
    --color-2: #771188;
    --color-3: #cc2222;
    --color-4: #cc8811;
    --color-5: #44cc44;
    --color-6: #ddee55;
    --color-7: #eeddff;
}
```

## License

lospec2css source code is dual-licensed under either

- **[MIT License](/docs/LICENSE-MIT)**
- **[Apache License, Version 2.0](/docs/LICENSE-APACHE)**

at your option.
