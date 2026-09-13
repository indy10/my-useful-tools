# 1장 나의 첫 바이브 코딩

# 2장 효과적인 프롬프트로 AI 200% 활용하기

### Part 1. 나의 첫 바이브 코딩

- 바이브 코딩의 개념
- AI 코딩 도구의 종류 
- 클로드 아티팩트로 웹페이지 만들기

### Part 2. 효과적인 프롬프트로 AI 200% 활용하기

- 프롬프트의 중요성
- 5W1H 프레임워크
- PRD 작성과 4단계 전략

### ㅁ핵심 키워드 정리

#### [1] 바이브 코딩
AI와 대화하며 프로그램을 만드는 개발 방식

#### [2] 아티팩트
클로드가 결과물을 생성하고 미리보기를 제공하는 작업 공간

#### [3] 프롬프트
AI에게 전달하는 요청  
명확성, 구체성, 맥락 제공

#### [4] 5W1H
Why, Who, What, When, Where, How\
체계적 사고의 틀

#### [5] PRD
제품 기획서\
바이브 코딩의 효과적인 프롬프트

#### [6] 4단계 전략
뼈대 →  기능 →  디자인 →  점검

# 3장 클로드 코드 시작하기

### Part 1. 클로드 코드 설치

- 노드JS와 깃 설치
- 터미널 사용법

### Part 2. 손글씨 인식 프로그램

- MNIST 데이터세트 (study-01)
- AI 프로그램 만들기
- 배치 파일 생성

### Part 3. CLAUDE.md 활용

- 프로젝트 설정 파일
- 계층적 구조 관리
- 웹 버전 확장 (study-01, web version)
- 이미지 활용, 참조, 관리 명령어

### ㅁ핵심 키워드 정리

#### [1] 클로드 코드  
터미널에서 AI와 대화하며 파일 생성/수정하는 도구

#### [2] 노드JS / 깃  
실행 환경(노드JS)과 버전 관리 도구(깃)

#### [3] MNIST
손글씨 숫자 7만 장의 표준 데이터세트

#### [4] 배치 파일
윈도우 명령어를 모아 실행하는 .bat 파일

#### [5] CLAUDE.md
프로젝트 설정 파일, 시작 시 자동 로드

#### [6] /init
CLAUDE.md 자동 생성 초기화 명령어

#### [7] /memory
CLAUDE.md에 규칙 빠르게 추가하는 단축키

#### [8] 계층적 구조
루트에 공통, 하위에 특화 규칙 분리 관리


# 4장 클로드 코드 실전 활용

### Part 1. 단계별 프롬프트와 "할 일 관리 앱"

- RPD 기반 체계적 프로젝트 구현 (study-02)
  + PRD 작성
    - 클로드 웹에서 기획/설계
  + 프롬프트 변환
    - 단계별로 분할
  + 순차 실행
    - 클로드 코드에서 구현
  + 결과 확인
    - 각 단계 검증

- 할 일 관리 앱 5단계 구현
  + 기본 구조
    - 할 일 추가, 완료 체크, 삭제 기능
  + 카테고리
    - 업무/개인/공부, UI 개선, 분류 기능
  + 대시보드
    - 진행률 표시, 미니 차트, 수정 기능
  + 고급 기능
    - 다크 모드, 일괄 삭제, 단축키
  + 최적화
    - 정렬 옵션, 내보내기, 가져오기

- /status, /model, /help, /exit

### Part 2. 작업 재개와 효율성 높이기

- 세션 관리와 컨텍스트 최적화 (study-02)
- claude --resume, /resume, claude --continue, claude -c
- /context, /compact

### Part 3. 프로젝트 개선과 작업 관리

- 이미지 활용, 참조, 관리 명령어 (study-02, web_version)
  + 화면 캡처
    - 윈도우 캡처 도구로 현재 UI 스크린샷
  + 이미지 전달
    - 이미지 파일을 터미널에 드래그 앤 드롭
  + 요청 입력
    - "이 디자인을 PC용 풀스크린으로 바꿔줘"

