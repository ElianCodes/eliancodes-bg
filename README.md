# eliancodes-bg

The ElianCodes Background as a CSS Houdini Paint Worklet

## installation

### NPM

```sh
npm i eliancodes-bg
```

### CDN

[https://unpkg.com/eliancodes-bg@0.0.1/index.js](<https://unpkg.com/eliancodes-bg@0.0.1/index.js>)

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
            CSS.paintWorklet.addModule('https://unpkg.com/eliancodes-bg@0.0.1/index.js')
        </script>
    </body>
</html>
```
