# #29. Suffocate

```html
<div></div>
<style>
  body {
    background: #F3AC3C
  }
  div {
    margin: 83 auto;
    width: 135;
    height: 135;
    rotate: 45deg;
    background: #1A4341;
  }
  div::after {
    display: block;
    content: '';
    translate: 54% -16%;
    left: -40;
    width: 200;
    height: 200;
    background: #F3AC3C;
    border-radius: 50%;
    box-shadow: -283px 0 #F3AC3C, -141px 141px #F3AC3C, -141px -142px #F3AC3C
  }
</style>
```

![result](https://cssbattle.dev/targets/29.png)
