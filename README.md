# Modal Component #

The modal component creates a modal window with the minimum cosmetics.


### Installation ###

```
npm install --save iotacss-modal
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)


### Options ###

```
$iota-modal-background          : #FFFFFF !default;
$iota-modal-padding             : 20px !default;
$iota-modal-backdrop-background : rgba(0, 0, 0, 0.5) !default;
```


### How to use it ###

```
<body class="is-modal-open">

  <div class="c-modal">

    <div class="c-modal__dialog">

      <p>Hi, I am a modal</p>

    </div>

  </div>

  <div class="c-modal-backdrop"></div>

</body>
```
