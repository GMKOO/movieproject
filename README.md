# SpringBoot-Project-DREAM BOX
스프링 부트 + JSP 공공 API를 이용한 영화정보 업로드 및 영화 예매 사이트


## 🖥️ 프로젝트 소개
영화 예매 사이트
<br>

## 🕰️ 개발 기간
* 23.08.28일 - 23.09.26일

### 🧑‍🤝‍🧑 맴버구성
 
 - 팀원1 :  관모 - 공공 API를 이용한 영화 정보 로드 및 영화 정보 DB 테이블 설계, 영화 등록,수정,삭제 관리자페이지, 메인페이지
 - 팀원2 :  지은
 - 팀원3 :  채아
 - 팀원4 :  지윤
 - 팀원5 :  준식

### ⚙️ 개발 환경
- `Java 11`
- **Framework** : 전자 정부 프레임워크 Springboot(2.x)
- **Database** : MariaDB
- **ORM** : Mybatis

## 📌 개인 주요 기능 

#### 메인 페이지 - <a href="https://github.com/GMKOO/movieproject/tree/master/movie/src/main/webapp/WEB-INF/views" >상세보기 - 이동</a> 
- 메인 페이지 Ajax 동적생성을 통한 개봉영화, 개봉예정 영화 및 개봉일,예매순,누적관객순  실시간 정렬 기능 
- 더보기 기능으로 페이징 기능 구현
- mhome.jsp
  
#### 공공 API를 활용해 영화정보 로드 및 최신영화 업데이트 기능 - <a href="https://github.com/GMKOO/movieproject/tree/master/movie/src/main/java/com/movie/web/mhome" >상세보기 - 이동</a>
- 영화 정보 DB테이블 설계 및 영화정보 포스터,줄거리,러닝타임 등 정보성 데이터 자동 저장 구현
- mhome.folder

#### 영화 관리자 페이지 <a href="https://github.com/GMKOO/movieproject/tree/master/movie/src/main/webapp/WEB-INF/views/admin" >상세보기 - 이동</a>
- API를 활용한 관리자 영화 등록 서포트 시스템 구현
- 영화 정보 및 등록,수정,삭제 기능 구현
- movieupload.jsp,mvdetil.jsp,newmovie.jsp
