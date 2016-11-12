# Modal Component #

The modal component creates a modal window with the minimum cosmetics.


### Installation ###

```
npm install --save iotacss-components-modal
```


### Options ###

```sass
$iota-components-modal-namespace         : 'modal' !default;
$iota-components-modal-dialog-name       : 'dialog' !default;
$iota-components-modal-open-name         : 'is-modal-open' !default;
$iota-components-modal-active-name       : 'is-active' !default

$iota-components-modal-padding           : $iota-global-gutter-default !default;
$iota-components-modal-background        : rgba(0, 0, 0, 0.5) !default;
$iota-components-modal-dialog-background : rgb(255, 255, 255) !default;
```


### How to use it ###

```css
<body class="is-modal-open">

  <div class="c-modal">

    <div class="c-modal__dialog">

      <p>Hi, I am a modal</p>

    </div>

  </div>

</body>
```
