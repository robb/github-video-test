# Github Video Test

## Markdown image syntax

`![](./record.mov)`
![](./record.mov)

`![](./record.webm)`
![](./record.webm)

`![](./record.gif)`
![](./record.gif)

## HTML `img` tag with `src`

`<img src="./record.mov">`
<img src="./record.mov">

`<img src="./record.webm">`
<img src="./record.webm">

`<img src="./record.gif">`
<img src="./record.gif">

## HTML `img` tag with `src` and `srcset`

`<img srcset="./record.mov, ./record.webm" src="./record.gif">`
<img srcset="./record.mov, ./record.webm" src="./record.gif">

## HTML `picture` tag

```html
<picture>
    <source srcset="./record.mov">
    <source srcset="./record.webm">
    <source srcset="./record.gif">
</picture>
```

<picture>
    <source srcset="./record.mov">
    <source srcset="./record.webm">
    <source srcset="./record.gif">
</picture>
