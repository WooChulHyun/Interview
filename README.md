# 인터뷰 정리

## HTML

### **DOCTYPE이란?**

DOCTYPE은 document type의 약어입니다. DOCTYPE은 항상 **DTD(Document Type Definition)**와 관련됩니다.

DTD는 특정 문서가 어떻게 구성되어야 하는지 정의합니다(예시: button은 span을 포함할 수 있지만, div는 포함할 수 없다.), 반면, DOCTYPE은 문서가 대략 존중할만한 DTD를 선언합니다. (예시: 이 문서는 HTML DTD를 존중한다.)

html문서 작성시 브라우저에게 버전을 알려주기 위하여 맨 처음에 html 버전을 표시하는데 이를 "DTD = document type definition = DOCTYPE = 독타입"이라고 부른다.

현재의 html5 버전의 독타입은 <!DOCTYPE html>로 표시한다.

위 html문서의 소스코드에서 보는 것처럼 맨 처음에 <!DOCTYPE html>를 표시하여 웹브라우저가 이 소스코드를 읽을때 이 웹문서가 html5로 작성되었음을 알려 준다.

웹 페이지의는 DOCTYPE 선언이 필요합니다. 유저 에이전트에게 문서가 존중하는 HTML 사양의 버전을 알리는데 사용됩니다.
