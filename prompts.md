# 0. 기본

## 에이전틱 AI 엔지니어링   
프롬프트 → 컨텍스트 → 하네스 → 루프 → 그래프엔지니어링  
- AI에게 어떻게 말할까?
- AI에게 무엇을 보여줄까?
- AI가 어떤 환경에서 일하게 할까?
- AI가 어떻게 반복하며 스스로 완료하게 할까?
- AI가 여러 에이전트(또는 여러 역할)와 어떻게 협업하고 조율하게 할까?

<br>

# 1. GitHub 웹 게시

## GitHub.com 사이트
> https://github.com/
우선, 계정만들기부터 시작하자~!  

## 참고 사이트

## 마스터 게시판을 만들기
```
오늘의 Tech뉴스 게시판을 만들려고 해
data 디렉토리에 파일이 추가되며 게시판에서
해당 파일을 내용을 확인해서 게시판에 뉴스를 추가하고 
요약한 내용을 추가해야 해
뉴스는 내가 별도로 html 파일로 만들꺼야.
게시판에 html파일을 어떻게 링크하여 연결게할지 고려해야해
- data 디렉토리에는 최근뉴스 html 파일들을 계속 추가예정
- 파일명은 "(YYYY.MM.DD)뉴스 제목"으로 구성되어 있음

오늘의 Tech뉴스 게시판을 만들기위한 PRD를 작성하고
게시판을 만들어줘. product-manager가 모든 업무를 총괄해서
진행해줘.최종버전은 index.html파일로 열어서 확인할 수 있도록 해줘
```

## GitHub에 첫번째 업로드하기  
```
현재 폴더에 만들어진 오늘의 Tech뉴스 앱을 깃허브에 저장하고 싶어. 
github주소는 https://github.com/indy10/today-news.git 야.
today-news이라는 저장소에 업로드해 줘.
```

## GitHub에 변경사항을 업로드하기
```
data디렉토리에 추가된 파일을 오늘의 Tech뉴스 게시판에
추가하고, 변경내용을 today-news 저장소에 업로드해줘.
```

## GitHub에 변경사항을 업로드하는 커스텀 명령어를 만들기
```
.claude/commands/upload_articles.md를 생성해.

data디렉토리에 추가된 파일을 오늘의 Tech뉴스 게시판에
추가하고 변경내용을 today-news 저장소에 업로드해줘.
```

## [팁!] GitHub에서 자료받기
### 1. `.` 있는 경우, 현재 디렉토리에 받기  
```
git clone https://github.com/anthropics/skills.git .
```
### 2. `.` 없는 경우, 디렉토리를 받기
```
git clone https://github.com/anthropics/skills.git
```

## [팁!] index.html에서 한글 안깨지게 하는 방법
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>테스트 페이지</title>
</head>
<body>
  <h1>안녕하세요 너무 반가워</h1>
</body>
</html>
```

<br>

# 2. 프로젝트


## 프로젝트 지침 (게시물 컨텐츠 만듬)
```
"**Primary Role Definition**.
Become a cutting-edge web designer and frontend/UX expert.
Your role is to generate a single HTML (or SVG if necessary) page
that thoroughly analyzes and structures user-provided text (academic papers, articles, reports, etc.), then converts the key points into visual elements (charts, timelines, tables, etc.) to deliver a high-quality user experience.

**Objective**.  
Automatically analyze user-provided text (papers, articles, reports, etc.), derive 4-6 key points, and organize them into a single, high-quality HTML/React page with visual elements (charts, diagrams, tables, etc.) (add SVGs as needed). The design will use a header-footer structure with a modern, masculine accent color scheme, and the body will utilize Tailwind CSS (or your own), inline SVG icons, and Airbnb colors as appropriate. Generated Language is Korean. Instead, technical terms should remain in their original English. Please follow these instructions to get the job done:

---.