- /config, /doctor, /export
  + /config
    - 설정 확인 및 변경
    - Auto-compact 설정
    - 테마 (Light/Dark)
    - 알림 방식
    - AI 모델 선택
  + /export
    - 대화 내용 내보내기
    - 클립보드 복사 또는 텍스트 파일 저장
    - 협업/백업용 활용
  + /doctor
    - 시스템 환경 진단
    - 프로젝트 실행 환경 점검
    - 문제 발견 시 해결 방법 제시

### ㅁ핵심 키워드 정리

#### [1] 단계별 프롬프트
PRD 기반으로 프로젝트를 나누어 구현하는 전략
#### [2] 세션 / -- resume
대화 상태 유지, 이전 작업 이어서 진행
#### [3] Shift + Tab
자동 승인 모드 전환 단축키
#### [4] 컨텍스트
AI가 기억하는 대화/작업 정보 메모리
#### [5] /context, /compact
컨텍스트 상태 확인 및 압축 명령어
#### [6] 멀티모달
텍스트와 이미지를 함께 이해하는 AI
#### [7] @ 기호
파일/폴더를 즉시 불러와 분석하는 참조
#### [8] /config, /doctor, /export
프로젝트 설정/진단/내보내기 관리 명령어

# 5장 게임 제작으로 배우는 체계적인 개발과 관리

### Part 1. 할루시네이션 없는 AI 콘텐츠 만들기

- 정확한 정보를 위한 검증 시스템 구축
- /memory로 교차 검증 가이드라인 구축, /clear로 초기화
- 상식 퀴즈 게임(study-03, 다운로드: study-03-basic - 1단계)
  + 4개 카테고리
    - 역사, 과학
    - 지리, 예술과 문화
  + 정답 판정
    - 즉시 피드백
    - 정답/오답 표시
  + 점수 시스템
    - 문제별 점수
    - 최종 결과 표시
  + 게임 흐름
    - 시작→ 문제풀이→ 결과 확인
- PRD를 3단계 프롬프트로 변환
- /clear

### Part 2. 자동화로 개발 효율 높이기 (다운로드: study-03-basic - 2단계)

- 2단계: 게임 모드 추가
  + 일반 / 스피드 / 서바이벌 모드
  + 점수 시스템 (난이도별 점수)
  + 힌트 기능 (점수 차감)
  + 제한 시간 룰
- 커스텀 명령어로 반복 작업 자동화
  + 나만의 단축 지시어
  + 마크다운 파일로 정의→ /명령어 한 번으로 복잡한 작업 자동 실행
- 커스텀 명령어 생성, 인수와 플레이스홀더 활용
  + /quiz-validate 한국사
    - 특정 카테고리 검증
    - $ARGUMENTS로 카테고리 받아 해당 카테고리만 검증
  + /quiz-range 1 20
    - 특정 범위 분석
    - $1, $2로 시작/끝 번호 받아 해당 범위 분석
  + /quiz-add 한국사 medium
    - 새 퀴즈 추가
    - 카테고리와 난이도 받아 새 문제 추가

### Part 3. 명령어 체이닝과 유지보수 전략 (다운로드: study-03-basic - 3단계)
- 3단계: 데이터 및 순위
  + 플레이 기록 로컬 저장
  + 리더보드 (순위표)
  + 개인 통계 대시보드
  + 사용자 프로필
- 여러 명령어를 연결한 자동화 워크플로
  + /quiz-check, /quiz-stats, /quiz-leaderboard
  + /help 항목 중 custom-commands
- && 연산자, 통합 명령어, AI 자동 생성
  + /teacher-dashboard, /export-report

### ㅁ핵심 키워드 정리

#### [1] 할루시네이션
AI가 그럴듯하지만 틀린 정보를 생성하는 현상

#### [2] /memory
CLAUDE.md에 검증 가이드라인 저장/편집

#### [3] /clear
대화와 컨텍스트를 완전히 초기화

#### [4] 커스텀 명령어
사용자가 직접 정의하는 단축 지시어

