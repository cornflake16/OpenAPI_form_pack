# **오픈 API 양식 샘플 코드**


<pre>(개요)<br>&nbsp;&nbsp;&nbsp;Open API를 활용하기 위한 샘플 코드 모음입니다.</pre>

## 공공데이터포털 (http://data.go.kr)
	 

 - (사용법)
    1. 공공데이터포털 홈페이지에서 API를 신청(현시점 기준 신청하고 1~2시간 후에 데이터를 요청할 수 있음)
    2. 파일을 열어 'SERVICE_KEY' 변수에 본인이 발급받은 공공데이터포털 API 인증키(UTF-8)입력 (ex. "=인증키")
    3. 홈페이지에서 제공하는 공식 API 문서를 확인하고 본인이 원하는 요청 값이 코드에 포함이 안 돼 있다면 코드 분석 후에 추가(재량)
  
 - (참고)
    - 파일의 확장자를 확인해서 본인의 사용할 언어와 일치하는지 확인합니다. 파일마다 샘플 출력 방식이 다를 수 있습니다.
    -  마지막 commit 시점을 기준으로 올바르게 실행하는지 확인한 것이므로 영원히 동작한다는 보장은 없습니다.
    
    
 - (파일 목록)  
	- [CoronaKoreaStatus.java](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/CoronaKoreaStatus.java): 코로나 국내 발생 현황_XML 파싱(DOM 방식)_주석 추가 예정
    
     &nbsp; => [**[참고 문서]**](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/docs/01.보건복지부_OpenAPI활용가이드_코로나바이러스감염증_감염현황%20조회%20서비스_v0.3%20(11).docx) [**[참고 페이지]**](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15043376)

	- [CoronaRegionalStatus.java](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/CoronaRegionalStatus.java): 코로나 시·도 발생 현황_XML 파싱(DOM 방식)_주석 추가 예정
    
     &nbsp; => [**[참고 문서]**](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/docs/03.보건복지부_OpenAPI활용가이드_코로나바이러스감염증_시도발생_현황%20조회%20서비스_v0.3%20(2).docx) [**[참고 페이지]**](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15043378)

	- [CoronaNationalStatus.java](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/CoronaNationalStatus.java): 코로나 해외 발생 현황_XML 파싱(DOM 방식)_주석 추가 예정
    
     &nbsp; => [**[참고 문서]**](https://github.com/cornflake16/OpenAPI_form_pack/blob/main/docs/04.보건복지부_OpenAPI활용가이드_코로나바이러스감염증_해외발생_현황%20조회%20서비스_v0.3.docx) [**[참고 페이지]**](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15043379)
<br>
&nbsp;-> 파일을 각각 하나씩 테스트하려면 각 파일에 있는 모든 메서드와 변수를 static으로 선언하고 main메서드 주석 해제
