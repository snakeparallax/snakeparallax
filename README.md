# Snake Parallax
A jquery plugin that creates a simple, clean, and powerfull parallax effect.

See live demo: [https://snakeparallax.github.io/snakeparallax/](https://snakeparallax.github.io/snakeparallax/)

## Getting started

### Dependecies

Get the latest [jQuery](https://code.jquery.com/jquery/ "JQuery Core - All Versions") library.

## Installation

### Include JS

First, include JQuery and ```Snake.Parallax.js``` files into your HTML head:

```
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="js/Snake.Parallax.js"></script>
```
### Call the plugin

Second, call the Snake Parallax initializer.

```
<script>
  $(document, window).SnakeParallax({
    backgroundImage:"url('YOUR_HERO_IMAGE')"
  });
</script>
```

### Set HTML

You need to create a div or section tag for your hero section, and add the attribute ```snake-parallax="hero"```. You do not need to create a special class, id, or css style for the section.

```
<section snake-parallax="hero">
  YOUR CONTENT
 </section>
```

Your parallax is ready!

# Credits

* reset.css: [source code](https://gist.github.com/DavidWells/18e73022e723037a50d6).
* Background image: Photo by [Pedro Lastra](https://unsplash.com/@peterlaster) on [Unsplash](https://unsplash.com).
