# Cat Walk

Using JavaScript to move an animated cat across the screen. 

```bash
<img style="position:absolute;" src="catwalk.gif">

<script>
  var img = document.getElementsByTagName('img')[0];
  img.style.postion = 'absolute';
  img.style.left = '0px';

  function catWalk() {
    img.style.left = parseInt(img.style.left) + 10 + 'px';
  }

  window.setInterval(catWalk, 50);
</script>
```
