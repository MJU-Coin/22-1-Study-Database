# Chap4. 테이블 설계의 기초
테이블의 개념과 정규형

## 과제
1. 데이터 타입 조사(MySQL 8.0 기준)
2. 제약 조건 조사(MySQL 8.0 기준)
3. KEY 종류에 대해서 조사


## Entity Relationship Diagram
- 요소
  1. Entity : 시스템화 하고자 하는 사건, 사물
  2. Relataionship : 엔티티, 어트리뷰트 간의 관계
  3. Attribute : 엔티티, 관계성의 성질을 나타내는 더 이상 쪼갤 수 없는 정보의 단위
- 데이터 모델링 3단계
  1. 개념적 모델링 : 추상화 수준이 높음.
  2. 논리적 모델링 : key, attribute, relationship 등을 정확히 표현
  3. 물리적 모델링 : 실제로 데이터베이스에서 사용할 수 있도록 설계

### Entity
- 하나의 객체를 표현하기 위한 테이블
- 특징
  - 식별자 존재
  - 2개 이상의 인스턴스가 존재
  - 속성 존재
  - 하나 이상의 관계 존재
- 종류
  - 유, 무형으로 분류
    - 유형 엔티티
    - 개념 엔티티
    - 사건 엔티티
  - 발생 시점으로 분류
    - 기본 엔티티 : 고객, 상품
    - 중심 엔티티 : 주문, 취소
    - 행위 엔티티 : 주문 내용, 취소 내용
### Relationship
- Entity들간의 관계를 표현
- 두 개의 Entity 사이에는 여러 가지 관계가 존재할 수 있다.
- 관계 차수(Cardinality)
  - 두 Entity 사이의 관계를 표현하는 방식
  1. 1:1
  2. 1:n
  3. n:m  
### Diagram