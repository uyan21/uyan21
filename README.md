# 안녕하세요 👋

**하드웨어 및 시스템 레벨 프로그래밍부터 고수준 웹 백엔드, 서비스 배포 및 자동화까지 전체 데이터 아키텍처를 유기적으로 연결하는 풀스택 & 임베디드 엔지니어**입니다.

* 🌐 **Full-Stack Web & Backend**: Python(FastAPI, Django), Node.js(Express)와 RDB(PostgreSQL, SQLite)를 활용하여 대화형 웹뷰 및 실시간 티켓/예약 비즈니스 웹 서비스를 설계하고 운영합니다.
* 🔌 **Low-Level & Embedded System**: C/C++, C#을 활용한 MCU 펌웨어 개발, 임베디드 라이브러리 및 데이터 최적화(압축 알고리즘) 설계, 소켓 프로그래밍 기반의 실시간 시스템 리소스 로깅에 강점이 있습니다.
* 🤖 **Automation & DevOps**: Docker 컨테이너 환경, Nginx 리버스 프록시, 리눅스 백그라운드 서비스(systemd/PM2)를 운용하며, 메시징 및 FCM 푸시 API를 연동하여 모니터링/업무 처리를 자동화합니다.

"저수준의 하드웨어 데이터 수집부터 웹 백엔드 서빙, 알림 자동화까지 End-to-End 데이터 흐름을 안전하고 효율적으로 설계하는 것에 열정을 가지고 있습니다."

---


## 기술 스택

**언어**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)

**프레임워크 & 도구**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878A?style=flat&logo=arduino&logoColor=white)

**DB**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

## 제가 만든 서비스와 한 일

기술 이름보다, 실제로 어떤 문제를 해결했는지 중심으로 정리했습니다.

| 만든 서비스 | 제가 한 일 |
| :--- | :--- |
| **조직·회원 관리** | 여러 단계로 나뉜 조직과 회원을 한곳에서 관리할 수 있게 만들었습니다. 사용자 역할에 따라 볼 수 있는 메뉴와 정보를 다르게 하고, 휴대폰에서도 간편하게 로그인하고 사용할 수 있도록 구성했습니다. 서버 설치와 보안 연결, 운영도 직접 맡았습니다. |
| **업무 요청 관리** | 업무 요청을 접수한 뒤 진행 상황과 처리 기록을 한눈에 볼 수 있게 만들었습니다. 상태가 바뀌면 담당자에게 메신저 알림을 보내고, 큰 파일도 첨부할 수 있도록 구현했습니다. |
| **신청·안내 자동화** | 사용자가 대화하듯 질문에 답하면 신청이 접수되고, 자신의 처리 상태도 확인할 수 있는 서비스를 만들었습니다. 접수 현황은 관리 화면에서 바로 확인할 수 있도록 연결했습니다. |
| **근무 일정 배정** | 사람마다 가능한 시간을 받아 겹치지 않게 근무 일정을 짜는 서비스를 만들었습니다. 자동 배정 결과와 전체 근무 현황을 관리 화면에서 쉽게 확인할 수 있게 했습니다. |
| **공간·장비 예약** | 사용 가능한 시간을 확인하고 공간이나 장비를 예약하는 서비스를 만들었습니다. 같은 시간에 예약이 겹치지 않도록 막고, 승인 단계마다 이메일이나 메신저로 알려주도록 했습니다. |
| **건강 지표 기록·보고** | 참여자의 건강 관련 수치를 계속 기록하고 변화 추이를 확인할 수 있게 만들었습니다. 데이터를 주기적으로 백업하고, 일간·주간 보고서가 자동으로 만들어지도록 운영했습니다. |

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



## GitHub 통계

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=uyan21&show_icons=true&theme=default&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uyan21&layout=compact&theme=default&hide_border=true" height="150"/>
</p>
