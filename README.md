# CSS Notepad
Collection of might be useful CSS features

## Contents
 - [Multiple Box Shadow](#multiple-box-shadows)
 - [Line-Clamp](#line-clamp)

## <a name="line-clamp"></a>Line-Clamp - multi-line text truncate
If you want multi-line text with `text-overflow: elipsis` style

### CanIUse
[line-clamp](https://caniuse.com/css-line-clamp) at Dec. 2020 prefixes needed

### Syntax
```CSS
.element {
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
}
```

### Links
 - https://css-tricks.com/almanac/properties/l/line-clamp/


## <a name="multiple-box-shadows"></a>Multiple Box Shadows (Facebook Style)
Nothing special, just a copy-cat from Facebook. The shadow make you feel that is has depth and is far more real compared to a regular shadow

### Syntax
```CSS
.element {
    box-shadow: 0 12px 28px 0 rgba(0, 0, 0, 0.2), 0 2px 4px 0 rgba(0, 0, 0, 0.1), inset 0 0 0 1px rgba(255, 255, 255, 0.5);
}
```
