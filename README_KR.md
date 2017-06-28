# things-setting

## Global 설정을 load하고 global설정을 설정하는 dialog여는 컴포넌트

###  Example
```html
    <things-setting id="setting"></things-setting>

    <div class="buttons">
      <things-button color="green" target-id="setting">Setting</things-button>
    </div>
```

# things-setting-dialog

## setting 정보를 다이어로그로 표현하는 컴포넌트
```html
<things-setting-dialog id="dialog" no-cancel-on-outside-click dev-mode="[[devMode]]">
</things-setting-dialog>
```

devMode가 true인 경우 화면에 서버 baseUrl정보를 입력받는 input이 보여짐

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