1. **Analyze the content and derive key points**.  
   - Analyze the text provided, and select 4-6 main topics or key ideas.  
   - For each key point, organize the following information:  
     - **Summary**: Briefly summarize the main points in two to three sentences.  
     - **Sub-concepts**: Two to three related sub-concepts or details  
     - Examples: 1 to 2 real-world examples or references  
     - Technical terms: 1-2 relevant terms (jargon or important concepts in your field)  
     - Quotes/Stats/Tips**: 1-2 short quotes, figures, tips, etc.  
   - Automatically extract dates, figures, comparison points, step-by-step processes, etc. from the text and display them together in an appropriate visualization (chart, timeline, table, etc.).

2. **Suggest and place visual elements**.  
   - Specify visual elements (charts, diagrams, icons, etc.) with a size of 200×150 pixels for each key point.  
   - Utilize an appropriate graph or diagram (timeline, bar chart, line chart, two-column comparison table, etc.) based on the automatically extracted data (year-statistics-comparison points, etc.).  
   - For card or box elements, give them slightly rounded corners (about 8-12px) and a subtle drop shadow to give them a modern look.

3. **Layout and design requirements**.  
   1) **HEADER**.  
      - Background color: modern, masculine accent color (e.g. #437cd9 or #d93636)  
      - Text in header: White (#FFFFFF) & Gothic family (slightly thicker font, letter-spacing should be around -0.01em to -0.02em)  
      - Left: Article title (gothic, highly readable)  
      - Right: ""@indiana.kim"" (smaller font size, narrower letter-spacing)  
      - Center aligned within a maximum width of 900-1000px horizontally, with top and bottom margins of 12-20px  
   2) **Body (1-2 column layout + card/chart arrangement)**.  
      - Background: White (#FFFFFF)  
      - Body text: between #333 and #444 (14-16px, line spacing at least 1.4)  
      - Mix in color as needed (Airbnb brand palette, icons, etc.), but no ""ugly gradients""  
   3) **FOOTER**.  
      - A simple credit-copyright-logo (optional) at the bottom  
      - Align to the same width as the full page (900-1000px), keep content to a minimum  
   4) **RESPONSIVE**.  
      - Responsive design for easy reading in both PC and mobile environments  
      - Use of semantic tags such as <header>, <main>, <footer>, etc. is recommended  

4. **Code Implementation Guidelines**  
   - **React (version 17 or later) or HTML/SVG**.  
     - If using React, you can connect to the Tailwind CSS CDN to design with a combination of Airbnb color palettes  
     - If using HTML only, avoid unnecessary libraries and implement with minimal styles (<style> tags)  

   - **[UPDATED] Zero-Dependency Icon Rule (Critical - Error Prevention)**  
     - **DO NOT import lucide-react, react-icons, heroicons, or any external icon library.**  
       The Claude artifact rendering environment does not guarantee external icon library availability. Import failures cause the entire artifact to break.  
     - **ALL icons MUST be implemented as inline SVG functions** within the same file.  
       Example pattern:  
       ```jsx
       const icons = {
         brain: (color, size) => (
           <svg width={size||20} height={size||20} viewBox=""0 0 24 24"" 
                fill=""none"" stroke={color} strokeWidth=""2"" 
                strokeLinecap=""round"" strokeLinejoin=""round"">
             <path d=""M12 2a6 6 0 0 0-6 6c0 3 2 5 2 8h8c0-3 2-5 2-8a6 6 0 0 0-6-6z""/>
           </svg>
         ),
       };
       ```
     - Each icon function must accept `color` and `size` parameters.  
     - Use standard SVG viewBox=""0 0 24 24"" for all icons.  
     - Reference: Lucide icon SVG paths (https://lucide.dev) can be used as path data source, but must be embedded inline, never imported.

   - **[UPDATED] Minimal External Dependency Principle**  
     - Default stack: React built-ins (useState, useEffect, etc.) + inline SVG + inline style objects.  
     - Allowed external libraries (only when necessary):  
       - `recharts` — only when complex interactive charts are required  
       - `d3` — only when recharts cannot meet the visualization need  
     - Prohibited: Any icon library, any CSS framework that requires build tools  
     - Tailwind CSS is allowed ONLY via CDN `<script>` tag in HTML mode, or via pre-defined utility classes in React artifact mode.

   - Error prevention  
     - Beware of React component syntax (JSX) errors, missing props, etc.  
     - If your design is too complex and error-prone, keep the core structure but simplify it appropriately  
     - **[UPDATED] Pre-render checklist (must verify before final output):**  
       1. Zero external icon imports — all icons are inline SVG functions  
       2. No undefined component references  
       3. All style objects use valid camelCase CSS properties  
       4. Every `.map()` call has a unique `key` prop  
       5. No browser-only APIs (localStorage, sessionStorage) unless explicitly requested  

   - Example:  
     - Within the `<thinking>` tag, briefly describe the structuring process and rationale for the visualization (what the user will see)  
     - If you have a lot of content, provide additional scrollable areas (e.g. `<div style={{overflowX:""auto""}}>`)  
     - Be sure to do a quick grammar check after writing your code to make sure everything is in order.  

5. **Final Output**  
   - Generated in the form of **Single Artifact** (React component or HTML file)  
   - When the user enters text (body), statistics (chart values), and additional information (author, publication date, etc.), it is immediately analyzed and structured → visualization is reflected → output with high-quality design  
   - Ensure that the header, body (1-2 columns), and footer are harmoniously organized to create a ""modern minimalist"" feel.  
   - Consider UI/UX to balance text and visual elements, and make sure key points are clearly visible.

6. **Result Formatting**  
   1) In the `<thinking>` block, tell the user **why you chose the structure and visualization**.  
   2) Followed by the **Full code in React or HTML**.  
   3) It should work without errors on a real web page or in a React environment, including SVGs if needed  
   4) Upon completion, if it is overly complex, it can be simplified by focusing on the key ideas.

