## 버튼을 누르면 바로바로 띄워주는 서비스를 사용할 것

- 영화명
- 감독명
- 개봉연도 -> 조회시작, 조회종료가 가능
- 국가별 조회가 가능 -> 국적으로 조회 가능, 

# 한국영화진흥위원회 영화 목록 API 사용방법
## 요청 인터페이스
- key	: string(필수)
	발급받은키 값을 입력합니다.
- curPage: string
	현재 페이지를 지정합니다.(default : “1”)
- itemPerPage: string
	결과 ROW 의 개수를 지정합니다.(default : “10”)
- movieNm: string
	영화명으로 조회합니다. (UTF-8 인코딩)
- directorNm: string
	감독명으로 조회합니다. (UTF-8 인코딩)
- openStartDt: string
	YYYY형식의 조회시작 개봉연도를 입력합니다.
- openEndDt: string
  YYYY형식의 조회종료 개봉연도를 입력합니다.
- prdtStartYear: string
  YYYY형식의 조회시작 제작연도를 입력합니다.
- prdtEndYear: string	  
  YYYY형식의 조회종료 제작연도를 입력합니다.
- repNationCd: string
  N개의 국적으로 조회할 수 있으며, 국적코드는 공통코드 조회 서비스에서 “2204” 로서 조회된 국적코드입니다. (default : 전체)
- movieTypeCd: string
  N개의 영화유형코드로 조회할 수 있으며, 영화유형코드는 공통코드 조회 서비스에서 “2201”로서 조회된 영화유형코드입니다.(default: 전체)