#### [5] 전역/프로젝트 명령어
~/.claude/commands vs .claude/commands

#### [6] 인수/플레이스홀더
$ARGUMENTS, $1, $2로 유연한 명령어 설계

#### [7] 명령어 체이닝
&& 연산자로 여러 명령어 순차 실행

#### [8] 통합 명령어
여러 작업을 하나로 묶은 자동화 파이프라인

# 6장 클로드 코드에서 API 설정하기

### Part 1. API와 OpenRouter

- API                                                                   
  + 프로그램과 프로그램 사이를 연결하는 다리
  + 간단한 요청만으로 복잡한 기능을 가져다 쓸 수 있게 해주는 통신 규칙
  + 날씨, 뉴스, 지도, AI
- 오픈라우터(OpenRounter), openrouter.ai
  + 여러 AI모델 API를 한곳에 모아 제공하는 통합 플랫폼
    - 모델 비교
      + 여러 AI 모델을 한눈에 비교
      + (google/gemma-3-27b-it:free, openai/gpt-oss-120b:free)
    - 무료/유료 필터
      + 무료 모델 쉽게 필터링 가능
    - 통합 API 키
      + 하나의 키로 다양한 모델 사용
  + API키 발급 (OPENROUTER_API_KEY=sk-or-v1-****) (study-04/.env)
  + .env, /init
  + AI모델의 API동작확인

### Part 2. 냉장고를 부탁해 앱 제작(3단계)

- 냉장고 사진을 업로드하면 식재료를 인식하고,\
        그 재료로 만들 수 있는 레시피를 추천하는 앱 (study-04)
- 이미지 인식 모델
- 사진에서 식재료 분석
- google/gemma-3-27b-it:free
- 텍스트 생성 모델
  + 맞춤 레시피 추천
  + openai/gpt-oss-120b:free
- PRD를 작성하고, [3단계] 각 단계별 개발 (study-04)\
    (차이점, Claude Code 내에서 PRD 작성후 단계별 1~3.md파일 생성)
  + 1단계 이미지 인식
    - 냉장고 사진에서 식재료 인식
  + 2단계 레시피 생성
    - 인식한 재료로 맞춤 레시피 추천
  + 3단계 레시피 저장
    - 사용자 프로필과 레시피 저장 기능
- openrouter.ai
  + Keys
  + Activity : AI모델의 사용현황, Cost확인

### ㅁ핵심 키워드 정리

#### [1] API
프로그램 간 통신을 위한 다리, 통신 규칙

#### [2] 오픈라우터
여러 AI모델 API를 한곳에 모은 통합 플랫폼

#### [3] API키
사용자를 인증하는 비밀 열쇠

#### [4] .env / .gitignore
API 키 저장 및 보안 관리 파일

#### [5] 다중 AI 모델 연동
이미지 인식 + 텍스트 생성 모델 함께 활용

#### [6] PRD 단계별 개발
복잡한 앱을 작은 단위로 나누어 점진적 구현


# 7장 클로드 코드 AI 에이전트로 개발팀 구성하기

### Part 1. 클로드 코드의 AI 에이전트 이해하기 (study-04, 냉장고를 부탁해) 

- 서브에이전트 생성과 협업
- 에이전트 개념, /agents 명령어, 서브에이전트 생성과 협업
- 에이전트(Agent)
  + 사람이 매번 세부 지시를 내리지 않아도 정해둔 목표와 규칙에 따라 스스로 판단하고 작업을 수행.
  + 개발자가 '무엇을 달성할지'를 지정하면 에이전트가 '어떻게 할지'를 결정．
  + 목표 설정→ 에이전트 판단→ 작업 수행→ 결과 보고．
- 서브에이전트
  + 특정 작업을 전문적으로 수행하도록 만든 독립형 AI도우미. 
  + 사용자가 직접 역할, 모델, 권한을 개별 설정.
  + 예) 코드 리뷰어, 최적화 전문가, UX 디자이너