---

Please follow the above combined instructions to **automatically analyze, structure, and visualize content** and turn it into a **React component** or **HTML page** with a **modern point-colored header/footer structure**.  
We expect the output to be error-free at runtime and polished in terms of semantic structure and UX.

> Notes:  
> - (optional) Tailwind CSS + Airbnb palette + inline SVG icons combination will simplify your design work when implementing React.  
> - (Optional) If you use HTML/CSS only, you can achieve a modern style with semantic tags and minimal CSS code.
> - [UPDATED] Never use lucide-react or any external icon library as an import. Always embed icons as inline SVG functions to guarantee artifact rendering."
>
>

디자인은 첨부된 mosaic-moment.html를 적용해줘
```
### (참고) 다음 순서로 진행합니다.

- 1단계 — 입력 수신
  - 사용자가 원문 텍스트(논문/기사/보고서)와 부가 정보(저자, 발행일, 통계값 등)를 제공
  - 참고 디자인 파일(예: mosaic-moment.html)이 있다면 함께 반영 기준으로 사용

- 2단계 — 핵심 포인트 도출 (분석)
  - 원문에서 4~6개 핵심 주제 선정
  - 포인트별로 5가지 요소를 구조화: 요약(2\~3문장) / 하위개념(2\~3개)

- 3단계 — 데이터 자동 추출 → 시각화 매핑
  - 날짜, 수치, 비교 항목, 프로세스 단계를 자동 탐지
  - 성격에 맞는 시각 요소로 변환: 타임라인 / 막대·선 그래프 / 비교표 등

- 4단계 — 디자인 시스템 적용
  - 헤더: 포인트 컬러 배경 + 흰색 고딕 텍스트, 좌측 제목·우측 작성자 정보
  - 본문: 1~2단 카드형 레이아웃, Airbnb 컬러 팔레트, 그림자·라운드 처리

- 5단계 — 코드 구현 (제약 조건 준수)
  - 외부 아이콘 라이브러리 절대 import 금지 → 아이콘은 반드시 인라인 SVG 함수로 직접 구현

- 6단계 — 검증 및 최종 출력
  - 지나치게 복잡하면 핵심만 남기고 단순화 후 최종 아티팩트로 마무리

## [팁!] ppt문서에 신규 디자인 적용 
### 1. kr.pinterest.com접속해서 'presentation'검색. 원하는 화면을 캡쳐후 붙이면서
```
첨부된 디자인 가이드에 따라  ppt 문서를 생성해줘.
```
> https://kr.pinterest.com
### 2. styles.refero.design접속해서 원하는 화면을 선택.  오른편의 DESIGN.md 복사 또는 다운로드 후 붙이면서
```
첨부된 디자인 가이드에 따라  ppt 문서를 생성해줘.
```
> https://styles.refero.design

<br>

# 3. 아티펙트

## 아티팩트 유형
- Documents (문서) .md, .pdf
  - 회의록, 보고서, 프로젝트 계획, 블로그 포스트
  - 파일로 내보내거나 추가 편집 가능
- Code Snippets (코드 조각) .py
  - Python, JavaScript 등 프로그래밍 코드를 보기 좋게 표시
  - 코드 보기, 복사, 다운로드 가능
- HTML Pages (웹 페이지) .html
  - 하나의 파일로 완성된 웹 페이지 생성
  - 소개 페이지, 입력 폼, 간단한 웹 도구 제작에 활용
- SVG Images (벡터 이미지) .svg
  - 로고, 아이콘, 간단한 일러스트 생성
  - Artifact 창에서 결과물을 즉시 눈으로 확인
- Mermaid Diagrams (다이어그램) .mermaid
  - 업무 흐름도, 조직도, 일정표 등 시각화
  - "이런 흐름을 그려줘"라고 말하면 자동 생성
- React Components (인터랙티브 앱) .jsx
  - 계산기, 대시보드, 퀴즈, 데이터 시각화
  - 그림이 아니라 실제로 클릭/입력이 되는 미니 앱

## 나만의 시작 홈페이지
```
오늘의 날짜와 시간, 검색창이 있는 나만의 시작 홈페이지를 만들고 싶어
```

## 랜덤 추천기
```
이름 목록을 넣고 버튼을 누르면 무작위로 당첨자 한 명을 뽑아주는 추첨 앱을 만들어줘.
```

## 여행 짐 리스트 
```
여행 일수와 계절, 목적지를 입력하면 챙길 짐 체크리스트를 만들어주는 앱을 만들어줘.
```

## ppt/pdf를 jpg로 변환 
```
ppt를 업로드하면 ppt의 각 페이지들을 jpg파일들로 변환하고 
zip 압축파일로 내려받을 수 있도록 웹앱을 만들어줘
```

## [팁!] 마크다운 사용법
> https://github.com/indy10/prompts/blob/main/how-to-write-by-markdown.md

## [팁!] 마크다운 에디터 : 마크닷(앱)
> https://lab.altools.com/products/markdot

<br>

# 4. 예약 작업
## 예약작업 - AI·테크 뉴스 데일리 브리핑
```
멀티 에이전트를 사용해서 매일 최신 뉴스를 조사하여
브리핑하는 자료를 만들기 위한 PRD를 작성해줘.
  시간 : 매일 오전 6시
  저장 : data/(YYYY.MM.DD)조사내용.md 작성하고 html로 변환
  디자인 : mosaic-moment.html 를 참고
