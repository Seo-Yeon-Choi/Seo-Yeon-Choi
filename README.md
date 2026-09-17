<h1 align="center">최서연 | Backend Developer</h1>

<p align="center">
  <strong>사용자의 업무 흐름을 이해하고, 기능과 데이터를 연결하는 개발자를 지향합니다.</strong>
</p>

<p align="center">
  <a href="https://github.com/Seo-Yeon-Choi/EduPOP">EduPOP</a> ·
  <a href="https://github.com/Seo-Yeon-Choi/RunPTApp">RunPT</a>
</p>

---

## About Me

안녕하세요. Java와 Spring 기반의 백엔드 개발자를 준비하고 있는 최서연입니다.

학원 운영과 학습을 지원하는 웹 서비스 **EduPOP**, 러너 맞춤형 경로 서비스 **RunPT**를 개발하며 화면·서버·데이터를 연결하는 경험을 쌓았습니다. 오류가 발생하면 요청 처리 과정과 데이터 흐름을 따라 원인을 파악하고, 수정한 내용이 관련 기능에도 올바르게 반영되는지 확인하려고 노력합니다.

사용자의 불편을 줄이는 기능을 만드는 데 흥미를 느끼며, 개발한 서비스를 안정적으로 배포하고 운영할 수 있도록 Linux·네트워크·클라우드에 대한 이해도 넓혀가고 있습니다.

## Tech Stack

| 구분 | 기술 |
| --- | --- |
| Backend | Java, Spring Boot, Spring Security |
| Database | MySQL, MyBatis |
| Web | Thymeleaf, HTML, CSS, JavaScript |
| 프로젝트 활용 | OAuth 2.0 기반 소셜 로그인, REST API 연동, LLM API 연동, Firebase |
| Tools | Git, GitHub, IntelliJ IDEA, Android Studio |

## Projects

### EduPOP

**학원 운영부터 시험·복습·학습 분석까지 연결하는 교육 플랫폼**

관리자·교사·학생이 각자의 역할에 맞게 학원 운영과 학습 기능을 이용하는 웹 서비스입니다.

- **역할:** 5인 팀의 팀장으로 일정 관리, 코드 통합 및 주요 기능 개발 담당
- Spring Security를 적용한 인증·역할별 접근 권한 처리와 Kakao·Naver·Google 소셜 로그인 통합
- 시험지 생성 기능과 PDF 텍스트 추출을 통한 문항 입력 기능 개발
- 사업자등록정보 검증 API 및 AI 유사 문제 생성 기능 연동
- 역할 접두사 불일치와 CSRF 토큰 누락으로 발생한 403 오류의 원인 분석 및 수정

**사용 기술:** Java, Spring Boot, Spring Security, MyBatis, MySQL, Thymeleaf

[프로젝트 자세히 보기 →](https://github.com/Seo-Yeon-Choi/EduPOP)

### RunPT

**희망 거리와 경사도를 반영하는 러너 맞춤형 경로 서비스**

사용자의 조건을 서버에 전달하고, 생성된 러닝 경로를 앱에서 확인하고 다시 불러올 수 있는 Android 서비스입니다.

- **역할:** Android 앱 화면 개발, 백엔드 연동 및 Firebase 기반 데이터 관리 담당
- 사용자가 입력한 희망 거리·경사도를 서버에 전달하고 생성된 경로를 화면에 표시
- 경로의 위도·경도 정보를 Firebase에 저장하고 이전 경로를 조회하는 기능 구현
- 사용자 입력부터 서버 응답, 화면 표시, 데이터 저장까지 이어지는 흐름 구현

**활용 환경:** Android Studio, Firebase, 백엔드 API

[앱 저장소 보기 →](https://github.com/Seo-Yeon-Choi/RunPTApp)

## Problem Solving & Collaboration

**인증·권한 오류의 원인 구분**

EduPOP에 Spring Security를 적용한 후 여러 기능에서 403 오류가 발생했습니다. 사용자 역할 값과 접근 권한 설정, 상태 변경 요청의 CSRF 토큰 전달 여부를 확인했습니다. 역할 접두사를 통일하고 필요한 요청에 CSRF 토큰을 전달하도록 수정하며, 같은 응답 코드도 서로 다른 원인에서 발생할 수 있다는 점을 배웠습니다.

**일정을 고려한 기능 범위 조정**

프로젝트 진행 중 학생별 통계 기능을 추가하자는 의견이 나왔을 때, 기능의 필요성과 남은 일정을 함께 검토했습니다. 기존 페이지를 재활용하는 방향으로 구현 범위를 조정하고 역할과 일정을 재분배해, 정해진 기간 안에 기능을 완성했습니다.

## Interests

- 인증·인가와 데이터 흐름을 이해하는 백엔드 개발
- 외부 API와 AI 기능을 실제 서비스의 업무 흐름에 맞게 연결하는 방법
- Linux·네트워크를 바탕으로 한 서비스 배포와 운영

<!-- 기술 블로그와 포트폴리오의 공개 URL을 확인한 뒤 아래에 추가하세요.
## Links
- Blog: 공개 블로그 URL
- Portfolio: 공개 포트폴리오 URL
- Email: 공개할 이메일 주소
-->
