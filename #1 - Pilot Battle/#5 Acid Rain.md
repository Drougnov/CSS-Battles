# Acid Rain

## Solution #1

**match**: 100% | **characters**: 615 | **score**: 601.14

```css
<div></div>
<style>
  body{
    display: grid;
    place-items: center;
    background: #0B2429;
  }
  div{
    width: 120px;
    height: 120px;
    background: #998235;
    border-radius: 50% 0 50% 50%;
    position: relative;
  }

  div:before{
    position: absolute;
    content: '';
    inset: 60px 0 0px -60px;
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    border-radius: 50% 0 50% 50%;
  }
  div:after{
    position: absolute;
    content: '';
    inset: -60px 0 0px 60px;
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    border-radius: 50%;
    z-index: -1;
  }
</style>
```

### minimized - Solution #1

**match**: 100% | **characters**: 355 | **score**: 613.57

```css
<div></div><style>body{display:grid;place-items:center;
background:#0B2429}div,div:before,div:after{width:120px;heigh
t:120px;background:#998235;border-radius:50% 0 50% 50%;
position:relative}div:before,div:after{position:absolute;cont
ent:'';inset:60px 0 0px -60px;background:#F3AC3C}div:after{
inset:-60px 0 0px 60px;border-radius:50%;z-index: -1}</style>
```