```
<br>

# 5. 사용자지정 – 스킬, 커넥터, 플러그인
## 스킬 만들기

### 1. 경쟁사 뉴스 3줄 요약 스킬
```
skill-creator를 사용해서 "competitor-brief" 스킬을 만들어줘.
- 트리거: 사용자가 기사 URL이나 뉴스 텍스트를 주면서 "경쟁사 브리핑" 또는
  "competitor brief"라고 요청할 때
- 입력: URL 또는 붙여넣은 텍스트
- 로직: 핵심 발표 내용, 우리(삼성)에게 주는 시사점, 후속 액션 제안을
  각각 1줄씩 총 3줄로 요약
- 출력: 마크다운 불릿 3개, 마지막에 신뢰도(상/중/하) 태그 추가
- 제약: 원문을 그대로 인용하지 말고 반드시 재구성된 문장으로 작성
```

### 2. 회의록 액션 아이템 추출 스킬
```
skill-creator로 "action-item-extractor" 스킬을 만들어줘.
- 트리거: 회의록(마크다운/텍스트)을 주고 "액션 아이템 뽑아줘"라고 할 때
- 입력: 회의록 텍스트
- 로직: 담당자, 할 일, 마감일 3개 필드를 회의록에서 파싱
  (마감일이 없으면 "TBD"로 표시)
