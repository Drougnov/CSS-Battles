# Push Button

## Solution #1

**match**: 100% | **characters**: 703 | **score**: 600.49

```css
<div></div>
<style>
   body{
     background: #6592CF;
     display: grid;
     place-items: center;
   }
  body:before{
    position: absolute;
    content: '';
    width: 300px;
    height: 150px;
    background: #243D83;
  }
  body:after{
    position:absolute;
    content: '';
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background: #6592CF;
  }
  div{
    background: #6592CF;
    display: grid;
    place-items: center;
    width: 150px;
    height: 150px;
    background: #243D83;
    border-radius: 50%;
    z-index: 5;
  }
  div:after{
    position:absolute;
    content: '';
    width: 50px;
    height: 50px;
    background: #EEB850;
    border-radius: 50%;
  }
</style>
```

### minimized - Solution #1

**match**: 100% | **characters**: 400 | **score**: 608.84

```css
<div></div><style>body,div{background:#6592CF;display:grid;
place-items:center;}body:before,body:after,div:after{width:
300px;content:'';position:absolute;background:#243D83;
height:150px;}body:after,div,div:after{width:250px;height:
250px;border-radius:50%;background:#6592CF;}div{width:150px;
height:150px;background:#243D83;z-index:5;}div:after{width:
50px;height:50px;background:#EEB850;}</style>
```

## Solution #2

**match**: 100% | **characters**: 624 | **score**: 601.05

```css
<div class="rectangle"></div>
<div class="circle">
  <div></div>
</div>
<style>
  body{
    background: #6592CF;
    display: grid;
    justify-items: center;
    align-items: center;
  }
  .rectangle{
    width:300px;
    height:150px; 
    background:#243D83;
  }
  .circle{
    position: absolute;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background: #6592CF;
    display: grid;
    justify-items: center;
    align-items: center;
  }
  .circle>div{
    position: absolute;
    width:50px;
    height:50px;
    border:50px solid #243D83;
    border-radius:50%;
    background:#EEB850;
  }
</style>
```

### minimized - Solution #2

**match**: 100% | **characters**: 448 | **score**: 605.59

```css
<div class="r"></div><div class="c"><div></div></div>
<style>body{background:#6592CF;display:grid;justify-items:
center;align-items:center;}.r{width:300px;height:150px;
background:#243D83;}.c{position:absolute;width:250px;height:2
50px;border-radius:50%;background:#6592CF;display:grid;
justify-items:center;align-items:center;}.c>div{position:
absolute;width:50px;height:50px;border:50px solid #243D83;
border-radius:50%;background:#EEB850;}</style>
```
