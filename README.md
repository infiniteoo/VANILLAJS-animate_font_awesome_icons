# VANILLA.JS - Animate Font Awesome Icons

### About

A quick lil project to animate font awesome icons utilizing setTimeout and setIntervals to change the innerHTML of a div using the Font Awesome unicode.

### Example

```
// houeglass animation
    function hourglassTip() {
      let hourglass = document.getElementById("hourglass");

      hourglass.innerHTML = "&#xf251";

      setTimeout(function () {
        hourglass.innerHTML = "&#xf252";
      }, 1000);
      setTimeout(function () {
        hourglass.innerHTML = "&#xf253";
      }, 2000);
    }

    hourglassTip();
    setInterval(hourglassTip, 3000);
```
