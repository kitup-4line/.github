<div align="center">

# KitUp
    
<img width="500" alt="image" src="https://github.com/user-attachments/assets/00acb040-3d81-43ac-8df9-7279b2ee34b6" />

### 신메뉴 출시 전, 가능성을 먼저 확인하다.

**예비 요식업 창업자를 위한 AI 기반 메뉴 테스트 서비스**

메뉴의 원가부터 판매 성과, 고객 반응까지  
실제 판매 전에 검증하고 개선 방향을 발견하는 서비스입니다.


[**서비스 바로가기**](https://kitup-eta.vercel.app/) | [**Frontend**](https://github.com/kitup-4line/kitup-frontend) | [**Backend**](https://github.com/kitup-4line/kitup-backend)

</div>

<br>


## 프로젝트 소개

**KitUp**은 예비 요식업 창업자가 공유주방에서 신메뉴를 판매하기 전, 메뉴의 수익성과 운영 가능성을 검증할 수 있도록 돕는 서비스입니다.

레시피를 직접 입력하거나 AI를 통해 원가를 추정하고, 판매 데이터와 고객 리뷰를 분석하여 데이터 기반의 의사결정을 지원합니다.

이번 해커톤 MVP에서는 실제 판매 대신 60건의 가상 주문 데이터와 연계된 실제 고객 리뷰를 활용하여 메뉴 테스트부터 분석 리포트까지의 과정을 구현했습니다.

<br>

## 기획 배경

### 감이 아닌 데이터로, 신메뉴의 가능성을 검증하다.

예비 창업자는 정확한 원가를 파악하기 어렵고, 매출과 실제 남는 이익을 구분하거나 고객 반응을 개선 방향으로 연결하는 데 어려움을 겪습니다.

KitUp은 복잡한 원가 계산의 부담을 줄이고, 판매 데이터와 고객 피드백을 이해하기 쉬운 분석 결과로 제공하여 보다 합리적인 창업 의사결정을 돕습니다.

<!-- IR Deck 이미지 삽입 위치: 문제 정의 및 솔루션 -->

<br>

## 서비스 이용 흐름

```text
내 테스트
    ↓
메뉴 등록 및 원가 산정
    ↓
운영 대시보드
    ↓
분석 리포트
    ↓
개선 방안 확인
```

<!-- IR Deck 이미지 삽입 위치: 서비스 이용 흐름 또는 전체 플로우 -->

<br>




## 주요 기능

### 01. 내 테스트

내 메뉴의 테스트 기록을 한곳에서 관리합니다.

- **작성 중** — 메뉴 정보를 이어서 작성합니다.
- **운영 중** — 매출과 수익성을 확인하고 고객 반응을 살펴봅니다.
- **완료** — 분석 리포트와 개선안을 확인합니다.



### 02. 메뉴 등록 및 원가 산정

**예비 창업자의 진입 장벽을 낮추는 2-Track 원가 산정 방식**

- **메뉴 기본 정보 입력**  
  메뉴명, 판매가, 포장비와 운영 시간대를 입력해 테스트를 준비합니다.

- **AI 원가 추정**  
  원가 계산이 낯설다면 구성 재료를 입력해 AI가 추정한 원가를 확인하고 수정합니다.

- **직접 입력**  
  사용하는 재료와 수량, 비용을 직접 입력해 레시피에 맞는 원가를 설정합니다.

  

### 03. 운영 대시보드

**테스트 판매 결과를 단순 매출이 아니라 “남는 돈”으로 보여준다**

- **4대 지표 확인**  
  완료 주문 수와 매출, 총공헌이익과 건당 공헌이익으로 판매 성과와 수익성을 확인합니다.

- **시간대별 판매**  
  주문이 몰리는 시간대를 확인해 필요한 인원과 재료를 미리 준비합니다.

- **채널별 판매 비교**  
  판매 비율과 건당 공헌이익을 비교해 어느 판매 방식에서 이익이 더 남는지 확인합니다.

- **주문 관리**  
  개별 주문의 상세 정보와 고객 리뷰를 함께 확인합니다.



### 04. 분석 리포트

**판매데이터를 바탕으로 무엇을 해야 하는지를 보여줍니다**

- **수익 구조 분석**  
  매출에서 비용을 제외한 이익을 확인하고, 어떤 비용이 수익에 영향을 주는지 살펴봅니다.

- **고객 반응분석 (VOC)**  
  고객이 만족한 점과 개선이 필요한 점을 정리하고, 근거가 되는 리뷰를 함께 보여줍니다.

- **개선 제안 보고서**  
  수익 분석과 고객 리뷰를 바탕으로 개선할 내용과 효과를 확인할 방법을 제안합니다.

분석에서 얻은 인사이트를 개선 실험에 적용하고, 새로운 테스트로 변화된 결과를 확인합니다.


<br>


## 비즈니스 모델 및 지속 가능성

예비 창업자를 위한 검증팩과 창업 지원 기관을 위한 라이선스로 수익을 확보할 계획입니다.

- **기관 라이선스 — 입주팀 1팀당 연 100,000원**  
  창업 지원 기관이 참가팀의 테스트 결과와 성과보고를 한 화면에서 관리합니다. 참가 창업자는 무료로 이용합니다.

- **창업 검증팩 — 1회 39,000원**  
  개별 예비 창업자나 지원 프로그램 수료 후 추가 검증이 필요한 팀에 분석 리포트, 개선 제안과 2차 테스트 1회를 제공합니다.

- **신메뉴 테스트 구독 — 가격 미정**  
  창업 후에도 신메뉴를 출시하기 전에 수익성과 고객 반응을 반복해서 검증할 수 있도록 월 구독으로 확장할 계획입니다.

> 위 가격과 제공 내용은 향후 사업 모델에 대한 기획안입니다.

<br>

## 활용성 및 확장성

예비 창업자의 메뉴 검증에서 시작해 운영 매장과 프랜차이즈로 활용 범위를 넓힐 계획입니다.

- **예비 창업자 — 실제 판매 결과로 메뉴 검증**  
  판매 데이터를 엑셀로 업로드하고, 창업 지원 기관이 참가팀의 테스트 결과를 함께 관리할 수 있도록 확장합니다.

- **운영 매장 — 신메뉴와 기존 메뉴 비교**  
  신메뉴의 판매 성과를 기존 메뉴와 비교하고, POS와 배달앱을 연동해 판매 데이터를 불러올 수 있도록 확장합니다.

- **프랜차이즈 — 직영점 검증 후 가맹점 도입**  
  본부 대시보드에서 직영점의 테스트 결과를 확인하고, 검증한 메뉴를 가맹점에 도입할 수 있도록 확장합니다.

> 향후 확장 계획입니다.

<br>

## 기대하는 변화

가게를 열기 전, 작은 판매 경험으로 메뉴를 점검하고 개선할 수 있도록 돕습니다.

- **판매 전 수익성 확인**  
  판매가와 예상 비용을 바탕으로 메뉴 한 건당 이익을 확인합니다.

- **판매 결과와 고객 반응에 근거한 판단**  
  판매 성과와 리뷰를 함께 살펴 유지할 강점과 개선할 문제를 찾습니다.

- **반복 테스트를 통한 개선**  
  메뉴, 가격과 포장을 바꾼 뒤 다시 테스트해 개선 전후의 결과를 비교합니다.

> 현재 MVP는 가상 주문과 공개 리뷰를 활용해 분석 과정을 시연합니다.

<br>

## 안정성 및 예외 처리

| 상황 | 대응 |
|---|---|
| 잘못된 입력 | 입력값을 검증하고 오류 내용을 안내합니다. |
| 리뷰 없음 | 매출과 비용 데이터를 바탕으로 개선안을 생성합니다. |
| AI 호출 실패 | 실패 상태를 안내하고 재시도를 지원합니다. |
| 개선안 생성 실패 | 완료된 리뷰 분류는 유지하고 개선안 생성만 재시도합니다. |
| 잘못된 AI 응답 | 응답 형식을 검증하고 원문과 일치하지 않는 인용을 제외합니다. |

<br>

## Team KitUp

<table>
<tr>
<th align="center">Frontend</th>
<th align="center">Frontend</th>
<th align="center">Backend</th>
<th align="center">Backend</th>
</tr>
<tr>
<td align="center"><a href="https://github.com/ssseeo"><img src="https://github.com/ssseeo.png" width="100" /></a></td>
<td align="center"><a href="https://github.com/hyunaway"><img src="https://github.com/hyunaway.png" width="100" /></a></td>
<td align="center"><a href="https://github.com/jominho37"><img src="https://github.com/jominho37.png" width="100" /></a></td>
<td align="center"><a href="https://github.com/choosooa"><img src="https://github.com/choosooa.png" width="100" /></a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/ssseeo"><b>김서윤</b></a></td>
<td align="center"><a href="https://github.com/hyunaway"><b>이현우</b></a></td>
<td align="center"><a href="https://github.com/jominho37"><b>조민호</b></a></td>
<td align="center"><a href="https://github.com/choosooa"><b>조수아</b></a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/ssseeo">@ssseeo</a></td>
<td align="center"><a href="https://github.com/hyunaway">@hyunaway</a></td>
<td align="center"><a href="https://github.com/jominho37">@jominho37</a></td>
<td align="center"><a href="https://github.com/choosooa">@choosooa</a></td>
</tr>
</table>

<br>

## Tech Stack

### Environment

![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django Q2](https://img.shields.io/badge/Django_Q2-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Communication

![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

<div align="center">

# KitUp

### 팔기 전에 검증하고, 데이터로 개선하다.

**더 나은 메뉴를 위한 첫 번째 테스트**

</div>
