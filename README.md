# Cat Walk

Using JavaScript to move an animated cat across the screen. 

```bash
<img style="position:absolute;" src="images/catwalk.gif">

<script>
  var img = document.getElementsByTagName('img')[0];
  //start position
  img.style.postion = 'absolute';
  img.style.left = '0px';

  function catWalk() {
    //distance traveled per frame
    img.style.left = parseInt(img.style.left) + 10 + 'px';
  }

  //speed
  window.setInterval(catWalk, 50);
</script>
```

