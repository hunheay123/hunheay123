# 백은혜 | AI·백엔드 개발자

**이화여자대학교 컴퓨터공학과**  
AI 엔진과 백엔드 서비스를 연결해 실제 사용 가능한 제품으로 구현하는 개발자입니다. 현재 캡스톤 프로젝트에서 개인화 영어 회화 서비스의 AI 파이프라인과 엔진 전반을 맡고 있습니다.

[GitHub](https://github.com/hunheay123) · [이메일](mailto:bihunheay1@gmail.com)

## 대표 프로젝트

### CHARACTER MATRIX | 개인화 영어 회화 AI
이화여자대학교 캡스톤디자인·창업프로젝트 · 진행 중  
[저장소](https://github.com/puter8/capstone) · [서비스 데모](https://capstone-eight-virid.vercel.app/home) · [시연 영상](https://youtu.be/Ptlq6SM4C6g)

사용자의 영어 발화 스타일과 음성, 접속 이력을 분석해 AI 캐릭터의 말투와 반응에 반영하는 서비스입니다.

- **담당:** AI 엔진 및 파이프라인 설계·구현
- 발화 스타일을 Formality·Energy·Intimacy·Humor·Curiosity 5개 축으로 분석
- Formality·Humor·Curiosity는 텍스트 모델, Intimacy는 누적 접속 이력, Energy는 개인 기준 음성과 현재 음성의 억양 폭 차이로 계산
- 5축 점수를 가중치 행렬로 `tone_casual`, `energy_level`, `humor_level` 파라미터로 변환하고, EMA와 누적 로직으로 캐릭터 변화를 안정화
- FastAPI 기반 대화 파이프라인을 Gemini 2.5 Flash, Google Cloud STT/TTS, Supabase와 연동
- 실제 대화 코퍼스 정제와 사람 라벨 기반 모델 학습·평가 도구 구현

**결과물:** 웹 서비스, 대화 API, 5축 분석·캐릭터 변환 엔진, 모델 및 데이터 처리 도구, 데모 영상과 시각화 자료  
**기술:** Python · FastAPI · scikit-learn · TF-IDF · 문장 임베딩 · Gemini 2.5 Flash · Google Cloud · Supabase

### VOV | 시각장애인 보조 AI
팀 프로젝트 · [저장소](https://github.com/hunheay123/vov-mobile-app)

- YOLO 객체 탐지, OCR 문자 인식, TTS 음성 안내를 모바일 앱에 통합
- 음성 명령으로 인식 기능을 전환하고, TMap 길 안내 및 위험 요소 알림 연동
- AWS EC2 AI 서버와 Socket.IO 실시간 통신 구현

**결과물:** 객체·문자 인식과 음성 안내를 제공하는 React Native 앱  
**기술:** React Native · Expo · YOLO · OCR · Socket.IO · AWS EC2 · TMap API

### VR 객체 인식 콘텐츠 | 4DIVE
팀 프로젝트 · [VR_4DIVE](https://github.com/hunheay123/VR_4DIVE) · [Team_4DIVE_Quest3](https://github.com/hunheay123/Team_4DIVE_Quest3)

- Unity·C#으로 Meta Quest 3 VR 환경을 구성하고 객체 인식 결과를 인터랙션에 연결

**결과물:** Meta Quest 3용 VR 콘텐츠  
**기술:** Unity · C# · Meta Quest 3 · XR

### Scholar | 자격증·스터디 플랫폼 백엔드
개인 프로젝트 · [저장소](https://github.com/hunheay123/Scholar_BE)

- Spring Security와 JWT 인증, 자격증·시험 일정 REST API 구현
- 스터디 게시글 CRUD와 사용자 권한 처리

**결과물:** 계층형 구조의 백엔드 API 서버  
**기술:** Java 17 · Spring Boot · Spring Security · JPA · MySQL

### 이커머스 추천 시스템
개인 프로젝트 · [Google Colab](https://colab.research.google.com/drive/1MwMZMay8OW7joN67dI83mTVrx5iEu7Ck)

- 협업 필터링과 콘텐츠 기반 추천을 결합하고 Neural Collaborative Filtering과 비교
- RMSE·Precision@K로 평가하고 Flask API로 추천 결과 제공

**기술:** Python · TensorFlow · scikit-learn · Pandas · Flask · MySQL

## 기술 역량

**언어:** Java · Python · JavaScript · C · C#  
**AI·백엔드:** FastAPI · Spring Boot · Flask · scikit-learn · TensorFlow  
**앱·XR:** React Native · Unity · Meta Quest  
**데이터·도구:** Supabase · MySQL · Git

## Contact

[GitHub](https://github.com/hunheay123) · [bihunheay1@gmail.com](mailto:bihunheay1@gmail.com)
