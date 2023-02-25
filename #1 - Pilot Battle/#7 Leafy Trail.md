# Leafy Trail

## Solution #1

**match**: 100% | **characters**: 569 | **score**: 601.77

```css
<div></div>
<style>
  body{
    background: #0B2429;
    margin: 75px 125px;
  }
  div{
    width: 150px;
    height: 150px;
    background: #998235;
    border-radius: 66% 0;
    position: relative;
  }
  div:after{
    position: absolute;
    content: '';
    width: 150px;
    height: 150px;
    background: #F3AC3C;
    border-radius: 66% 0;
    margin-left: 50px;
  }
  div:before{
    position: absolute;
    content: '';
    width: 150px;
    height: 150px;
    background: #1A4341;
    border-radius: 66% 0;
    margin-left: -50px;
    z-index: -1;
  }
</style>
```
