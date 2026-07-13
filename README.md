# 안녕하세요 👋

**하드웨어 및 시스템 레벨 프로그래밍부터 고수준 웹 백엔드, 서비스 배포 및 자동화까지 전체 데이터 아키텍처를 유기적으로 연결하는 풀스택 & 임베디드 엔지니어**입니다.

* 🌐 **Full-Stack Web & Backend**: Python(FastAPI, Django), Node.js(Express)와 RDB(PostgreSQL, SQLite)를 활용하여 대화형 웹뷰 및 실시간 티켓/예약 비즈니스 웹 서비스를 설계하고 운영합니다.
* 🔌 **Low-Level & Embedded System**: C/C++, C#을 활용한 MCU 펌웨어 개발, 임베디드 라이브러리 및 데이터 최적화(압축 알고리즘) 설계, 소켓 프로그래밍 기반의 실시간 시스템 리소스 로깅에 강점이 있습니다.
* 🤖 **Automation & DevOps**: Docker 컨테이너 환경, Nginx 리버스 프록시, 리눅스 백그라운드 서비스(systemd/PM2)를 운용하며, 메시징 및 FCM 푸시 API를 연동하여 모니터링/업무 처리를 자동화합니다.

"저수준의 하드웨어 데이터 수집부터 웹 백엔드 서빙, 알림 자동화까지 End-to-End 데이터 흐름을 안전하고 효율적으로 설계하는 것에 열정을 가지고 있습니다."

---


## 기술 스택

**언어**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)

**프레임워크 & 도구**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878A?style=flat&logo=arduino&logoColor=white)

**DB**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

---

## 주요 프로젝트

## 🛠️ Core Projects (서비스 개발 및 운영)

| 프로젝트명 | 핵심 기능 및 아키텍처 | 기술 스택 | 주요 역할 및 기여 |
| :--- | :--- | :--- | :--- |
| **Hierarchical Org-Manager** | • **다계층 회원 및 권한 관리 시스템** (본사-지사-팀 구조)<br>• **모바일 임베디드 웹뷰(In-App Webview)** 기반의 패스워드리스 자동 인증 설계<br>• 모바일 환경 최적화 단일 웹앱(Single Page App) UI 제공 | FastAPI, SQLite, Vanilla JS, In-App Webview SDK, Nginx, systemd | • 백엔드 REST API 설계 및 권한 처리 필터 구현<br>• 모바일 사용자 경험 향상을 위한 웹 앱 프론트 개발<br>• Nginx 리버스 프록시 및 TLS 인증 배포 자동화 |
| **Work Ticket & Request System** | • **실시간 티켓 기반 업무 요청 관리 플랫폼**<br>• 업무 상태 변화에 따른 **인스턴트 메신저 실시간 자동 알림** 연동<br>• 대용량 파일 첨부 및 처리 로그 추적 기능 | Node.js (Express), PostgreSQL, Real-time Messaging API, PM2 | • 관계형 DB 스키마 설계 및 파일 업로드 처리 로직 최적화<br>• 비동기 메시징 및 상태 머신(State Machine) 구현<br>• 시스템 모니터링 및 무중단 서버 운영 관리 |
| **Workflow Automation Assistant** | • **신청서 접수 및 워크플로우 자동화 대화형 서비스**<br>• 신규 접수 현황 모니터링 대시보드와 유기적 연동<br>• 정형 데이터 입력 가이드 및 사용자 맞춤 상태 조회 | Python, FastAPI, Messenger Chatbot API, PostgreSQL | • 사용자 대화 흐름(Conversation Flow) 모델 구현<br>• 데이터 시각화 및 백오피스 통계 가공 API 작성 |
| **Staff Scheduling & Matching Web** | • **가용 시간 기반 안내 스태프 스케줄 매칭 시스템**<br>• 교대 근무(Shift) 자동 할당 및 조율 알고리즘 적용<br>• 대시보드를 통한 직관적인 근무 현황 시각화 | Node.js (Vite), Express, SQLite, TypeScript | • 스케줄 충돌 방지 핵심 알고리즘 개발 및 최적화<br>• Vite 기반 프론트엔드 빌드 시스템 및 API 연동 |
| **Resource Booking Platform** | • **공유 공간 및 물리 자원 실시간 예약 웹**<br>• 타임슬롯 기반 중복 예약 방지 알고리즘 적용<br>• 예약 승인 단계별 이메일/메시징 알림 프로세스 | Python (FastAPI/Flask), HTML5/CSS3, Nginx | • 예약 상태 관리 트랜잭션 처리 최적화<br>• 직관적이고 깔끔한 캘린더 인터페이스 UI 구현 |
| **Metrics Tracking & Logger Service** | • **참여자 건강 지표 모니터링 및 로깅 서비스**<br>• 주기적 데이터 백업 및 Docker 컨테이너 기반 격리 운영<br>• 배치 처리 기반의 일간/주간 리포트 자동 생성 | Python, PostgreSQL, Docker, Messaging API | • Docker Compose 환경 구성 및 데이터 지속성(Volume) 설계<br>• 주기적 배치 작업(Scheduler)을 통한 통계 가공 |