- 서브에이전트의 특징
  + 독립적인 AI 모델 선택\
    에이전트별로 Opus, Sonnet, Haiku 등 다른 모델 선택 가능
  + 세밀한 권한 설정\
    읽기 전용, 쓰기 권한 등 안전하고 체계적인 작업 분담
  + 작업 맥락 유지\
    여러 에이전트가 순차적으로 협업할 때 맥락 공유
- /agents 명령어 삭제됨. 아래 명령어로 생성.
  + create a code-reviewer subagent that .... 
  + edit the file directly. 

### Part 2. AI에이전트로 소프트웨어 개발 자동화하기 (study-05)

- AI개발팀 구축과 앱 만들기
- AI개발팀 구축, AI공감 다이어리, PDF요약 AI앱 만들기
- AI개발팀 서브에이전트
  + 제품 기획 관리자 (PM), product-planning-manager
    -  PRD 작성, 목표/기능 정의, 일정 관리
  + 백엔드 개발자, backend-developer
    - 서버 구축, DB 설계, 핵심 로직
  + 프런트엔드 개발자, frontend-developer
    -  화면 설계, UI 구현, 인터페이스
  + 품질 보증 엔지니어, qa-engineer
    -  버그 탐지, 성능 테스트, 안정성 확보
  + AI 통합 전문가, ai-integration-expert
    -  AI 모델 연동, 최적화, 솔루션 구현

- AI공간 다이어리 앱 (study-05, .env, /init)
  - 일기를 쓰면 감정을 분석하고 공감의 글을 덧붙여주는 앱
  - 에이전트별 역할
    + backend-developer: 텍스트 입력과 저장 기능 구현
    + frontend-developer: 일기 작성 UI와 감정 분석 결과 표시
    + qa-engineer: 전체 시스템 테스트와 버그 수정
  - API: OpenRouter의 무료 모델 사용, .env 파일의 API 키 참조
  - AI 공감 다이어리 결과
    + 일기 작성\
      오늘의 감정과 생각을 자유롭게 기록
    + 감정 분석\
      AI가 텍스트 속 감정을 자동으로 탐지
    + 공감 메시지\
      감정에 맞는 위로와 격려의 글 제공

- PDF요약 AI앱
    + PDF 파일을 업로드하면 텍스트를 추출하고 요약, 정리, 분석하는 앱
      - 요약 모드 선택\
        일반 요약, 간단 요약 등 다양한 모드
      - PDF 업로드\
        드래그&드롭으로 간편하게 파일 업로드
      - 결과 표시\
        요약된 내용을 깔끔하게 정리하여 표시
- claude --dangerouly-skip-permission

### ㅁ핵심 키워드 정리

#### [1] 에이전트
목표와 규칙에 따라 스스로 판단하고 작업 수행하는 AI 대리인
#### [2] AI 서브에이전트
특정 작업을 전문적으로 수행하는 독립형 AI 도우미
#### [3] /agents
서브에이전트를 생성하고 관리하는 클로드 코드 전용 명령어
#### [4] 코드 리뷰
코드의 버그와 규칙 위반을 점검하고 개선점 제안
#### [5] 최적화
프로그램의 속도와 효율성을 향상시키는 성능 개선 작업
#### [6] UX 디자인
사용자가 쉽고 편리하게 이용할 수 있도록 인터페이스 설계
#### [7] AI개발팀
PM, 백엔드, 프런트엔드, QA, AI 전문가로 구성된 에이전트 팀
#### [8] 에이전트 협업
여러 에이전트가 역할을 분담해 프로젝트를 완성하는 방식

### study 01~06 요약
- study-01 : 손글씨 인식(MNIST)
- study-02 : 할 일 관리
- study-03 : 상식 퀴즈 게임(study-03-basic 1/2/3단계)
- study-04 : 냉장고를 부탁해 (서브에이전트: code-reviewer, system-optimizer, ux-designer)
- study-05 : AI공감 다이어리, PDF요약 AI앱 (index.html, index_pdf.html)
- study-06 : 
```
           1. Notion MCP
           2. Sequential Thinking MCP
           3. Context7 MCP 
           4. Playwright MCP
           5. GitHub MCP
           6. vercel.com / superbase.com
```

