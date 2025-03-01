​

## oo 프로젝트 Front-end/Back-end 소개

- 프리미엄 코스메틱 브랜드 Aesop 클론 프로젝트
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.
  ​

### 개발 인원 및 기간

- 개발기간 : 2023/2/4 ~ 2012/2/17
- 개발 인원 : 프론트엔드 3명, 백엔드 2명
  FE - 김한솔, 이수민, 김수현(Project Manager)
  BE - 장주성(Product Manager), 최원경

- [백엔드 github 링크](https://github.com/wecode-bootcamp-korea/42-1st-ASAP-backend.git)
  ​

### 프로젝트 선정이유

- ​브랜드 전략에 맞게 사이트가 잘 구성되어있으며 디자인이 아름답고 세련됨

### 데모 영상(이미지 클릭)

[![ASAP 페이지 데모영상](http://img.youtu.be/oADqkrk6GPM/0.jpg)](https://youtu.be/oADqkrk6GPM)
​

## 적용 기술 및 구현 기능

### 적용 기술

​- FE : ​Javascript. reactJS, react-router-dom, SASS

- BE : Javascript, Node.js, Express.js, jwt, Bcrypt, My SQL

### 구현 기능

#### 공통

- 일반 회원가입 / 로그인
- 입력 값 유효성 검사
- 메뉴 네비게이션 바 (클릭 시 전체화면으로 구현)
- UseContext로 데이터 전역에서 사용
- 카트 개수 현황 조회
- 푸터 그리드로 구현
- 전체적으로 모두 백엔드에서 받은 데이터로 구현
  ​

#### 메인페이지

- 추천 상품 영상 삽입
- 추천 상품 캐러셀

#### 제품 리스트 페이지

- 백엔드에서 받은 상품 데이터 대로 출력
- 카테고리 전체보기 / 상세 카테고리 페이지 2개 레이아웃으로 구현
- 필터 기능으로 원하는 제품만 열람 가능
- 페이지 로딩 지연 시 버튼에 로딩 컴포넌트 구현
- 옵션 별로 라디오 버튼 생성
- 옵션 선택 후 버튼 클릭 시해당 값 백엔드로 전송

#### 상세 제품 페이지

- 옵션 별로 라디오 버튼 생성
- 옵션 선택 후 버튼 클릭 시 해당 값 백엔드로 전송
- 애니메이션 적용한 캐러셀 구현

#### 결제 페이지

- 마운트 애니메이션 적용
- 입력 창 애니메이션 적용
- 카트에 담은 제품 및 가격, 총합 , 개수 확인 가능
- 인풋 값 대로 백엔드에 데이터 전송

## Reference

- 이 프로젝트는 [Aesop](https://www.aesop.com/kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
  접기
