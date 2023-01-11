# Pilot Battle

## Solution #1

**match**: 100% | **characters**: 153 | **score**: 693.06

```css
<div></div>
<style>
    body{
        background: #5d3a3a;
        margin: 0;
    }
    div{
        width: 200px;
        height: 200px;
        background: #b5e0ba;
    }
</style>
```

### minimized - Solution #1

**match**: 100% | **characters**: 109 | **score**: 740.2

```css
<div></div><style>body{margin:0;background:#5d3a3a;}div{
width:200px;height:200px;background:#b5e0ba;}</style>
```

## Solution #2

**match**: 100% | **characters**: 188 | **score**: 666.66

```css
<style>
  body{
    background: #5d3a3a;
    margin: 0;
  }
  body:after{
    position:absolute;
    content: '';
    width: 200px;
    height: 200px;
    background: #b5e0ba;
  }
</style>
```