# 8장 MCP로 클로드 코드의 한계 넘어서기
### Part 1. MCP로 이해하고 클로드 코드와 연결하기
- AI의 무한 확장 가능성
- MCP 개념, 로컬/원격 MCP, 노션 MCP 연동
- MCP (Model Context Protocol) 
  + AI 모델이 외부 데이터, 도구, 서비스와 연결될 때 사용하는 표준화된 통신 규약.
  + AI가 다양한 시스템과 일관된 방식으로 대화하고 협업할 수 있게 해주는 다리 역할!
- API vs. MCP 차이점
  + API
    - 서로 다른 프로그램이 데이터를 주고받을 수 있게 하는 인터페이스. 
    - 다른 서비스의 기능을 잠시 빌려오는 방식.
    - 예: 오픈라우터 API로 AI 모델을 가져와 텍스트 생성에 사용
  + MCP
    - 여러 API와 파일, 데이터베이스를 한꺼번에 통합해 연결하는 프로토콜. 
    - AI가 외부 시스템에 직접 접근 가능.
    - 예: AI가 직접 파일 시스템 조작, 데이터베이스 조회/수정
  + 로컬MCP
    - MCP 중개 프로그램을 내 컴퓨터 안에서 직접 실행
    - 인터넷 없이 작동, 빠른 응답 속도, 개인정보 보호 유리
    - claude mcp add [이름] -s local --[실행 명령]
  + 원격MCP
    - 인터넷상 외부 서버에서 실행
    - 설정이 간편, 여러 사용자와 공유 용이, 명령어 한 줄로 연결
    - claude mcp add --transport http [이름] [서버 URL]
  + 노션MCP 연동하기
    - 터미널에서 claude mcp add 명령으로 MCP 서버 설치
    - 클로드 코드 실행 후 /mcp명령어로 목록 확인 → 노션 계정 인증
    - 클로드 코드에서 노션MCP 기능 사용 (15개 도구 제공)
    - claude mcp add --transport http notion https://mcp.notion.com/mcp
  + Sequential Thinking MCP 연동하기
    - claude mcp add sequential-thinking -s local -- npx @modelcontextprotocol/server-sequential-thinking@latest
    - claude mcp add sequential-thinking -s local -- cmd /c npx -y @modelcontextprotocol/server-sequential-thinking@latest

### Part 2. MCP로 구현하는 완전 자동화 개발 환경
- 테스트 자동화와 버전 관리
- Playwright 테스트 자동화, 깃허브 버전관리
- Context7
  + 클로드 코드가 항상 최신 문서를 참고하도록 돕는 지식 연결 도구
  + claude mcp add --transport http context7 https://mcp.context7.com/mcp --header "CONTEXT7_API_KEY: YOUR_API_KEY"
- Playwright
  + 웹 사이트를 자동으로 테스트하고 비를 검증하는 브라우저 제어 도구
  + claude mcp add playwright -- npx @playwright/mcp@latest
  + claude mcp add playwright -- cmd /c npx @playwright/mcp@latest
- GitHub
  + 프로젝트를 버전 관리하고 자동으로 업로드하는 협업 도구
  + claude mcp add --transport http github https://api.githubcopilot.com/mcp -H 'Authorization: Bearer $(grep GITHUB_PAT .env | cut -d '=' -f2)'
- MCP 서버 찾는 방법: 구글에서 "[서비스명] MCP" 검색→ 깃허브 문서 확인

### Part 3. 데이터베이스 연결해 진짜 서비스 만들기
- 배포와 데이터베이스 연동
- 배포는 내 애플리케이션을 외부의 인터넷에 연결된 제3의 서버에 올리는 과정입니다.\
  항상 켜져 있는 서버에서 앱을 실행해 언제, 어디서든 URL로 접속할 수 있습니다.
