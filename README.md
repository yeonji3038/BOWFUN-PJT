# 🐾 BOWFUN

#### 반려동물 유치원, 병원 위치와 용품을 안전하고 간편한 결제 시스템을 제공하는 종합 쇼핑몰 플랫폼

> 2023.10.12 ~ 2023.11.03

<br>

---

1. **[웹 서비스 소개](#1-웹-서비스-소개)**
2. **[기술 스택](#2-기술-스택)**
3. **[주요 기능](#3-주요-기능)**
4. **[시스템 아키텍쳐](#4-시스템-아키텍쳐)**
5. **[서비스 화면](#5-서비스-화면)**
6. **[개발 팀 소개](#6-개발-팀-소개)**
   
## 1. 웹 서비스 소개

### ✨ BOWFUN: 반려동물을 위한 통합 쇼핑 & 위치 기반 서비스 플랫폼

반려동물 유치원, 병원, 호텔 정보를 찾고
용품까지 안전하게 구매하고 싶었던 경험, 있으신가요?

BOWFUN은 지도 기반 정보 탐색부터 상품 구매 및 결제까지
반려동물과 함께하는 삶을 더 간편하고 안전하게 만들어드립니다.

#### 🌟 BOWFUN만의 특별함

    - 하나의 플랫폼으로 모두 해결: 병원, 유치원, 호텔 정보 검색부터 용품 쇼핑까지 한번에
    - 지도 기반 서비스: Kakao Map API를 활용하여 주변 서비스를 직관적으로 확인
    - 안전한 결제 시스템: 결제 API와 연동된 신뢰도 높은 쇼핑 환경 제공

#### 💡 이런 분들에게 완벽해요

    - 반려동물 용품과 지역 서비스를 함께 관리하고 싶은 보호자
    - 병원/유치원/호텔 등의 위치와 상세 정보를 한눈에 보고 싶은 사람
    - 간편한 결제 시스템과 통합 쇼핑 경험을 원하는 사용자

<div id="기술-스택"></div>
<br>

## 2. 기술 스택
 
### **Backend**

<img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=IntelliJ IDEA&logoColor=white"> <img src="https://img.shields.io/badge/Java 17-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/SpringBoot 3.4.3-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white"> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON Web Tokens&logoColor=white"> <br> <img src="https://img.shields.io/badge/Lombok-BC4521?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Redis 7.4.2-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/MySQL 8.0.40-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/P6Spy-0A0A0A?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/External API-4B5563?style=for-the-badge&logo=code&logoColor=white">

### **Frontend**

<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/Kakao Map API-FFCD00?style=for-the-badge&logo=kakao&logoColor=black">


### **Communication**

<img src="https://img.shields.io/badge/Git(Gitlab)-FCA121?style=for-the-badge&logo=Gitlab&logoColor=white"> <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Mattermost-0058CC?style=for-the-badge&logo=Mattermost&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">


<br>
<div id="주요-기능"></div>

## 3. 주요 기능

|                기능                | 내용                                                                                                                                                                                                      |
| :--------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      **월세 자동 청구 및 관리**      | 설정된 날짜에 월세 입금 내역이 자동으로 반영됩니다. 세입자는 자신의 월세 납부 내역을 조회할 수 있으며, 집주인은 모든 세입자별로 월세 수금 상태를 임대인 대시보드에서 모니터링할 수 있습니다.                               |
|    **월세 연체 방지 및 미납액 관리**   | 월세 납부 일정을 미리 알려주는 문자 알림 서비스와 연체 시 경고 알림을 자동 발송합니다.                         |
|        **세입자 편의 기능**         | 집 유지보수 요청 기능을 통해 집주인에게 수리 요청(누수/누전 문제 등)을 보내고 처리 진행 상태를 조회할 수 있습니다.     
|        **월세 자동이체 기능**         | 임차인이 계좌 정보를 등록하고 기간 및 납부일을 설정하면, 설정한 날짜에 월세가 자동으로 이체됩니다.

<br/>

<div id="시스템-아키텍처"></div>
<br>

## 4. 시스템 아키텍쳐

<br>

![System Architecture](/docs/System_Architecture.jpg)


<br>
<div id="서비스-화면"></div>

## 5. 서비스 화면

### 로그인 & 회원가입
| <img src="docs/screenshots/로그인.jpg" width="200"> | <img src="docs/screenshots/회원가입.gif" width="200"> |
|:---:|:---:|
| 로그인 화면 | 회원가입 화면 |

- JWT 기반 인증 시스템 구현
- 임대인/임차인 구분하여 회원가입 지원

--- 

### 임대인 서비스

### 1. 임대인 대시보드
| <img src="docs/screenshots/임대인_홈화면.gif" width="200"> |
|:---:|
| 임대인 대시보드 |

- 월별 수입 통계 및 연체 현황 분석
- 최근 문의 내역 실시간 확인

### 2. 세대 관리
| <img src="docs/screenshots/임대인_세대관리.gif" width="200"> | <img src="docs/screenshots/임대인_계약코드생성.gif" width="200"> |
|:---:|:---:|
| 세대 관리 | 계약코드 발행 |

- 도로명 주소 기준 건물 등록 및 관리
- 세대별 입주/공실 현황 실시간 확인
- 카카오 맵 API 활용해해 등록한 건물의 위치 조회
- 10분간간 유효 계약코드 발행 시스템

### 3. 임차인 관리
| <img src="docs/screenshots/임대인_임차인%20관리.gif" width="200"> | <img src="docs/screenshots/임대인_문의.gif" width="200"> | <img src="docs/screenshots/임대인_공지사항.gif" width="200"> |
|:---:|:---:|:---:|
| 임차인 관리 | 문의 관리 | 공지사항 전달 |

- 세입자별 계약 정보 및 월세 납부 이력 관리
- 유지보수 요청 실시간 확인 및 처리
- 건물별 공지사항 전달 시스템

---

### 임차인 서비스

### 1. 임차인 대시보드
| <img src="docs/screenshots/임차인_홈화면.gif" width="200"> |
|:---:|
| 임차인 대시보드 |

- 월세 납부 현황 및 공지사항 실시간 확인

### 2. 월세 관리 화면
| <img src="docs/screenshots/월세납부내역.gif" width="200"> |
|:---:|
| 월세 관리 화면 |

- 월세 납부 내역 조회
- 보증금 현황 확인

### 3. 월세 납부 화면
| <img src="docs/screenshots/자동이체.gif" width="200"> | <img src="docs/screenshots/월세직접납부.gif" width="200"> |
|:---:|:---:|
| 자동이체 설정 | 월세 직접 결제 |

- 계좌등록과 날짜설정으로 자동이체 등록
- 자동이체 등록 여부 확인

### 4. 문의 등록
| <img src="docs/screenshots/문의등록.gif" width="200"> |
|:---:|
| 문의 등록 |

- 임차인이 임대인에게 궁금한 점이나 요청사항을 작성하여 전달


### 5. 공지사항 조회
| <img src="docs/screenshots/임차인_공지사항.gif" width="200"> |
|:---:|
| 공지사항 조회 |

- 임대인이 해당 건물에 작성한 공지사항 조회

<br>
<div id="개발-팀-소개"></div>

## 6. 개발 팀 소개

---

| ![곽희섭](https://avatars.githubusercontent.com/HuiSeopKwak) | ![김유진](https://avatars.githubusercontent.com/zladb) | ![김성민](https://avatars.githubusercontent.com/ssm-kim) | ![김민주](https://avatars.githubusercontent.com/hong00z) | ![이지현](https://avatars.githubusercontent.com/ww42777) | ![최연지](https://avatars.githubusercontent.com/yeonji3038)
|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| 곽희섭 ([@HuiSeopKwak](https://github.com/HuiSeopKwak)) | 김유진 ([@zladb](https://github.com/zladb)) | 김성민 ([@ssm-kim](https://github.com/ssm-kim)) | 김민주 ([@hong00z](https://github.com/hong00z)) | 이지현 ([@ww42777](https://github.com/ww42777)) | 최연지 ([@yeonji3038](https://github.com/yeonji3038)) | 
| Leader / Back End | Back End | Infra / Back End | Front End | Front End | Front End |

<br />
<div id="산출물"></div>

## 📝 산출물

---

### 1. [기능 명세서](https://gravel-seagull-322.notion.site/1afef7bc762580fbaa03df1df705095b?pvs=4)

### 2. [와이어 프레임](https://www.figma.com/design/Zf5XDzkeLFFUZUo6hddF9C/%EC%9B%94%EA%B0%84-ZIP?node-id=0-1&p=f&t=TrUvVEuFhH5ZNduj-0)

### 3. [API 명세서](https://gravel-seagull-322.notion.site/API-1b4ef7bc76258019a0a4f6f80af26682?pvs=4)

### 4. [ERD](/docs/erd.png)

### 5. [포팅매뉴얼](/exec/포팅메뉴얼/)

### 6. [최종발표](/exec/월간ZIP_발표.pdf)
