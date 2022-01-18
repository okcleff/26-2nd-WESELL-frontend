# 🚀 WESELL | 위셀
- [WeSell 시연 영상](https://youtu.be/-U2m9llGnuI)

## 팀명 : WESELL
### [KREAM](https://kream.co.kr/)을 모티브로 한 팀 프로젝트
- 초기 세팅부터 직접 구현했으며 실제 사이트와 같은 수준의 개발하려 팀원들과 소통하며 작업한 프로젝트

### 프로젝트 선정이유

- 경매 시스템 및 구매 및 판매 시스템이 체계적으로 잘 갖춰져있었고 스타일페이지로 인한 소비자들과의 소통을 할 수 있었고 각 페이지마다 연결점이 많아서 협업시스템과 로직구현을 좀 더 연습하게 할 수 있을 것 같아서 프로젝트를 선정하게 되었습니다

## 👫 개발기간 및 팀원
- 기간: 2021-11-15 ~ 2021-11-26
- Front-end[4명]: 강지원, 안재우, 옥원철, 전지완
- Back-end[2명]: 박대현, 허규빈

## 적용 기술

- Front-end: HTML5, CSS3, React, styled-components, JSX, React-Router v6
- Back-end: Python, django, MySQL, AWS(EC2, RDS, S3), Docker
- 협업툴: Trello, Slack, Notion, Github, dbdiagram, postman

## 구현 기능 및 개인 역할

> **옥원철**
- 담당 화면 및 기능
  - 메인 화면 레이아웃 구성
    - 최상단 배너 이미지 슬라이드 기능(라이브러리 미사용, 각 슬라이드의 index를 state로 관리)
    - Array 관련 메소드(slice, map)를 활용하여 더보기 버튼 구현
    - React Router v6의 useNavigate hook을 활용하여 제품 이미지 클릭시 상세 페이지로 이동
  - 상세페이지 내 제품 구매 및 판매 기능
    - 즉시 구매/판매: 제시 금액으로 구매/판매 주문 POST 요청, 동시에 (거래가 체결되었으므로) 경매 목록에서 해당 금액 DELETE 요청
    - 구매/판매 입찰: 희망하는 입찰가를 입력하여 POST 요청

## 레퍼런스
- 이 프로젝트는 <u>[KREAM](https://kream.co.kr/)</u> 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
