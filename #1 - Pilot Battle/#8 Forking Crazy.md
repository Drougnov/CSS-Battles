# Forking Crazy

## Solution #1

**match**: 100% | **characters**: 775 | **score**: 600.25

```css
<div class="top">
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
</div>
<div class="middle"></div>
<div class="bottom"></div>
<style>
  body{
    background: #6592CF;
  }
  .top{
    display: flex;
    width: 140px;
    height: 110px;
    margin: 50px auto;
  }
  .top span{
    width: 20px;
  }
  span:nth-child(odd){
    border-radius: 20px 20px 0 0;
    background: #060F55;
  }
  span:nth-child(even){
    background: #6592CF;
    border-radius: 0 0 20px 20px;
  }
  .middle{
    width: 140px;
    height: 100px;
    background: #060F55;
    margin: -60px auto;
    border-radius: 0 0 80px 80px;
  }
  .bottom{
    width: 20px;
    height: 55px;
    background: #060F55;
    margin: 55px auto;
  }
</style>
```

### minimized - Solution #1

**match**: 100% | **characters**: 553 | **score**: 602.06

```css
<div id="t"><span></span><span></span><span></span><span>
</span><span></span><span></span><span></span></div><div
 id="m"></div><div id="b"></div><style>body{background:
 #6592CF}#t{display:flex;width:140px;height:110px;margin:50px
  auto}#t span{width:20px}span:nth-child(odd){background:
   #060F55;border-radius:20px 20px 0 0}span:nth-child(even){
background:#6592CF;border-radius:0 0 20px 20px}#m{width:
 140px;height:100px;background:#060F55;margin:-60px auto;
border-radius:0 0 80px 80px}#b{width:20px;height:55px;margin:
 55px auto;background:#060F55
```
