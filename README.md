# Web_Crawling


* GET

  * URL에 쿼리 스트링(데이터)을 붙여서 서버에 전송

  * 데이터를 Header(헤더)에 포함하여 전송

  * URL에 정보들이 그대로 노출되기 때문에 POST 방식보다 상대적으로 보안에 취약

  * 캐싱이 가능

* POST

  * 데이터들을 URL뒤에 붙여서 서버로 보내는 것이 아닌 Body에 담아서 전송

  * 요청 헤더의 Content-Type에 콘텐츠 타입을 명시

  * 데이터들이 URL에 노출되지 않기 때문에 GET 방식보다 상대적으로 보안적
  
* 정적 수집
  * requests
  * 수집속도 빠름 (별도 페이지 조작 필요 X)
  * 파싱 : beautifulsoup
* 동적 수집
  * Selenium
  * 상대적으로 느림
  * 파싱 : Beautifulsoup / selenium
