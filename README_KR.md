# things-image-selector

## 파일 선택용 컴포넌트. 해당 컴포넌트는 Event `things-image-selector-toggle`을 통하여 `things-dialog-manager`로 Event를 전송하여 `things-image-selector-dialog`를 화면에 표현한다.

Example:

```html
      <things-image-selector
        resource-url="attachments">
      </things-image-selector>
```

*****
</br></br>


## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

그리고, 아래의 방법을 통해 실행할 수 있다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-image-selector`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-image-selector/`를 통해 이를 미리 확인할 수 있다. 
