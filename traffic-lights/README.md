# Traffic Lights - Pure CSS :traffic_light:

A set of traffic lights cycling through the colours. Pure CSS art.

## Overview

This was a fun project to work on. From a pencil sketch to this was a 
satisfying conclusion. :heart_eyes:

### The challenge

A 1 day challenge to create a set of traffic lights that light up.
  - Pure CSS (no SVG, Canvas or JS allowed)
  - Lights will be on a continuous cycle

## Tech stack

- Semantic HTML5 markup
- CSS custom properties
- SASS

## What I learned

This little project taught me a lot about CSS animations and how you can use it
with simple shapes to create a larger, more complicated image. Also learned
about layering.

```sass
@keyframes green-light-shine
  0%
    background: linear-gradient(-93deg, $green-light-on 56%, $green-light-off)
  30%
    background: linear-gradient(-93deg, $green-light-on 56%, $green-light-off)
  35%
    background: linear-gradient(-93deg, #111 56%, #111)
  100%
    background: linear-gradient(-93deg, #111 56%, #111)
```

## Author

- Website - [Carlos E Alford M](https://carlosealford.com)
- Twitter - [@webshuriken](https://www.twitter.com/webshuriken)

## Acknowledgments

My acknowledgment goes out to all those people working hard.
It is the grind which makes things like SASS. :smile:
