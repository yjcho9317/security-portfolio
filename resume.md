<!--
[사람인/원티드 입력용 숏버전]

간략소개:
9년차 모바일 보안 엔지니어. 200여 기업 납품 보안 SDK 설계·운영, AI 위협 탐지 3건 리드. 50만 DL B2C 보안 앱 기술 리드. 현재 AI 보안 영역으로 확장 중.

자소서 (자유양식 1,000자 이내):
200여 금융·공공기관에 납품하는 보안 SDK를 메인 담당하며 KISA 백신 보안 성능 인증을 획득했습니다. Frida로 직접 우회 및 공격 PoC를 작성하며 선제 대응하고, Ghidra로 경쟁사 앱을 분석하며 탐지 로직을 개선해왔습니다. 딥페이크 탐지에서는 정확도 95%를 달성했지만 온디바이스 추론 제약으로 클라우드로 전환했고, 보이스피싱 탐지에서는 Recall 99.34%에도 FP Rate 22%를 확인하고 제품화를 보류했습니다. 클라우드 전환 프로젝트에서는 5인 팀의 앱 개발 리드를 맡았습니다. 현재는 ML 기반 악성앱 탐지 시스템을 설계하는 한편, MCP 서버를 직접 개발하면서 프로토콜의 보안 문제를 체감하고 보안 방화벽(mcp-fence)을 만들어 오픈소스로 배포했습니다. 모바일 보안에서 쌓은 경험을, AI 보안이라는 새로운 영역에서 이어가고 있습니다.
-->

# 조영진

## 간략 소개

9년차 모바일 보안 엔지니어. 200여 금융·공공기관에 납품하는 보안 SDK를 설계·운영하며, AI로 위협 탐지까지 확장해왔습니다.

50만 다운로드 B2C 보안 앱의 기술 리드를 맡았고, 현재는 보안을 위한 AI에서, AI를 위한 보안으로 영역을 확장하고 있습니다.

---

## 스킬

**Security:** Frida (Java/Native 후킹 기반 탐지 우회 검증, 안티프리다 탐지 구현), Ghidra (네이티브 .so 바이너리 분석), jadx, YARA (malware family 식별용 시그니처 룰 작성)

**Android:** Android SDK, Android NDK/JNI, Kotlin, Java, C++, Jetpack Compose, MVVM, Coroutines + Flow, Room, Hilt, WorkManager

**iOS:** iOS SDK, Swift, Objective-C, Xcode, CocoaPods

**AI/ML:** Python, PyTorch, TensorFlow Lite, MLflow, ML Kit

**Automation & DevOps:** n8n, Docker, Firebase, Git, Jenkins

**Agent Security:** TypeScript, MCP

---

## 경력

**라온시큐어** | AI 연구 2팀 | 책임연구원 | 2018.04 -- 현재

- AI 기반 악성앱 탐지 -- 전체/모델 개발 리드 (2026.02 -- 현재)
- 클라우드 서비스 전환 -- 앱 개발 리드, 5인 팀 (2025.02 -- 2025.10)
- AI 보이스피싱 탐지 연구 -- 전체/모델 개발 리드, 3인 팀 (2025.09 -- 2025.12)
- AI 딥페이크 탐지 -- 앱 개발 리드 / 모델 서브, 6인 팀 (2024.04 -- 2024.12)
- 라온 모바일 시큐리티 앱 설계/운영 (2021.07 -- 현재)
- TouchEn mVaccine (Android/iOS SDK) 메인 담당 (2019.04 -- 현재)
- TouchEn nxKey (macOS) 개발 (2019.04 -- 2021.09)
- TouchEn Transkey / mTranskey (Web SDK) 개발/운영 (2018.10 -- 2021.07)

---

## 경력기술서

### 주요 프로젝트

#### 1. TouchEn mVaccine SDK/APP 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 메인 담당 (Android/iOS SDK, App)
- **업무 기간:** 2019.04 -- 현재
- **기술 스택:** Android SDK, Android NDK, iOS SDK, Kotlin, Coroutines, Java, C++, Objective-C, Swift, Frida, Ghidra, jadx, YARA, Jenkins
- **프로젝트 개요:** 200여 금융·공공기관에 납품하는 모바일 보안 SDK. 1,000만+ 사용자 대상. KISA 백신 보안 성능 인증 획득. 공격자 관점의 리버스 엔지니어링을 통해 탐지 로직을 지속적으로 강화.

**주요 업무 및 성과:**

- Magisk/RootHide/KernelSU 등 진화하는 루팅 기법 연구/분석 및 탐지 기능 개발. Frida Java/Native 후킹 기반 공격 시뮬레이션으로 탐지 우회 벡터를 발견하고 NDK 레벨 방어 로직 강화. 안티프리다 탐지 구현.
- 경쟁사 보안 앱 리버스 엔지니어링 — jadx(DEX), Ghidra(네이티브 .so 바이너리)를 통한 탐지 로직 분석 및 벤치마킹.
- iOS 탈옥 탐지, 원격 탐지, 디버깅 탐지 모듈 개발.
- FakeCall, BankingTrojan 등 실제 공격 기법의 런타임 후킹 기반 PoC를 작성하여 방어 로직 사전 검증.
- 원격 탐지: 시스템, KNOX 등의 보안 정책(SandBox 등)을 우회하여 탐지하는 방법 개발.
- 보이스피싱 악성앱 실시간 탐지 기능 개발.
- NDK/JNI 기반 네이티브 모듈 개발. 시스템 레벨 탐지 로직 구현.
- Java→Kotlin 마이그레이션 및 MVVM 재설계. WorkManager/Coroutines 비동기 처리, ANR/메모리 릭 JNI 레벨 추적·해결. Jenkins CI/CD, Firebase 원격 로그 구축.
- URL Scheme 기반 앱-웹 간 통신 및 AIDL/Bound Service 기반 앱 간 통신 기능 개발.
- Android 5~16 메이저 버전, 삼성/LG/샤오미/Pixel 호환성 검증. 분기 릴리즈 운영. 플레이스토어 배포 및 업데이트 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.TouchEn.mVaccine.webs

#### 2. AI 기반 딥페이크 영상 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 / 모델 개발 서브 (6인 팀)
- **업무 기간:** 2024.04 -- 2024.12
- **기술 스택:** Android SDK, Kotlin, Python, PyTorch, TFLite, i3d, ResNet
- **프로젝트 개요:** 오픈소스 기반 딥페이크 탐지 모델을 모바일 보안 서비스에 응용. 앱 개발을 메인으로, 모델 추가 학습/튜닝을 서브로 담당.

**주요 업무 및 성과:**

- 자체 데이터셋 구축으로 동양인 탐지 정확도 65%→95% 달성.
- TFLite 양자화(FP32→FP16→INT8) 적용 후 온디바이스 추론 성능과 MediaProjection 프레임 캡처 제약(720p, 30fps 미달)을 측정하여 클라우드 비동기 아키텍처로 전환. 측정 데이터를 팀에 공유해 모델 담당자·기획과 합의 후 방향 확정.
- 라온 모바일 시큐리티 앱(50만 다운로드)에 탑재.
- 본 경험을 이어 온디바이스 딥페이크 탐지 AI SDK 개발 진행 중.

#### 3. AI 기반 보이스피싱 탐지 연구

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드 (3인 팀)
- **업무 기간:** 2025.09 -- 2025.12
- **기술 스택:** KoBERT, 경량 LLM, Python, NLP
- **프로젝트 개요:** 보이스피싱 통화를 AI로 실시간 탐지하는 연구. Recall 99.34%를 달성했으나 실서비스 적용에는 오탐이 많아 제품화 보류.

**주요 업무 및 성과:**

- 3인 팀 구성 및 기획부터 프로토타입 개발까지 전체 리드.
- KoBERT 기반 모델과 경량 LLM 모델을 통한 실시간 탐지 파이프라인 설계. Recall 99.34% 기록.
- 데이터 불균형으로 FP Rate 22%(정상 통화 5건 중 1건 오탐) 확인. 오탐률을 위험한 수치로 보고 체감 가능한 형태로 정리해 팀·상위 보고에 공유, 합의를 거쳐 제품화 보류 결정.
- 후속 방향으로 정상 대화 데이터 보강, 합성 데이터 보강 및 Hard Negative Mining 전략을 제안.

