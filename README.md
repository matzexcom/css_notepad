# CSS Notepad
Collection of might be useful CSS features

## Line-Clamp - multi-line text truncate
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
