<div align="center">

# 안녕하세요, 백은혜입니다 👋

**이화여자대학교 컴퓨터공학과**

Java · Python · JavaScript · C  |  AI · Backend · VR · Mobile

[![Gmail](https://img.shields.io/badge/bihunheay1@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bihunheay1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-hunheay123-181717?style=flat-square&logo=github)](https://github.com/hunheay123)

</div>

---

## 🙋‍♀️ About Me

- 🎓 **이화여자대학교** 컴퓨터공학과 재학
- 🤖 AI 엔진 설계 및 자연어 처리에 관심이 많습니다 (현재 졸업프로젝트 AI 파트 담당)
- 🔭 백엔드 개발(Spring Boot)과 AI 응용 서비스 구축 경험
- 🥽 VR/XR 개발 경험 (Meta Quest 3 · Unity)
- 📱 React Native 모바일 앱 개발 경험
- 🤝 팀 프로젝트에서 기획, 설계, 개발 전 과정에 참여한 경험

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

**Frameworks & Libraries**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database & Tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)

---

## 🚀 Projects

### 🧠 CHARACTER MATRIX — 개인화 영어 회화 AI 엔진 `진행 중`
> 발화 스타일 분석 기반 영어 회화 AI 시스템 | 이화여대 캡스톤디자인&창업프로젝트 (졸업프로젝트)

사용자의 말투를 실시간으로 분석해 AI 캐릭터의 성격이 맞춰 변하는 **개인화 영어 회화 플랫폼**

- **담당 파트: AI 엔진 전체 설계 및 구현**
- 영어 문장에서 Formality·Energy·Intimacy·Humor·Curiosity **5축 성격 지표** 추출 (규칙 기반 → ML 고도화 예정)
- 5축 점수를 행렬 연산(`W × v + bias`)으로 AI 캐릭터 파라미터(tone_casual, energy_level, humor_level)로 변환
- **EMA(지수이동평균) 스무딩**으로 대화 누적에 따른 자연스러운 성격 변화 구현
- GPT-4o 시스템 프롬프트에 캐릭터 파라미터를 주입해 개인화 응답 생성
- FastAPI로 AI 추론 서버 구성, Supabase(pgvector) 연동 설계
- **Tech:** `Python` `FastAPI` `GPT-4o` `NLP` `NumPy` `sentence-transformers`

[![Repo](https://img.shields.io/badge/GitHub-capstone-181717?style=flat-square&logo=github)](https://github.com/puter8/capstone)

---

### 🥽 VR 객체 인식 콘텐츠 — 4DIVE
> Meta Quest 3 기반 VR 콘텐츠 개발 

- Unity와 C#을 활용한 Meta Quest 3 VR 환경 구축
- 실시간 객체 인식을 VR에 통합한 인터랙티브 콘텐츠 개발
- **Tech:** `Unity` `C#` `Meta Quest 3` `XR`

[![Repo](https://img.shields.io/badge/GitHub-VR_4DIVE-181717?style=flat-square&logo=github)](https://github.com/hunheay123/VR_4DIVE)
[![Repo](https://img.shields.io/badge/GitHub-Team_4DIVE_Quest3-181717?style=flat-square&logo=github)](https://github.com/hunheay123/Team_4DIVE_Quest3)

---

### 👁️ VOV (Vision of Vision) — 시각장애인 보조 AI 앱
> AI 기반 실시간 환경 인식 모바일 앱 | 팀 프로젝트

- **YOLO** 객체 탐지(WebSocket) + **OCR** 문자 인식 + TTS 음성 안내 통합
- **음성 명령만으로** 모든 기능 제어 (객체 탐지 → OCR → 내비게이션 전환)
- TMap API 연동 음성 내비게이션, 위험 물체 감지 시 햅틱·경적 알림
- AWS EC2 AI 서버(YOLO, OCR, STT)와 Socket.IO 실시간 통신
- **Tech:** `React Native` `Expo` `Socket.IO` `YOLO` `TMap API`

[![Repo](https://img.shields.io/badge/GitHub-vov--mobile--app-181717?style=flat-square&logo=github)](https://github.com/hunheay123/vov-mobile-app)

---

### 📚 Scholar — 자격증 스터디 플랫폼 백엔드
> 자격증 정보 조회 · 스터디 커뮤니티 · 일정 관리 REST API | 개인 프로젝트

- JWT(Access + Refresh Token) 기반 인증 시스템 구현
- 자격증 정보 조회, 즐겨찾기, 시험 일정 관리 API 개발
- 스터디 게시판 & 정보 공유 게시판 CRUD (인증 기반 권한 처리)
- 레이어드 아키텍처(Controller → Service → Repository) 설계
- **Tech:** `Java 17` `Spring Boot 3.5` `Spring Security` `JPA` `MySQL`

[![Repo](https://img.shields.io/badge/GitHub-Scholar_BE-181717?style=flat-square&logo=github)](https://github.com/hunheay123/Scholar_BE)

---

### 📅 EWhatodo — 이화여대 맞춤형 캘린더 앱
> 이화여대 학생을 위한 통합 일정·정보 관리 iOS 앱 | 팀 프로젝트 (2023.05 ~ 2023.06)

- 사이버캠퍼스, 이화앱, 한국장학재단 API 연동
- 개인 시간표 & 강의계획서 연동, 맞춤형 캘린더·To-Do 관리
- 관심 키워드 기반 공모전·동아리 알림 시스템
- **기여:** 유스케이스 다이어그램 설계, 온보딩 UI/UX 설계 (Proto.io)
- **Tech:** `iOS` `Oracle DB` `Proto.io`

[![결과물](https://img.shields.io/badge/결과물-Google_Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1P8xYwTcFUOwMi5-NfQpYEOb7yYjbdRbw/view?usp=sharing)

---

### 🛒 이커머스 추천 시스템
> 협업 필터링 + 딥러닝 기반 상품 추천 시스템 | 개인 프로젝트 (2024.07 ~ 2024.08)

- 협업 필터링(User-Based, Item-Based) + 콘텐츠 기반 하이브리드 추천 모델 구현
- Neural Collaborative Filtering(딥러닝) 실험 적용
- RMSE, Precision@K 성능 평가 → 추천 정확도 **20% 향상**
- Flask 기반 웹 API로 실시간 추천 결과 제공
- **Tech:** `Python` `TensorFlow` `Scikit-Learn` `Pandas` `Flask` `MySQL`

[![Colab](https://img.shields.io/badge/Colab-노트북_보기-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1MwMZMay8OW7joN67dI83mTVrx5iEu7Ck)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hunheay123&show_icons=true&theme=calm&hide_border=true&locale=kr)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hunheay123&layout=compact&theme=calm&hide_border=true&locale=kr)

</div>

---

## 📬 Contact

| | |
|--|--|
| 📧 Email | [bihunheay1@gmail.com](mailto:bihunheay1@gmail.com) |
| 📞 Phone | +82-10-7745-3871 |
| 🎓 School | 이화여자대학교 컴퓨터공학과 |
