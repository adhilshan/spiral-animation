# Spiral Hypnotic Animation

A captivating spiral hypnotic animation created using only HTML and CSS! This effect uses expanding, fading circles to create a hypnotic, eye-catching animation that draws in viewers.

![Spiral Animation Preview](https://raw.githubusercontent.com/adhilshan/spiral-animation/refs/heads/main/Screenshot%202024-11-06%20125546.png)  

## Features

- **Pure HTML & CSS**: No JavaScript needed for this smooth animation effect.
- **Expanding Circles**: The animation creates a hypnotic illusion using multiple expanding circles with timed delays.
- **Customizable Colors and Size**: Easily change background color, circle color, and animation timing in the CSS.

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/adhilshan/spiral-animation.git
```

Then open `index.html` in a browser to view the animation.

## Usage

1. **Adjusting Colors**: Change the `background-color` property in the `body` style and the `border` color in the `.circles` class to customize the animation’s look.
2. **Animation Speed**: Modify the `animation-duration` in the `.one` to `.nine` classes to adjust the speed of the animation.
3. **Size Adjustments**: Tweak the `width` and `height` in the `.circles` class to make the circles larger or smaller.

## Code Explanation

The animation leverages CSS `@keyframes` and multiple circles with staggered delays for a hypnotic effect. Below is a preview of the CSS animation:

```css
@keyframes circles {
  from {
    transform: scale(0.3);
    display: none;
  }
  to {
    transform: scale(6);
  }
}

.circles {
  width: 20vw;
  height: 20vw;
  border: 5px solid white;
  border-radius: 50%;
  position: absolute;
  top: 40%;
  left: 40%;
  animation: circles 4.4s infinite linear;
}
```

## Contributing

Feel free to fork this project and make your own modifications or improvements! Pull requests are always welcome.
