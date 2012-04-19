jquery.parallax.js
====== 

A jQuery parallax plugin 


Options
---
* `speed`: multiplier at which the rate of the selected elements scroll (default: `1`)
* `axis`: axis on which the selected elements scroll. Takes a string of `'x'` or `'y'` (default: `'x'`)

Example
---
Turns parallax on two layers on the Y-axis at different speeds.

```javascript
  $('.layer1').parallax({ speed: 0.5, axis: 'y' });
  $('.layer2').parallax({ speed: 0.3, axis: 'y' });
```

TODO
---
* Set up working demo
* Implement start/stop positions for parallax to trigger on and off. 

Contributing
---
This project uses [smoosh](https://github.com/fat/smoosh) for compiling, linting.
