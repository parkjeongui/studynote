﻿get, post 방식의 request는 서버로 본인이 가지고 있는 data를 전달하기 위해서 사용된다. 데이터를 전달한다는 본질적인 측면에 있어서는 동일하지만, 차이점 또한 존재한다.

1.  GET

- \<form> 태그의 method 속성값으로 get을 입력한다.
- DB에 추가로 정보를 처리하지 않고, 저장된 Data를 단순히 요청하는 용도
-   URL 뒤에 파라미터(쿼리 문자열)로 데이터가 전송된다.
- ex) https://www.google.com/search?q=test (test라는 키워드로 검색하는 url)
- 데이터 전송량은 주소값+파라미터로 255자로 제한된다.

    
   <br>
   <br>
    
2.  POST
- \<form> 태그의 method 속성값으로 post를 입력한다.

-   서버에게 데이터 처리를 요청하는 방식

-   데이터가 request 객체 헤더정보에 포함되어 전송된다.

- URL에 데이터가 드러나지 않기 때문에 보안에 좀 더 유리함

- 한 번 요청시 데이터 전송량의 제한이 없음