- Vercel배포, Supabase데이터베이스 연동
- Vercel
  + 작성한 코드를 깃허브에 올리면 자동으로 빌드, 배포해 주는 클라우드 플랫폼. 간단한 웹 애플리케이션은 무료로 배포 가능!
  + 깃허브 저장소 준비→ Vercel에 깃허브 인증→ 배포할 저장소 선택→ 즉시 URL 발급!
- supabase로 데이터베이스 연동
- supabase는 데이터베이스 구축을 자동화해 주는 클라우드 데이터베이스 플랫폼입니다.
  + 무료 플랜 제공, API 자동 생성, 실시간 동기화, 다중 사용자 지원
- supabase MCP
  + claude mcp add --transport http supabase "https://mcp.supabase.com/mcp"
  + claude mcp add supabase -s local -e SUPABASE_ACCESS_TOKEN=<Supabase API 토큰> -- cmd /c npx -y @supabase/mcp-server-supabase@latest
- 클라우드 스토리지의 장점
  + 어디서나 동일한 데이터 접근 가능
  + 여러 기기에서 같은 리스트 확인
  + 여러 사람이 공유/협업 가능
  + 데이터 영구 보존
- 로컬 스토리지의 한계
  + 다른 컴퓨터/브라우저에서 데이터 공유 안됨
  + 브라우저 캐시 삭제 시 데이터 사라짐
  + 기기를 바꾸면 데이터 유실
  + 시크릿 모드에서 데이터 보이지 않음
- study-06
  + notion, context7, Playwright, github, vercel, supabase
  + claude mcp add --scope user --header "CONTEXT7_API_KEY: ctx7sk-e3754db5-7e20-42c5-8c43-9da0d7055bd5" \
    --transport http context7 https://mcp.context7.com/mcp
  + claude mcp add --transport http github https://api.githubcopilot.com/mcp \
    -H 'Authorization: Bearer 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'

### ㅁ핵심 키워드 정리
#### [1] MCP
AI 모델이 외부 서비스와 연결되는 표준 통신 규약
#### [2] 로컬 MCP
내 컴퓨터 안에서 직접 실행하는 MCP
#### [3] 원격 MCP
인터넷상 외부 서버에서 실행하는 MCP
#### [4] Playwright
웹 자동 테스트 도구
#### [5] 버전 관리
코드 변경 이력을 기록하고 관리
#### [6] 배포
앱을 외부 서버에 올리는 과정
#### [7] Vercel
자동 빌드/배포 클라우드 플랫폼
#### [8] Supabase
클라우드 데이터베이스 플랫폼

----
### 추가 프롬프트
```
선생님 모드 도구인 quiz-class-compare.md quiz-class-roster.md quiz-class-stats.md 
quiz-student-report.md quiz-teacher.md quiz-weak-topics.md 에는 teacher로 
시작하는 도구 특성이 보이도록 명령어 이름을 수정해줘
```

```
.claude/commands/export-report.md 파일을 새로 만들어 줘.
/teacher-dashboard의 결과를 teacher-dashboard.html로 저장해줘
teacher-dashboard.html을 읽어서 CSV 또는 PDF로 저장할 수 있도록 해줘
```


(study-03)
```
code-reviewer 서브에이전트를 만들어줘.
역할 : 코드를 읽고 버그는 없는지, 코딩 규칙에 따라 올바르게 작성되었는지를 점검하고 성능 최적화를 제안하는 전문 코드 품질 검토자.
```

```
system-optimizer 서브에이전트를 만들어줘.
역할 : 애플리케이션의 작동을 원활하게 개선하고 속도를 빠르게 만들며 병목 지점을 찾아서 해결하는 시스템 최적화 엔지니어.
```

```
ux-designer 서브에이전트를 만들어줘.
역할 : 사용자가 쉽고 편하게 이용할 수 있도록 화면 디자인, 버튼 배치, 에러 메시지를 개선하는 사용자 경험 전문가.
```

