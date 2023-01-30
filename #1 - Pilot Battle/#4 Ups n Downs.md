# Ups n Downs

## Solution #1

**match**: 100% | **characters**: 351 | **score**: 614.37

```css
<div></div>
<div></div>
<div></div>
<style>
  body{
    background: #62306D;
    display: flex;
    justify-content: center;
  }
  div{
    width: 100px;
    height: 100px;
    border-radius: 50% 50% 0 0;
    background: #F7EC7D;
    margin-top: 42px;
  }
  div:nth-child(odd){
    transform-origin: bottom;
    transform: rotate(180deg);
  }
</style>
```

### minimized - Solution #1

**match**: 100% | **characters**: 270 | **score**: 630.51

```css
<div></div><div></div><div></div><style>body{background:
#62306D;display:flex;justify-content:center}div{width:100px;
height:100px;border-radius:50% 50% 0 0;background:#F7EC7D;
margin-top:42px}div:nth-child(odd){transform-origin:bottom;
transform:rotate(180deg)}</style>
```
