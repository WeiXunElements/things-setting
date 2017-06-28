# things-setting

## 이는 전역변수를 브라우저 저장소에서 추출하거나 브라우저 저장소에 저장하고 수정하는 컴포넌트이다.

###  Example
```html
    <things-setting id="setting"></things-setting>

    <div class="buttons">
      <things-button color="green" target-id="setting">Setting</things-button>
    </div>
```

# things-setting-dialog

## 이는 setting 정보를 다이얼로그로 표현하는 컴포넌트이다.
```html
<things-setting-dialog id="dialog" no-cancel-on-outside-click dev-mode="[[devMode]]">
</things-setting-dialog>
```

devMode가 true인 경우, 화면에 서버 baseUrl 정보를 입력 받는 input이 보여진다.

```js
this.$.dialog.open();
```

*****
</br></br>


## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-setting`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-setting/`를 통해 이를 미리 확인할 수 있다. 