```
code-reviewer로 "상식 퀴즈 게임" 애플리케이션 코드 전체를 리뷰한 뒤, 
발견한 문제를 system-optimizer가 수정해서 성능 최적화한 다음, 
ux-designer가 사용자 경험을 개선하게 해 줘
```

```
qa-engineer 서브에이전트를 만들어줘.
역할 : 전체 시스템의 기능 테스트, 에러 처리 검증, 성능 최적화, 코드 리뷰를 수행하는 품질 관리 전문가. 버그 발견, 사용성 개선사항 제안.
```

```
product-manager 서브에이전트를 만들어줘.
역할 : 전체 개발 일정을 관리하는 프로덕트 매니저로서 PRD를 작성하여 제품의 목표, 기능, 사용자 요구사항을 정의한다
```

```
backend-developer 서브에이전트를 만들어줘.
역할 : 서버 아키텍처 설계, API 개발, 데이터 처리, 외부 서비스 통합, 보안 및 성능 최적화를 담당하는 서버 사이드 개발 전문가. 안정적이고 확장 가능한 백엔드 시스템 구축.
```

```
frontend-developer 서브에이전트를 만들어줘.
역할 : 사용자 인터페이스 설계 및 구현, 반응형 디자인, 웹 접근성, 성능 최적화를 담당하는 클라이언트 사이드 개발 전문가.
```

```
ai-integration-expert 서브에이전트를 만들어줘.
역할 : LLM 및 AI 서비스 통합, 프롬프트 최적화, 모델 파인튜닝, AI 파이프라인 구축을 담당하는 인공지능 전문가. 여기서는 OpenRouter API를 통해 DeepSeek 모델과 연동하여 텍스트 생성, 요약을 구현하는 LLM 활용 전문가
```

```
code-reviewer에게 냉장고를 부탁해 어플리케이션 코드를 검토하게 해줘.
```

```
code-reviewer로 "냉장고를 부탁해" 애플리케이션 코드 전체를 리뷰한 뒤, 
발견한 문제를 system-optimizer가 수정해서 성능 최적화한 다음, 
ux-designer가 사용자 경험을 개선하게 해 줘
```

```
AI 공감 다이어리를 만들어 줘. 오늘 있었던 일을 한 줄로 쓰면, AI가 감정을 분석하고 공감하며 위로해 주는 일기 애플리케이션이야.
backend-developer가 OpenRouter API를 연동해서 감정 분석과 공감 메시지를 생성하는 기능을 구현해 줘.
openai/gpt-oss-120b:free 무료 모델을 사용하고, API 키는 현재 폴더의 ‘.env’ 파일에 저장된 것을 사용해.
frontend-developer가 따뜻하고 편안한 느낌의 일기장 UI를 만든 다음, qa-engineer가 실제로 여러 상황에서 문제없이 작동하는지 테스트해 줘.
문제를 발견하면 완전히 해결할 때까지 수정하고, 최종 버전을 브라우저에서 바로 열 수 있는 ‘index.html’ 파일로 만들어 줘.
```

```
PDF 문서를 업로드하면 AI가 요약해주는 웹 애플리케이션을 만들 거야.
먼저 product-manager가 PDF 문서 요약 앱의 상세 PRD와 기능 명세를 작성하고,
backend-developer가 PDF 파일 업로드, 텍스트 추출 기능을 구현해.
ai-integration-expert가 OpenRouter API를 연동해서 추출된 텍스트를 요약하는 기능을 구현해 줘.
openai/gpt-oss-20b:free 무료 모델을 사용하고, API 키는 현재 폴더의 ‘.env’ 파일에 저장된 것을 사용해.
frontend-developer가 드래그&드롭 파일 업로드 UI와 요약 결과를 깔끔하게 표시하는 한글 인터페이스를 구현한 다음,
qa-engineer가 실제로 여러 상황에서 문제없이 작동하는지 테스트해 줘. 
문제를 발견하면 완전히 해결할 때까지 수정하고, 최종 버전을 브라우저에서 바로 열 수 있는 ‘index_pdf.html’ 파일로 만들어 줘.
```
