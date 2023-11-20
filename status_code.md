# 상태코드

### HTTP 응답 상태 코드

1. 1xx(Informational)<br>
&emsp;- 서버에서 요청 수신<br>
&emsp;- 현재 처리중 or 정보를 알려줄 팔요줄 경우 없을때<br>

2. 2xx(Successful)<br>
&emsp;- 요청이 성공적으로 완료됨<br>

3. 3xx(Redirection)<br>
&emsp;- 요청을 마치기위해 추가 동작이 필요한 경우<br>

4. 4xx(Client Error)<br>
&emsp;- 400(Bad Request) : 요청 오류<br>
&emsp;- 401(Unauthorized) : 권한 없음<br>
&emsp;- 403(Forbidden) : 접근 금지<br>
&emsp;- 404(Not Found) : 잘못된 URL 요청 or 리소스 없을때<br>

4. 5xx(Server Error)<br>
&emsp;- 500(Internal Server Error) : 서버 응답 없음<br>
&emsp;- 502(Bad Gateway) : 게이트워이, 프록시 작업시 잘못된 응답 수신<br>
&emsp;- 503(Service Unavailable) : 서비스 과부화, 서비스 중단<br>
