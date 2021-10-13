# eliancodes-bg

The ElianCodes Background as a CSS Houdini Paint Worklet

## installation

### NPM

```sh
npm i eliancodes-bg
```

### CDN

Still waiting for the package to show up on any CDN. Preferably use this method since the package is very small and easy to use.

## Usage

### Properties

`--color-for-bg`

takes in a color and uses it to render the background

### Example

```html
<html class="bg">
    <body>
        <style>
            .bg {
                --color-for-bg: lightgreen;
                background-image: Paint(eliancodes-bg);
            }
        </style>
        <script>
            CSS.paintWorklet.addModule('cdn_link_here')
        </script>
    </body>
</html>
```