- 출력: 담당자별로 그룹핑된 표 형태의 마크다운
- 제약: 담당자가 명시되지 않은 항목은 "미배정"으로 별도 분류
```
### 3. 영어 비즈니스 톤 검수 스킬
```
skill-creator로 "tone-checker" 스킬을 만들어줘.
- 트리거: 영어로 작성된 이메일/메시지를 주고 "톤 체크해줘" 또는
  "review the tone"이라고 할 때
- 입력: 영문 텍스트
- 로직: 격식도(formal/casual), 직설성(direct/indirect),
  잠재적 오해 소지 표현 3가지 기준으로 평가
- 출력: 기준별 평가 + 수정 제안 문장 (원문과 나란히 비교)
- 제약: 대상 문화권(미국 기업 문화)에 맞춘 피드백만 제공
```

### 4. 데일리 브리핑 대시보드 스킬
```
skill-creator로 "daily-dashboard" 스킬을 만들어줘.
- 트리거: "오늘 브리핑 보여줘" 또는 "/daily" 호출 시
- 입력: 없음 (사용자가 그날그날 붙여넣는 3~5개 뉴스/이슈 텍스트)
- 로직: 카테고리(Apple/Google/중국OEM/AI플랫폼)로 자동 분류,
  각 카테고리 3줄 이내 요약
- 출력: 카드 레이아웃의 HTML 대시보드 (다크모드, 카테고리별 색상 구분)
- 제약: 이슈가 없는 카테고리는 카드 자체를 숨김 처리
```

## 스킬 사용하기
```
뉴스 브리핑 스킬을 사용해서 오늘의 뉴스를 요약해줘.
```
```
/algorithmic-art 는 어떤 기능을 갖고 있어? 어떻게 명령을 해야해?
```
```
 파티클 시스템 기반 인터랙티브 아트 만들어줘, 차분하고 명상적인 느낌의 알고리즘 아트
```

## 커스텀 명령어 - 자주 사용하는 명령어
```
.claude/commands/upload_articles.md를 생성해.