---

## 📚 Open Source & Utility Projects (공개 유틸리티 저장소)

| 저장소명 | 구분 / 언어 | 주요 기능 및 핵심 개념 | 관련 기술 스택 |
| :--- | :--- | :--- | :--- |
| **[pushFCM](https://github.com/uyan21/pushFCM)** | Utility / Python | • Firebase FCM 서비스를 연동한 **크로스 플랫폼 푸시 알림 발송 모듈**<br>• 실시간 유저 타겟팅 알림 메시지 요청 처리 기능 제공 | Python, Firebase Cloud Messaging API |
| **[FirebaseJson](https://github.com/uyan21/FirebaseJson)** | Library / C++ | • 임베디드 기기(IoT) 환경에서 **Firebase Realtime Database 연동을 지원하는 JSON 파서**<br>• 제한된 리소스의 하드웨어에 최적화된 경량 직렬화/역직렬화 라이브러리 | C++, Embedded Systems, Arduino |
| **[dhtdjango](https://github.com/uyan21/dhtdjango)** | Web App / Python | • **DHT 온습도 센서 데이터 모니터링 및 로깅용 웹 서버**<br>• 데이터 시각화 및 대시보드를 통한 실시간 환경 정보 트래킹 제공 | Python, Django, SQLite, IoT Sensors |
| **[huffman](https://github.com/uyan21/huffman)** | Algorithm / C++ | • **허프만 코딩 기반의 무손실 데이터 압축 및 압축 해제 도구**<br>• 빈도수 기반 이진 트리 설계 및 파일 비트 스트림(Bitstream) 최적화 | C++, Data Structures |
| **[deepLearningStudy](https://github.com/uyan21/deepLearningStudy)** | Study / Python | • **머신러닝 및 딥러닝 핵심 알고리즘 분석 및 실습** 저장소<br>• CNN, RNN 등 모델 구현 및 PyTorch/TensorFlow를 사용한 파라미터 튜닝 기록 | Python, Jupyter Notebook, Deep Learning |
| **[gitman](https://github.com/uyan21/gitman)** | System / C++ | • CLI 환경에서 로컬 Git 저장소들의 상태 감지 및 변경 이력을 모니터링하는 **로컬 저장소 백업 유틸리티** | C++, Git API, CLI Tools |
| **[multiple_FND](https://github.com/uyan21/multiple_FND)** | Hardware / C++ | • MCU 환경에서 다중 FND(7-Segment)를 제어하기 위한 **동적 스캐닝 드라이버**<br>• 타이머 인터럽트를 활용한 플리커 프리(Flicker-free) 멀티플렉싱 제어 기법 적용 | C++, AVR, MCU System |
| **[memorizerSource](https://github.com/uyan21/memorizerSource)** | Desktop / C# | • 데이터 조회 및 암기 학습 보조용 **데스크톱 애플리케이션**<br>• 가볍고 직관적인 UI 설계 및 로컬 데이터베이스 연동 | C#, .NET WinForms |
| **[saveRInfo](https://github.com/uyan21/saveRInfo)** | System / C | • 저수준 시스템 레벨에서 **네트워크 소켓 정보 및 리소스 상태를 로깅하는 시스템 유틸리티** | C, Socket Programming, System Logs |



## 🛠️ Core Projects (서비스 개발 및 운영)

| 프로젝트명 | 핵심 기능 및 아키텍처 | 기술 스택 | 주요 역할 및 기여 |
| :--- | :--- | :--- | :--- |
| **Hierarchical Org-Manager** | • **다계층 회원 및 권한 관리 시스템** (본사-지사-팀 구조)<br>• **모바일 임베디드 웹뷰(In-App Webview)** 기반의 패스워드리스 자동 인증 설계<br>• 모바일 환경 최적화 단일 웹앱(Single Page App) UI 제공 | FastAPI, SQLite, Vanilla JS, In-App Webview SDK, Nginx, systemd | • 백엔드 REST API 설계 및 권한 처리 필터 구현<br>• 모바일 사용자 경험 향상을 위한 웹 앱 프론트 개발<br>• Nginx 리버스 프록시 및 TLS 인증 배포 자동화 |
| **Work Ticket & Request System** | • **실시간 티켓 기반 업무 요청 관리 플랫폼**<br>• 업무 상태 변화에 따른 **인스턴트 메신저 실시간 자동 알림** 연동<br>• 대용량 파일 첨부 및 처리 로그 추적 기능 | Node.js (Express), PostgreSQL, Real-time Messaging API, PM2 | • 관계형 DB 스키마 설계 및 파일 업로드 처리 로직 최적화<br>• 비동기 메시징 및 상태 머신(State Machine) 구현<br>• 시스템 모니터링 및 무중단 서버 운영 관리 |
| **Workflow Automation Assistant** | • **신청서 접수 및 워크플로우 자동화 대화형 서비스**<br>• 신규 접수 현황 모니터링 대시보드와 유기적 연동<br>• 정형 데이터 입력 가이드 및 사용자 맞춤 상태 조회 | Python, FastAPI, Messenger Chatbot API, PostgreSQL | • 사용자 대화 흐름(Conversation Flow) 모델 구현<br>• 데이터 시각화 및 백오피스 통계 가공 API 작성 |
| **Staff Scheduling & Matching Web** | • **가용 시간 기반 안내 스태프 스케줄 매칭 시스템**<br>• 교대 근무(Shift) 자동 할당 및 조율 알고리즘 적용<br>• 대시보드를 통한 직관적인 근무 현황 시각화 | Node.js (Vite), Express, SQLite, TypeScript | • 스케줄 충돌 방지 핵심 알고리즘 개발 및 최적화<br>• Vite 기반 프론트엔드 빌드 시스템 및 API 연동 |
| **Resource Booking Platform** | • **공유 공간 및 물리 자원 실시간 예약 웹**<br>• 타임슬롯 기반 중복 예약 방지 알고리즘 적용<br>• 예약 승인 단계별 이메일/메시징 알림 프로세스 | Python (FastAPI/Flask), HTML5/CSS3, Nginx | • 예약 상태 관리 트랜잭션 처리 최적화<br>• 직관적이고 깔끔한 캘린더 인터페이스 UI 구현 |
| **Metrics Tracking & Logger Service** | • **참여자 건강 지표 모니터링 및 로깅 서비스**<br>• 주기적 데이터 백업 및 Docker 컨테이너 기반 격리 운영<br>• 배치 처리 기반의 일간/주간 리포트 자동 생성 | Python, PostgreSQL, Docker, Messaging API | • Docker Compose 환경 구성 및 데이터 지속성(Volume) 설계<br>• 주기적 배치 작업(Scheduler)을 통한 통계 가공 |

---

## 📚 Open Source & Utility Projects (공개 유틸리티 저장소)

| 저장소명 | 구분 / 언어 | 주요 기능 및 핵심 개념 | 관련 기술 스택 |
| :--- | :--- | :--- | :--- |
| **[pushFCM](https://github.com/uyan21/pushFCM)** | Utility / Python | • Firebase FCM 서비스를 연동한 **크로스 플랫폼 푸시 알림 발송 모듈**<br>• 실시간 유저 타겟팅 알림 메시지 요청 처리 기능 제공 | Python, Firebase Cloud Messaging API |
| **[FirebaseJson](https://github.com/uyan21/FirebaseJson)** | Library / C++ | • 임베디드 기기(IoT) 환경에서 **Firebase Realtime Database 연동을 지원하는 JSON 파서**<br>• 제한된 리소스의 하드웨어에 최적화된 경량 직렬화/역직렬화 라이브러리 | C++, Embedded Systems, Arduino |
| **[dhtdjango](https://github.com/uyan21/dhtdjango)** | Web App / Python | • **DHT 온습도 센서 데이터 모니터링 및 로깅용 웹 서버**<br>• 데이터 시각화 및 대시보드를 통한 실시간 환경 정보 트래킹 제공 | Python, Django, SQLite, IoT Sensors |
| **[huffman](https://github.com/uyan21/huffman)** | Algorithm / C++ | • **허프만 코딩 기반의 무손실 데이터 압축 및 압축 해제 도구**<br>• 빈도수 기반 이진 트리 설계 및 파일 비트 스트림(Bitstream) 최적화 | C++, Data Structures |
| **[deepLearningStudy](https://github.com/uyan21/deepLearningStudy)** | Study / Python | • **머신러닝 및 딥러닝 핵심 알고리즘 분석 및 실습** 저장소<br>• CNN, RNN 등 모델 구현 및 PyTorch/TensorFlow를 사용한 파라미터 튜닝 기록 | Python, Jupyter Notebook, Deep Learning |
| **[gitman](https://github.com/uyan21/gitman)** | System / C++ | • CLI 환경에서 로컬 Git 저장소들의 상태 감지 및 변경 이력을 모니터링하는 **로컬 저장소 백업 유틸리티** | C++, Git API, CLI Tools |
| **[multiple_FND](https://github.com/uyan21/multiple_FND)** | Hardware / C++ | • MCU 환경에서 다중 FND(7-Segment)를 제어하기 위한 **동적 스캐닝 드라이버**<br>• 타이머 인터럽트를 활용한 플리커 프리(Flicker-free) 멀티플렉싱 제어 기법 적용 | C++, AVR, MCU System |
| **[memorizerSource](https://github.com/uyan21/memorizerSource)** | Desktop / C# | • 데이터 조회 및 암기 학습 보조용 **데스크톱 애플리케이션**<br>• 가볍고 직관적인 UI 설계 및 로컬 데이터베이스 연동 | C#, .NET WinForms |
| **[saveRInfo](https://github.com/uyan21/saveRInfo)** | System / C | • 저수준 시스템 레벨에서 **네트워크 소켓 정보 및 리소스 상태를 로깅하는 시스템 유틸리티** | C, Socket Programming, System Logs |



## 🛠️ Core Projects (서비스 개발 및 운영)

| 프로젝트명 | 핵심 기능 및 아키텍처 | 기술 스택 | 주요 역할 및 기여 |
| :--- | :--- | :--- | :--- |
| **Hierarchical Org-Manager** | • **다계층 회원 및 권한 관리 시스템** (본사-지사-팀 구조)<br>• **모바일 임베디드 웹뷰(In-App Webview)** 기반의 패스워드리스 자동 인증 설계<br>• 모바일 환경 최적화 단일 웹앱(Single Page App) UI 제공 | FastAPI, SQLite, Vanilla JS, In-App Webview SDK, Nginx, systemd | • 백엔드 REST API 설계 및 권한 처리 필터 구현<br>• 모바일 사용자 경험 향상을 위한 웹 앱 프론트 개발<br>• Nginx 리버스 프록시 및 TLS 인증 배포 자동화 |
| **Work Ticket & Request System** | • **실시간 티켓 기반 업무 요청 관리 플랫폼**<br>• 업무 상태 변화에 따른 **인스턴트 메신저 실시간 자동 알림** 연동<br>• 대용량 파일 첨부 및 처리 로그 추적 기능 | Node.js (Express), PostgreSQL, Real-time Messaging API, PM2 | • 관계형 DB 스키마 설계 및 파일 업로드 처리 로직 최적화<br>• 비동기 메시징 및 상태 머신(State Machine) 구현<br>• 시스템 모니터링 및 무중단 서버 운영 관리 |
| **Workflow Automation Assistant** | • **신청서 접수 및 워크플로우 자동화 대화형 서비스**<br>• 신규 접수 현황 모니터링 대시보드와 유기적 연동<br>• 정형 데이터 입력 가이드 및 사용자 맞춤 상태 조회 | Python, FastAPI, Messenger Chatbot API, PostgreSQL | • 사용자 대화 흐름(Conversation Flow) 모델 구현<br>• 데이터 시각화 및 백오피스 통계 가공 API 작성 |
| **Staff Scheduling & Matching Web** | • **가용 시간 기반 안내 스태프 스케줄 매칭 시스템**<br>• 교대 근무(Shift) 자동 할당 및 조율 알고리즘 적용<br>• 대시보드를 통한 직관적인 근무 현황 시각화 | Node.js (Vite), Express, SQLite, TypeScript | • 스케줄 충돌 방지 핵심 알고리즘 개발 및 최적화<br>• Vite 기반 프론트엔드 빌드 시스템 및 API 연동 |
| **Resource Booking Platform** | • **공유 공간 및 물리 자원 실시간 예약 웹**<br>• 타임슬롯 기반 중복 예약 방지 알고리즘 적용<br>• 예약 승인 단계별 이메일/메시징 알림 프로세스 | Python (FastAPI/Flask), HTML5/CSS3, Nginx | • 예약 상태 관리 트랜잭션 처리 최적화<br>• 직관적이고 깔끔한 캘린더 인터페이스 UI 구현 |
| **Metrics Tracking & Logger Service** | • **참여자 건강 지표 모니터링 및 로깅 서비스**<br>• 주기적 데이터 백업 및 Docker 컨테이너 기반 격리 운영<br>• 배치 처리 기반의 일간/주간 리포트 자동 생성 | Python, PostgreSQL, Docker, Messaging API | • Docker Compose 환경 구성 및 데이터 지속성(Volume) 설계<br>• 주기적 배치 작업(Scheduler)을 통한 통계 가공 |

---

## 📚 Open Source & Utility Projects (공개 유틸리티 저장소)

| 저장소명 | 구분 / 언어 | 주요 기능 및 핵심 개념 | 관련 기술 스택 |
| :--- | :--- | :--- | :--- |
| **[pushFCM](https://github.com/uyan21/pushFCM)** | Utility / Python | • Firebase FCM 서비스를 연동한 **크로스 플랫폼 푸시 알림 발송 모듈**<br>• 실시간 유저 타겟팅 알림 메시지 요청 처리 기능 제공 | Python, Firebase Cloud Messaging API |
| **[FirebaseJson](https://github.com/uyan21/FirebaseJson)** | Library / C++ | • 임베디드 기기(IoT) 환경에서 **Firebase Realtime Database 연동을 지원하는 JSON 파서**<br>• 제한된 리소스의 하드웨어에 최적화된 경량 직렬화/역직렬화 라이브러리 | C++, Embedded Systems, Arduino |
| **[dhtdjango](https://github.com/uyan21/dhtdjango)** | Web App / Python | • **DHT 온습도 센서 데이터 모니터링 및 로깅용 웹 서버**<br>• 데이터 시각화 및 대시보드를 통한 실시간 환경 정보 트래킹 제공 | Python, Django, SQLite, IoT Sensors |
| **[huffman](https://github.com/uyan21/huffman)** | Algorithm / C++ | • **허프만 코딩 기반의 무손실 데이터 압축 및 압축 해제 도구**<br>• 빈도수 기반 이진 트리 설계 및 파일 비트 스트림(Bitstream) 최적화 | C++, Data Structures |
| **[deepLearningStudy](https://github.com/uyan21/deepLearningStudy)** | Study / Python | • **머신러닝 및 딥러닝 핵심 알고리즘 분석 및 실습** 저장소<br>• CNN, RNN 등 모델 구현 및 PyTorch/TensorFlow를 사용한 파라미터 튜닝 기록 | Python, Jupyter Notebook, Deep Learning |
| **[gitman](https://github.com/uyan21/gitman)** | System / C++ | • CLI 환경에서 로컬 Git 저장소들의 상태 감지 및 변경 이력을 모니터링하는 **로컬 저장소 백업 유틸리티** | C++, Git API, CLI Tools |
| **[multiple_FND](https://github.com/uyan21/multiple_FND)** | Hardware / C++ | • MCU 환경에서 다중 FND(7-Segment)를 제어하기 위한 **동적 스캐닝 드라이버**<br>• 타이머 인터럽트를 활용한 플리커 프리(Flicker-free) 멀티플렉싱 제어 기법 적용 | C++, AVR, MCU System |
| **[memorizerSource](https://github.com/uyan21/memorizerSource)** | Desktop / C# | • 데이터 조회 및 암기 학습 보조용 **데스크톱 애플리케이션**<br>• 가볍고 직관적인 UI 설계 및 로컬 데이터베이스 연동 | C#, .NET WinForms |
| **[saveRInfo](https://github.com/uyan21/saveRInfo)** | System / C | • 저수준 시스템 레벨에서 **네트워크 소켓 정보 및 리소스 상태를 로깅하는 시스템 유틸리티** | C, Socket Programming, System Logs |





---

## GitHub 통계

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=uyan21&show_icons=true&theme=default&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uyan21&layout=compact&theme=default&hide_border=true" height="150"/>
</p>
