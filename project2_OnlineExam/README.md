# 정보처리기사 CBT 시스템 🖥️

## 소개

이 프로젝트는 **오프라인 국비지원 부트캠프** 중 진행된 **정보처리기사 CBT 시스템**입니다. 이 시스템은 정보처리기사 자격증 준비를 돕기 위해 개발되었으며, 문제풀이와 정답률 확인, 결제 기능 등을 갖춘 풀스택 프로젝트입니다. 또한 모든 페이지는 적응형 웹페이지로 구성되어 PC, 태블릿, 모바일 환경에서도 적절한 화면 비율로 이용이 가능합니다.

본 프로젝트는 다음과 같은 기능을 제공합니다:
- 회원가입 (일반 회원 '777' 코드, 관리자 '999' 코드)
- 로그인 (Spring Security 적용)
- 문제풀이 (모의고사 또는 기출문제 선택 가능)
- 정답률 및 문제풀이 확인
- 결제 기능 (카카오페이 API 사용)
- 게시판 (공지사항, 수강후기, 과목별 질문 게시판)
- 단어장 기능 (개념 설명 확인)
- 마이페이지 (결제 내역 확인 및 회원정보 수정)

---

<br>

## 기능 설명 및 화면 구성

### 1. 메인 페이지
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![main](https://github.com/user-attachments/assets/1f0a71a9-2ce4-4b2a-9c39-886bf4701ae0) | ![main_mobile](https://github.com/user-attachments/assets/49328608-540f-4de3-801e-f2b5eb4e26a0) | ![main2](https://github.com/user-attachments/assets/24bf0bc2-6ee4-44a7-9bbe-5ea6b8741861)

### 2. 회원가입
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![join](https://github.com/user-attachments/assets/d68c6698-a810-4205-ae56-35177ed3b914) | ![join_mobile](https://github.com/user-attachments/assets/9637f45a-64a4-4d6b-b8fd-8e07b7e56e3b) |

  ![join2](https://github.com/user-attachments/assets/5bb6cc81-a17f-4d60-8b16-9738ed205957)

### 3. 로그인
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![login](https://github.com/user-attachments/assets/5e35a026-d4c4-4712-9144-d0047d4e1b27) | ![login_mobile](https://github.com/user-attachments/assets/20739878-5131-4518-9b9b-a6f3225e4647) |

### 4. 문제풀이
- 사용자는 모의고사 또는 기출문제를 선택해 문제를 풀 수 있으며, 정답률 및 문제풀이 결과를 확인할 수 있습니다.

  ![example](https://github.com/user-attachments/assets/2d10e247-9342-4f07-b58c-7afd896d1ad4)
  ![example2](https://github.com/user-attachments/assets/9ed992d1-a6ce-480e-885a-f2ab197d2ef1)
  ![example3](https://github.com/user-attachments/assets/07d90f36-9baa-4d45-ae19-b705b91dbdaf)
  ![example4](https://github.com/user-attachments/assets/51375671-fd7c-4230-a29a-629c7848911c)

### 5. 결제 기능
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![membership](https://github.com/user-attachments/assets/a61ecce6-3c7a-4b23-b10f-e769245a2f19) | ![membership2](https://github.com/user-attachments/assets/e259722d-7d12-42bb-87cb-ed6be89f70b6) |

  ![membership2_normal](https://github.com/user-attachments/assets/c75626f2-6df7-412b-8294-b935eaf4ec61)

### 6. 게시판
- 총 3개의 게시판이 있으며, 공지사항, 수강후기, 과목별 질문 게시판을 통해 정보를 확인하고 의견을 남길 수 있습니다.

#### 1) 공지사항
  ![notice](https://github.com/user-attachments/assets/77a5fcf4-a4c1-48e0-9629-bc49eb61c30c)
  ![notice2](https://github.com/user-attachments/assets/2cf8854e-fddb-4f4d-9f2f-b4506e0e3dc9)
#### 2) 수강후기 
  ![review](https://github.com/user-attachments/assets/3726eb7a-f440-44aa-8477-a549ddf979d0)
  ![review2](https://github.com/user-attachments/assets/e96db5b5-a146-4a96-afcb-382e0f379226)
#### 3) 과목별 질문 게시판
  ![qna](https://github.com/user-attachments/assets/187edcf4-9f28-4137-8111-063b3df44427)
  ![qna2](https://github.com/user-attachments/assets/5dd550d1-59b0-4be3-b503-b6ddfdafccc4)

### 7. 단어장 기능
- 간단한 설명을 보고 맞춰볼 수 있는 단어장 기능을 제공하여 자격증 시험에 나올 개념을 복습할 수 있습니다.

  ![word](https://github.com/user-attachments/assets/0605ff15-737f-45f3-9e10-7670ca8366a9)
  ![word2](https://github.com/user-attachments/assets/f4d1337c-aa11-4771-9784-b15274c85534)

### 8. 마이페이지
![mypage](https://github.com/user-attachments/assets/d9e1b375-b715-4466-8a9e-48f0ca47a06e)
![mypage2](https://github.com/user-attachments/assets/b0ce4864-06f1-4885-a034-9ff50aa8bd18)
---

<br>

## 요구명세서

정보처리기사 CBT 시스템의 요구명세서는 아래의 링크에서 확인 가능합니다.

  [정보처리기사 CBT 시스템 요구명세서](https://github.com/seunggi-coding/Fullstack/blob/main/project1_SmartFarm/%EC%9A%94%EA%B5%AC%EB%AA%85%EC%84%B8%EC%84%9C%20%ED%99%95%EC%9D%B8.pdf)
  [정보처리기사 CBT 시스템 테이블 명세서](https://github.com/seunggi-coding/Fullstack/blob/main/project1_SmartFarm/%EC%9A%94%EA%B5%AC%EB%AA%85%EC%84%B8%EC%84%9C%20%ED%99%95%EC%9D%B8.pdf)
  [정보처리기사 CBT 시스템 유스케이스 엑터 목록 ![join](https://github.com/user-attachments/assets/d68c6698-a810-4205-ae56-35177ed3b914) | ![join_mobile](https://github.com/user-attachments/assets/9637f45a-64a4-4d6b-b8fd-8e07b7e56e3b) |

  ![join2](https://github.com/user-attachments/assets/5bb6cc81-a17f-4d60-8b16-9738ed205957)

### 3. 로그인
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![login](https://github.com/user-attachments/assets/5e35a026-d4c4-4712-9144-d0047d4e1b27) | ![login_mobile](https://github.com/user-attachments/assets/20739878-5131-4518-9b9b-a6f3225e4647) |

### 4. 문제풀이
- 사용자는 모의고사 또는 기출문제를 선택해 문제를 풀 수 있으며, 정답률 및 문제풀이 결과를 확인할 수 있습니다.

  ![example](https://github.com/user-attachments/assets/2d10e247-9342-4f07-b58c-7afd896d1ad4)
  ![example2](https://github.com/user-attachments/assets/9ed992d1-a6ce-480e-885a-f2ab197d2ef1)
  ![example3](https://github.com/user-attachments/assets/07d90f36-9baa-4d45-ae19-b705b91dbdaf)
  ![example4](https://github.com/user-attachments/assets/51375671-fd7c-4230-a29a-629c7848911c)

### 5. 결제 기능
| PC 버전 | Mobile 버전 |
|:-------:|:-----------:|
| ![membership](https://github.com/user-attachments/assets/a61ecce6-3c7a-4b23-b10f-e769245a2f19) | ![membership2](https://github.com/user-attachments/assets/e259722d-7d12-42bb-87cb-ed6be89f70b6) |

  ![membership2_normal](https://github.com/user-attachments/assets/c75626f2-6df7-412b-8294-b935eaf4ec61)

### 6. 게시판
- 총 3개의 게시판이 있으며, 공지사항, 수강후기, 과목별 질문 게시판을 통해 정보를 확인하고 의견을 남길 수 있습니다.

#### 1) 공지사항
  ![notice](https://github.com/user-attachments/assets/77a5fcf4-a4c1-48e0-9629-bc49eb61c30c)
  ![notice2](https://github.com/user-attachments/assets/2cf8854e-fddb-4f4d-9f2f-b4506e0e3dc9)
#### 2) 수강후기 
  ![review](https://github.com/user-attachments/assets/3726eb7a-f440-44aa-8477-a549ddf979d0)
  ![review2](https://github.com/user-attachments/assets/e96db5b5-a146-4a96-afcb-382e0f379226)
#### 3) 과목별 질문 게시판
  ![qna](https://github.com/user-attachments/assets/187edcf4-9f28-4137-8111-063b3df44427)
  ![qna2](https://github.com/user-attachments/assets/5dd550d1-59b0-4be3-b503-b6ddfdafccc4)

### 7. 단어장 기능
- 간단한 설명을 보고 맞춰볼 수 있는 단어장 기능을 제공하여 자격증 시험에 나올 개념을 복습할 수 있습니다.

  ![word](https://github.com/user-attachments/assets/0605ff15-737f-45f3-9e10-7670ca8366a9)
  ![word2](https://github.com/user-attachments/assets/f4d1337c-aa11-4771-9784-b15274c85534)

### 8. 마이페이지
![mypage](https://github.com/user-attachments/assets/d9e1b375-b715-4466-8a9e-48f0ca47a06e)
![mypage2](https://github.com/user-attachments/assets/b0ce4864-06f1-4885-a034-9ff50aa8bd18)
---

<br>

## 요구명세서

정보처리기사 CBT 시스템의 요구명세서는 아래의 링크에서 확인 가능합니다.

  [정보처리기사 CBT 시스템 요구명세서](https://github.com/seunggi-coding/Fullstack/blob/main/project2_OnlineExam/project2_%EC%9E%91%EB%8B%B9%EB%AA%A8%EC%9D%98.pdf)
  [정보처리기사 CBT 시스템 테이블 명세서](https://github.com/seunggi-coding/Fullstack/blob/main/project2_OnlineExam/project2_%ED%85%8C%EC%9D%B4%EB%B8%94%20%EB%AA%85%EC%84%B8%EC%84%9C.pdf)
  [정보처리기사 CBT 시스템 유스케이스 엑터 목록](https://github.com/seunggi-coding/Fullstack/blob/main/project2_OnlineExam/%EC%9C%A0%EC%8A%A4%EC%BC%80%EC%9D%B4%EC%8A%A4%20%EC%97%91%ED%84%B0%20%EB%AA%A9%EB%A1%9D.pdf)
---

<br>

## 사용 기술 스택

### Backend
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/SQL%20Developer-4479A1?style=for-the-badge&logo=Oracle&logoColor=white">
<img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=Hibernate&logoColor=white">
<img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white">

### Frontend
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white">

### Tools
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=IntelliJIDEA&logoColor=white">

---

<br>

## 프로젝트 팀원

| Frontend Developer | Backend Developer | Backend Developer |
| :----------------: | :----------------: | :----------------: |
| ![김효식](https://github.com/member1.png?size=120) | ![문승기](https://github.com/seunggi-coding.png?size=120) | ![배정웅](https://github.com/member2.png?size=120) |
| [김효식](https://github.com/member1) | [문승기](https://github.com/seunggi-coding) | [배정웅](https://github.com/member2) |

---

이 README 파일은 **오프라인 국비지원 부트캠프** 중 개발된 정보처리기사 CBT 시스템의 핵심 내용을 다루고 있으며, 유지보수 및 확장을 위한 기본 자료로 활용될 수 있습니다.