data디렉토리에 추가된 파일을 오늘의 Tech뉴스 게시판에
추가하고 변경내용을 today-news 저장소에 업로드해줘.
```

## 스킬 다운로드

### 1. 앤스로픽 스킬  
> https://github.com/anthropics/skills

### 2. 스킬 에코  
> https://skills.sh

### 3. 스킬 마켓플레이스
> https://skillsmp.com

<br>

## 다채롭고 쉬운 MCP 설치  

### 1. 거대한 MCP 창고  
> https://smithery.ai

### 2. 카카오톡(PlayMCP)  
> https://playmcp.kakao.com/?page=0

### 3. 다이소(daiso-mcp)  
> https://github.com/hmmhmmhm/daiso-mcp

<br>

# 6. 멀티에이전트

## 서브에이전트 만들기  

### 1. AI·테크 뉴스 조사, 분석 전문가
```
서브 에이전트를 만들어줘
구글에 특화된 조사하고 분석하는 전문가 : 구글이 개발하는 Android, 어플, AI 등 기능 조사, 인사이트 발굴, 목표설정, 목표제안, 트렌드 분석한다.
애플에 특화된 조사하고 분석하는 전문가 : 애플이 개발하는 iPhone/iPad/Mac, iOS/iPadOS/MacOS, 어플, AI 등 기능 조사, 인사이트 발굴, 목표설정, 목표제안, 트렌드 분석한다.
C브랜드(Xiaomi, OPPO, Honor)에 특화된 조사하고 분석하는 전문가 : C브랜드가 개발하는 기기들과 어플, 서비스, AI등 기능 조사, 인사이트 발굴, 목표설정, 목표제안, 트렌드 분석한다.
빅테크 AI 전문가 : ChatGPT, Claude, Gemini가 개발하는 기기들과 어플, 서비스등 기능 조사, 인사이트 발굴, 목표설정, 목표제안, 트렌드 분석한다.
```

### 2. 앱과 서비스 개발 전문가
```
서브 에이전트를 만들어줘
코드 리뷰어 : 코드를 읽고 버그는 없는지, 코딩 규칙에 따라 올바르게 작성되었는지를 점검하고 성능 최적화를 제안하는 전문 코드 품질 검토자.
최적화 전문가 : 애플리케이션의 작동을 원활하게 개선하고 속도를 빠르게 만들며 병목 지점을 찾아서 해결하는 시스템 최적화 엔지니어.
UX 디자이너 : 사용자가 쉽고 편하게 이용할 수 있도록 화면 디자인, 버튼 배치, 에러 메시지를 개선하는 사용자 경험 전문가.
제품 기획 관리자 : 전체 개발 일정을 관리하는 프로덕트 매니저로서 PRD를 작성하여 제품의 목표, 기능, 사용자 요구사항을 정의한다
백엔드 개발자 : 서버 아키텍처 설계, API 개발, 데이터 처리, 외부 서비스 통합, 보안 및 성능 최적화를 담당하는 서버 사이드 개발 전문가. 안정적이고 확장 가능한 백엔드 시스템 구축.
프런트엔드 개발자 : 사용자 인터페이스 설계 및 구현, 반응형 디자인, 웹 접근성, 성능 최적화를 담당하는 클라이언트 사이드 개발 전문가.
품질 보증 엔지니어 : 전체 시스템의 기능 테스트, 에러 처리 검증, 성능 최적화, 코드 리뷰를 수행하는 품질 관리 전문가. 버그 발견, 사용성 개선사항 제안.
AI 통합 전문가 : LLM 및 AI 서비스 통합, 프롬프트 최적화, 모델 파인튜닝, AI 파이프라인 구축을 담당하는 인공지능 전문가. 여기서는 OpenRouter API를 통해 DeepSeek 모델과 연동하여 텍스트 생성, 요약을 구현하는 LLM 활용 전문가
```
## 활용1 - AI·테크 뉴스 브리핑
```
멀티 에이전트를 사용해서 매일 최신 뉴스를 조사하여 
브리핑하는 자료를 만들기 위한 PRD를 작성해줘.
시간 : 매일 오전 6시
저장 : data/(YYYY.MM.DD)조사내용.md 작성하고 html로 변환
디자인 : mosaic-moment.html 를 참고
```

## 활용2 - AI 공감 다이어리 앱 개발  
```
AI 공감 다이어리를 만들어 줘. 
오늘 있었던 일을 한 줄로 쓰면, AI가 감정을 분석하고 공감하며 위로해 주는 일기 애플리케이션이야.
backend-architect가 OpenRouter API를 연동해서 감정 분석과 공감 메시지를 생성하는 기능을 구현해 줘.
DeepSeek V3.1 무료 모델을 사용하고, API 키는 현재 폴더의 ‘.env’ 파일에 저장된 것을 사용해.
frontend-developer가 따뜻하고 편안한 느낌의 일기장 UI를 만든 다음, qa-engineer가 실제로 여러 상황에서 문제없이 작동하는지 테스트해 줘.
문제를 발견하면 완전히 해결할 때까지 수정하고, 최종 버전을 브라우저에서 바로 열 수 있는 ‘index.html’ 파일로 만들어 줘.
```

## 서브 에이전트 위치  
c:/Users/indiana.kim/.claude/agents   
c:/Users/indiana.kim/vibe-coding/today-news/.claude/agents  

## 스킬 위치  
c:/Users/indiana.kim/.claude/skills   
c:/Users/indiana.kim/vibe-coding/today-news/.claude/skills  

## 커스텀 명령어 위치
c:/Users/indiana.kim/.claude/commands   
c:/Users/indiana.kim/vibe-coding/today-news/.claude/commands  

<br>

# 7. Cowork & Claude 코드
## Claude Code에서 자동 승인 모드 
```
claude --dangerously-skip-permissions
```
## Claude Code(Windows 로컬 실행)에서 DRM 문서 읽는 방법
```
DRM 걸린 문서(xlsx, docs, pdf 등)는 반드시 Windows의 프로그램 자동 조작 기능(COM)으로 실행해줘
```

<br>

# 8. Skill & Custom 명령어
## 앞의 내용 참고

<br>

# 9. 참고 사이트 
