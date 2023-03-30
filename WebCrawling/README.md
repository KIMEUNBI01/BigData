# 크롤링(crawling) 
= 웹 페이지를 가져와서 데이터를 추출해 내는 방법

사용 라이브러리 : BeautifulSoup
  - HTML 문서를 탐색해 원하는 부분만 추출 가능
  - 문자열을 실제 HTML코드로 변환해줌

파이썬을 이용한 교촌치킨 매장 정보 크롤링
- URL: https://www.kyochon.com/shop/domestic.asp 
- 국내 모든 매장의 [매장이름, 시/도, 군/구, 주소] 네 가지 정보를 가져와 하나의 csv파일로 저장
