# Modal Component #

The modal component creates a modal window with the minimum cosmetics.


### Installation ###

```
npm install --save iotacss-components-modal
```


### Options ###

```sass
$iota-component-modal-namespace         : 'modal' !default;
$iota-component-modal-dialog-name       : 'dialog' !default;
$iota-component-modal-open-name         : 'is-modal-open' !default;
$iota-component-modal-active-name       : 'is-active' !default

$iota-component-modal-padding           : $iota-global-gutter-default !default;
$iota-component-modal-background        : rgba(0, 0, 0, 0.5) !default;
$iota-component-modal-dialog-background : rgb(255, 255, 255) !default;
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