#### 4. AI 기반 악성앱 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드
- **업무 기간:** 2026.02 -- 현재
- **기술 스택:** Python, PyTorch, MLflow, YARA, Docker, Android
- **프로젝트 개요:** 시그니처 기반 탐지의 한계(제로데이 대응 불가, 난독화/리패키징 우회에 취약)를 해결하기 위해, ML 모델 기반 탐지 시스템을 설계/개발 중.

**주요 업무 및 성과:**

- APK 정적 분석 기반 특징 추출 파이프라인 설계 및 ML 모델 학습 아키텍처 구축. YARA로 known malware를 선탐지하고, 미탐지 샘플을 ML 모델로 분류하는 2단계 탐지 구조 설계.
- MLflow 실험 추적 구조까지 구축. 모델 레지스트리·FastAPI 서빙·GitHub Actions CI/CD는 PoC 수준에서 설계를 고정해둔 상태. 현재 악성앱 샘플 수집과 모델 학습을 진행하며 단계적으로 붙여나가는 중. Docker 기반 학습 환경 구성.
- 난독화/리패키징 기반 adversarial evasion을 고려한 모델 robustness 검증 설계 중.

#### 5. 라온 모바일 시큐리티 앱 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 개발 및 운영, 기술 리드
- **업무 기간:** 2021.07 -- 현재
- **기술 스택:** Kotlin, Coroutines + Flow, Room, Hilt, MVVM, Firebase Crashlytics, Firebase Analytics
- **프로젝트 개요:** B2C 모바일 보안 서비스 앱. 10가지 이상 보안 기능을 하나의 앱에서 제공.

**주요 업무 및 성과:**

- 기능 설계 및 개발 담당. 신규 기능(딥페이크 탐지 등) 도입 시 기술 검토 및 아키텍처 결정.
- 스미싱 문자 패턴화/정규화를 통한 실시간 탐지 기능 개발.
- 50만 다운로드, 1,000명+ 평가, 평점 4.5 기록.
- MVVM 리팩토링. Coroutines + Flow, Room, Hilt(DI) 선제 도입.
- 플레이스토어 배포/업데이트 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.raonsecure.mobile.security

#### 6. 클라우드 서비스 전환

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 (5인 팀)
- **업무 기간:** 2025.02 -- 2025.10
- **기술 스택:** Android SDK, Java, Kotlin
- **프로젝트 개요:** 기존 로컬 기반 보안 검사를 클라우드 기반으로 전환. 라이선스 기반 수익 구조에서 사용량 기반 과금 구조로의 전환을 목표로 설계.

**주요 업무 및 성과:**

- 로컬 기반 호출에서 클라우드 기반으로 아키텍처를 전환.
- 로컬 DB 용량 제약 제거로 검사 가능한 악성앱 탐지 패턴 5배 이상 확장 가능한 구조로 설계.
- 기존 CDN 기반 패턴 배포 대비 서버 비용 절감.
- 실제 사용 횟수 기반 집계 및 통계 수집 구조 설계.

---

### 기타 프로젝트

#### 1. TouchEn Transkey / mTranskey -- Web SDK 개발 및 운영

- **업무 기간:** 2018.10 -- 2021.07
- **기술 스택:** JavaScript, Java Servlet, REST API
- 웹 기반 보안 키보드 솔루션. 금융/공공기관 대상. 세션 미사용 통신 개발, RESTful API 설계/제공.

#### 2. TouchEn nxKey -- macOS App 개발

- **업무 기간:** 2019.04 -- 2021.09
- **기술 스택:** Objective-C, C++, macOS DriverKit
- macOS용 보안 키보드 솔루션. Hooking Daemon 개발, macOS DriverKit 기반 가상 키 발생 기능 구현.

---

### 사이드 프로젝트

#### 1. mcp-fence (1인 개발 / 오픈소스)

