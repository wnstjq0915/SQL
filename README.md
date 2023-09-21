# SQL
[DB생성 및 개발환경세팅](rds로_데이터베이스생성.md)

## 문법 정리
- 23.06.11:  
[SQL의 기본](230611.md)
- 23.06.12:  
[select 관련 키워드/함수](230612_1.md)  
[문자열 관련 키워드/함수](230612_2.md)  
- 23.06.13:  
[datetime, 댓글테이블](230613_1.md)  
[join](230613_2.md)  
- 23.06.14:  
[인스타그램 DB 만들기 / 이미지 db 활용](230614_1.md)  
[일정공유앱 DB 만들기 / 친구와 팔로우 시스템](230614_2.md)  
- 23.06.15:  
[영화리뷰앱 DB 만들기 / FULLTEXT](230615.md)  

## 기능구현 팁
- 메인화면이 가장 많은 데이터들이 모여있기 때문에(조인을 많이함)  
가장 어려움. 나중에 하는거 추천
  
### 추천하는 순서
1. 회원가입 페이지
2. insert를 하는 페이지(즐겨찾기 페이지, 리뷰리스트 등)
3. select만 하는 페이지
4. join을 이용하여 select를 하는 페이지
