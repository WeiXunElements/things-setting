# things-setting

## This is a component that extracts global variables from the browser repository and stores and modifies them in the browser repository.

###  Example
```html
    <things-setting id="setting"></things-setting>

    <div class="buttons">
      <things-button color="green" target-id="setting">Setting</things-button>
    </div>
```

# things-setting-dialog

## This is a component that presents the setting information in a dialogue.
```html
<things-setting-dialog id="dialog" no-cancel-on-outside-click dev-mode="[[devMode]]">
</things-setting-dialog>
```

If devMode is true, the input which receives the server baseUrl information is shown on the screen.

```js
this.$.dialog.open();
```

*****
</br></br>


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-setting/`, where `things-setting` is the name of the directory containing it.
