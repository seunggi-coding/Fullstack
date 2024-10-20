# SmartFarm 관리 시스템 🌱

## 소개

이 프로젝트는 **오프라인 국비지원 부트캠프** 기간 동안 진행한 **SmartFarm 관리 시스템**입니다. IoT 시스템을 기반으로 한다는 것을 가정하여 원격으로 작물 재배를 관리하고, 사용자 정보와 작물 정보를 효율적으로 관리할 수 있는 풀스택 프로젝트입니다. 회원가입, 로그인, 실시간 날씨 정보 제공, 참고 영상 모달창 기능 등을 제공하며, 관리자는 장치 제어와 공지사항 작성 등 다양한 기능을 사용할 수 있습니다.

본 프로젝트는 다음과 같은 기능을 제공합니다:
- 회원가입 (일반 사용자 '777' 코드, 관리자 '999' 코드)
- 로그인
- 메인 페이지
- 장치 제어 및 작물 재배 정보 확인
- 문의 게시판
- 공지사항
- 회원 정보 수정
- 실시간 날씨 정보 위젯 및 팝업
- 참고 영상 모달창 기능

---

<br>

## 기능 설명 및 화면 구성

### 1. 메인 페이지
- 로그인 후 메인 페이지로 이동하여 실시간 날씨 위젯과 공지사항, 문의 게시판, 참고 영상 모달창을 확인할 수 있습니다.

  ![main](https://github.com/user-attachments/assets/186ad0e9-1ab2-4563-b28e-0ea1348ce048)
  ![main_weather_widget](https://github.com/user-attachments/assets/082c0c61-232b-4d07-96a6-b1d86ae2914a)
  ![main_popup](https://github.com/user-attachments/assets/7ea9a69d-18cd-4621-beab-632413f346b4)

### 2. 회원가입
- 사용자는 '777' 회원코드로 가입할 수 있으며, 관리자는 '999' 회원코드를 사용해 회원가입이 가능합니다.

  ![join](https://github.com/user-attachments/assets/17448a8c-6e73-44b5-be04-35b7b18c54ff)
  ![join_success](https://github.com/user-attachments/assets/ceed1814-45d8-45b9-a08c-8a9d936000a1)

### 3. 로그인
- 로그인 기능을 통해 사용자는 시스템에 접속하며, 사용자 또는 관리자의 권한에 따라 페이지 접근 권한이 달라집니다.

  ![login](https://github.com/user-attachments/assets/d80c9900-eba8-4c57-a04a-fedf2445aa12)

### 4. 장치 제어
- 사용자는 원격으로 장치를 제어할 수 있으며, 장치 상태 및 작업 성공 여부가 화면에 표시됩니다.

  ![device](https://github.com/user-attachments/assets/f5c937ef-18dc-4af7-856f-a94d7f0366ca)
  ![device_water](https://github.com/user-attachments/assets/47c56eda-546e-4386-9c69-217888c41d6f)
  ![device_sucess](https://github.com/user-attachments/assets/a9db89a3-e9a6-4c5d-8976-271b52bd18a1)
  ![device_success_after](https://github.com/user-attachments/assets/b41b5a28-be2d-4c59-8af1-96bfb9bbf9e2)

### 5. 작물 정보 확인
- 작물 재배 정보를 확인할 수 있습니다. 작물 리스트에 마우스를 호버하면, 각 작물에 대한 자세한 재배 정보가 나타나며, 재배 상태와 필요한 관리 작업 등을 확인할 수 있습니다. 장치 상태 및 작업 성공 여부도 화면에 표시됩니다.

  ![list](https://github.com/user-attachments/assets/34b7155d-b4d1-4c24-b671-9a4637210277)
  ![list2](https://github.com/user-attachments/assets/7187c62b-6dd6-41cd-bc32-8275ce1c3a56)


### 6. 문의 게시판
- 사용자는 문의 게시판을 통해 질문을 올리고, 관리자는 답변을 작성할 수 있습니다.

  ![qna](https://github.com/user-attachments/assets/f7af3575-67a7-4ce1-807d-e3153c041acb)
  ![qna_add](https://github.com/user-attachments/assets/c6ae3d4a-e7d2-4606-bd85-bf22c12cf2f5)

### 7. 공지사항
- 관리자는 공지사항을 작성하여 중요한 정보를 사용자에게 전달할 수 있습니다.

  ![notice](https://github.com/user-attachments/assets/b51d4a73-714e-4a9e-ac4f-86943254d560)
  ![notice_add](https://github.com/user-attachments/assets/c10c790e-8cd3-4a5c-a736-9583293ddc48)

### 8. 회원 정보 수정
- 사용자는 마이페이지에서 회원 정보를 수정할 수 있습니다.

  ![mypage](https://github.com/user-attachments/assets/cb27f78f-690f-4598-a9b6-55e7e60f21fc)

---

<br>

## 요구명세서

SmartFarm 관리 시스템의 요구명세서는 아래의 링크에서 확인 가능합니다.

  [SmartFarm 관리 시스템 요구명세](https://github.com/seunggi-coding/Fullstack/blob/main/project1_SmartFarm/%EC%9A%94%EA%B5%AC%EB%AA%85%EC%84%B8%EC%84%9C%20%ED%99%95%EC%9D%B8.pdf)

---

<br>

## 사용 기술 스택

### Backend
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/SQL%20Developer-4479A1?style=for-the-badge&logo=Oracle&logoColor=white">
<img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=Hibernate&logoColor=white">
<img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white">

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

이 README 파일은 **오프라인 국비지원 부트캠프** 중 개발된 SmartFarm 관리 시스템의 핵심 내용을 다루고 있으며, 유지보수 및 확장을 위한 기본 자료로 활용될 수 있습니다.
