<!-- <div class="con"> -->

# Oracle Study

## 기본 개념
- MySQL과 대부분 비슷하지만 차이점이 존재
- 공공기관, SI 프로젝트에서 많이 사용됨
- 다량의 데이터 처리를 위한 쿼리 작성 능력이 필요
- 쿼리 튜닝, DB이관, 개발을 위한 쿼리 작성(CRUD)
- DBA 등 관련 능력 배양시 연봉 협상 능력이 상승

## CRUD 
- creat table
- insert, update, delete, select 등 기본 쿼리 작성 방법은  MySQL과 거의 동일
- 차이점 및 특화된 부분에 대한 추가 학습을 통해 실무 능력 향상 도모

### Query
- Primary Key 설정
  - CONSTRAINT PK_TOPIC PRIMARY KEY(ID) => id라는 컬럼을 프라이머리 키로 지정
  - unique가 기본 설정됨
  - 검색에 있어서 속도의 차이가 있음
  
- Sequence
  - CREATE SEQUENCE SEQ_TOPIC => SEQUENCE 생성
  - SEQ_TOPIC.NEXTVAL => 이전 SEQUENCE 값에서 1만큼 증가한 값
  - SEQ_TOPIC.CURRVAL => 현재 SEQUENCE 값
  - SELECT SEQ_TOPIC.CURRVAL FROM DUAL; => 가상 테이블에서 현재 SEQUENCE 값을 불러옴
    - SEQUENCE 값을 한번만 불러올 수 있음
    
                                 



---


<!-- </div> -->
