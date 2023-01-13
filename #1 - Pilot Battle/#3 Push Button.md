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
