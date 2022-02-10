# Push Button
#  [Target #3 - Push Button](https://cssbattle.dev/play/3)

![](https://cssbattle.dev/targets/3.png)


## My Solution
```HTML
<div class="a">
  <div class="q">
    <div class="c b"></div>
    <div class="c s"></div>
  </div>
</div>
<style>
  .a {
    position: fixed;
    inset: 0;
    background: #6592cf;
  }
  .q {
    position: relative;
    top: 25%;
    width: 75%;
    background: #243d83;
    height: 150;
    left: 12.5%;
  }
  .c {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
  }
  .s {
    width: 50;
    height: 50;
    background: #eeb850;
  }
  .b {
    width: 150;
    height: 150;
    background: #243d83;
    border: 50px solid #6592cf;
  }
</style>
```
## Optimized Solution
```HTML
<style>*{margin:75 50;background:radial-gradient(circle,#eeB850 25px,0,#243D83 75px,0,transparent 125px,#243D83 125px)no-repeat#6592CF}</style>
```

## Concept
  - Background
  - Radial-gradient