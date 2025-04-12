# Traffic Lights - Pure CSS

A set of traffic lights cycling through the colours. Pure CSS art.

## Overview :traffic_light:

This was a fun project to work on. From a pencil sketch to this was a 
satisfying conclusion. :heart_eyes:

### The challenge

A 1 day challenge to create a set of traffic lights that light up.
  - Pure CSS (no SVG, Canvas or JS allowed)
  - Lights will be on a continuous cycle

### Screenshot

![A set of traffic lights with pure CSS](./screenshot.png)

### Links

- Solution URL: [Github Repo](https://github.com/CarlosEAM/traffic-lights_pure-css)
- Live URL: [Traffic Lights](https://carloseam.github.io/traffic-lights_pure-css/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [SASS](https://sass-lang.com/)

### What I learned

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

### Continued development

Doing more Pure CSS challenges are going to come in handy, specially when
designing on working on CSS image creations.

## Author

- Website - [Carlos E Alford M](https://carlosealford.com)
- Frontend Mentor - [CarlosEAM](https://www.frontendmentor.io/profile/CarlosEAM)
- Twitter - [@webshuriken](https://www.twitter.com/webshuriken)

## Acknowledgments

My acknowledgment goes out to all those people working hard.
It is the grind which makes things like SASS. :smile:
