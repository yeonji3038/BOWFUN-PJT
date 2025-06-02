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

<img src="https://img.shields.io/badge/STS4-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Framework-6DB33F?style=for-the-badge&logo=spring&logoColor=white">

### **Database**

<img src="https://img.shields.io/badge/Oracle%20DB-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/SQL%20Developer-008000?style=for-the-badge&logo=databricks&logoColor=white">


### **Communication**

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">


<br>
<div id="주요-기능"></div>

## 3. 주요 기능

|                기능                | 내용                                                                                                                                                                                                      |
| :--------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      **상품 거래 및 결제 시스템**      | 사용자는 반려동물 용품을 선택하고, 장바구니 담기부터 결제까지 한 번에 진행할 수 있습니다. KG이니시스 결제 시스템을 도입하여 신뢰도 높은 안전한 결제가 가능합니다.                              |
|      **게시판 / 공지사항 기능**   | 	사용자 간 정보 공유를 위한 커뮤니티 기능과 운영자가 전달하는 공지사항을 게시할 수 있는 기능을 제공합니다.                         |
|      **병원 / 유치원 / 호텔 / 펜션 위치 확인**         | Kakao Map API를 활용해 주변 반려동물 관련 시설(병원, 유치원, 호텔, 펜션 등)의 위치를 지도에서 직관적으로 확인할 수 있습니다. 
|        **카카오 로그인 / 회원가입**         | 	카카오 OAuth 인증을 이용한 간편 로그인 및 회원가입 기능을 제공하여 사용자 접근성과 편의성을 높였습니다.

<br/>

<div id="시스템-아키텍처"></div>
<br>

## 4. 시스템 아키텍쳐

<br>

<a href="#"><img src="./코드/ww.png" alt=""/><br />


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
<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="#"><img src="./코드/yj.png" width="100px;" alt=""/><br />
        <sub><b>FullStack : 팀장 최연지
      </td>
      <td align="center">
        <a href="#"><img src="./코드/dw.png" width="100px;" alt=""/><br />
        <sub><b>FullStack : 이동운
      </td>
      <td align="center">
        <a href="#"><img src="./코드/cb.png" width="100px;" alt=""/><br />
        <sub><b>FullStack : 전찬범
      </td>
      <td align="center">
        <a href="#"><img src="./코드/jh.png" width="100px;" alt=""/><br />
        <sub><b>FullStack : 황지현
      </td>
    </tr>

  </tbody>
</table>

<br/>

## 📝 산출물

---

### 1. [PPT](https://gravel-seagull-322.notion.site/1afef7bc762580fbaa03df1df705095b?pvs=4)

