# #145. Spotlight

```html
<div></div>
<style>
  body {
    margin: 0;
    background: #E3516E
  }
  div {
    float: right;
    width: 150;
    height: 150;
    background: #D9D9D9;
  }
  div::after {
    content: '';
    display: block;
    position: absolute;
    top: 50;
    right: 50;
    width: 150;
    height: 150;
    border-radius: 100% 0 0 100%;
    rotate: -45deg;
    background: #D9D9D9
  }
</style>
```

![result](https://cssbattle.dev/targets/145.png)