- **기술 스택:** TypeScript, MCP, OWASP, npm, GitHub Actions
- **프로젝트 개요:** nworks(MCP 서버)를 개발하면서 MCP 프로토콜의 보안 문제를 직접 겪어, 탐지 도구가 없어서 직접 만든 보안 프록시. MCP 클라이언트-서버 간 양방향 트래픽을 스캔하여 프롬프트 인젝션, 시크릿 유출, 도구 변조(rug-pull)를 탐지. OWASP MCP Top 10 중 7개 항목 커버. npm 배포.
- GitHub: https://github.com/yjcho9317/mcp-fence
- npm: https://www.npmjs.com/package/mcp-fence

#### 2. aiignore-cli (1인 개발 / 오픈소스)

- **기술 스택:** TypeScript, npm, GitHub Actions
- **프로젝트 개요:** AI 코딩 도구용 ignore 파일 생성 CLI. 바이브 코딩 시 private key 등 민감 정보가 AI에 노출되는 것을 방지. 보안 엔지니어 관점에서 개발.
- GitHub: https://github.com/yjcho9317/aiignore-cli
- npm: https://www.npmjs.com/package/aiignore-cli

#### 3. nworks (1인 개발 / 오픈소스)

- **기술 스택:** TypeScript, MCP, npm, GitHub Actions
- **프로젝트 개요:** NAVER WORKS API를 CLI와 MCP 서버로 래핑한 오픈소스 도구. awesome-mcp-servers 등록(PR 머지), Glama AAA 인증 획득.
- GitHub: https://github.com/yjcho9317/nworks
- npm: https://www.npmjs.com/package/nworks

#### 4. 셀카픽 (1인 개발 / 배포 중)

- **기술 스택:** Kotlin, Coroutines, Jetpack Compose, MVVM, ML Kit, AdMob
- **프로젝트 개요:** ML Kit 기반 얼굴 유사도 분석 앱. 기획부터 스토어 배포까지 단독 진행.
- Google Play: https://play.google.com/store/apps/details?id=com.yjcho.aiphotocleaner

---

## 학력

**신한대학교(4년제)** | 컴퓨터공학전공 | 편입/졸업 | 2015.03 -- 2018.08
- 졸업작품: 비콘 기반의 맞춤형 스마트 홈 서비스 (융복합지식학회 우수논문상 수상)

**신흥대학교(2/3년제)** | 웹프로그래밍전공 | 수료 | 2012.03 -- 2015.02

---

## 자격/수상

| 연도 | 항목 | 발급 |
|------|------|------|
| 2017.08 | 정보처리기사 | 한국산업인력공단 |
| 2017.10 | 2017년도 융복합지식학회 추계학술대회 논문 발표 우수논문상 | 융복합지식학회 |

---

## 자기소개서

라온시큐어에서 9년째 모바일 보안 SDK를 개발해왔습니다. TouchEn mVaccine을 메인으로 담당하며 200여 금융·공공기관에 납품해왔고, 1,000만 이상 사용자가 사용하는 SDK를 운영하며 KISA 백신 보안 성능 인증을 획득했습니다. B2C 앱인 라온 모바일 시큐리티는 50만 다운로드, 평점 4.5를 기록했습니다.

보안 SDK를 만드는 일은 방어만으로는 부족합니다. Frida로 직접 우회 및 공격 PoC를 작성하며 선제 대응하고, Ghidra로 경쟁사 앱을 분석하며 탐지 로직을 개선해왔습니다. 룰 기반으로는 한계가 있는 위협에는 AI를 적용했습니다. 딥페이크 탐지에서는 정확도 95%를 달성했지만 온디바이스 추론 제약으로 클라우드로 전환했고, 보이스피싱 탐지에서는 Recall 99.34%에도 FP Rate 22%를 확인하고 제품화를 보류했습니다. 로컬 기반 보안 검사를 클라우드로 전환하는 프로젝트에서는 5인 팀의 앱 개발 리드를 맡아 탐지 패턴 확장성 확보와 과금 구조 전환을 설계했습니다.

현재는 ML 기반 악성앱 탐지 시스템을 설계하는 한편, AI 에이전트 보안 영역으로 확장하고 있습니다. MCP 서버(nworks)를 직접 개발하면서 프로토콜의 보안 문제를 체감했고, 이를 탐지하는 보안 방화벽(mcp-fence)을 만들어 오픈소스로 배포했습니다. 모바일 보안에서 쌓은 경험을, AI 보안이라는 새로운 영역에서 이어가고 있습니다.
