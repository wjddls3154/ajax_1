# ajax_1
### jQuery & Ajax 

## Ajax
jQuery 에서 비동기 통신을 할 수 있는 메소드 
- $.ajax() : 비동기 HTTP 요청
- $.get() : GET 방식의 HTTP 요청
- $.post() : POST 방식의 HTTP 요청
- $.getScript(),$getJSON() : GET 방식의 HTTP 요청 후, 정해진 양식으로 소스코드 전달받음
- .load() : HTML 코드를 읽어옴

Ajax 와 함께 사용할 수 있는 메소드
- done : 요청이 성공하면, done() 메소드로 데이터 전달
- fail : 요청이 실패하면, fail() 메소드로 실패 메시지 전달
- always : 요청의 성공여부와 관련없이 실행

Ajax 로드 할때, 아래 콜백함수를 넣게 되면 이 결과를 얻을수있다. 
responseText : 요청 결과
statusText : 요청의 상태
xhr : 요청한 오브젝트
xhr.status : 파일의 응답 상태
