# J's AI Agent Dev Class

AI Agent 개발 절차와 관련 개념을 학습하기 위한 정적 웹앱입니다. HTML, CSS, Vanilla JavaScript만으로 구성되어 있으며 별도 빌드 과정 없이 브라우저에서 실행할 수 있습니다.

## 주요 메뉴

- **Dev Process**: AI Agent를 구현하기 위한 7단계 개발 절차
- **Agentic Workflow**: Agentic Workflow, Vibe Coding, AI Agent와 Skill의 차이
- **Reasoning**: AI 추론과 인지적 고려사항
- **Harness**: Harness Engineering과 Guardrail 설계
- **Environment**: Agent 실행 환경과 배포 구조
- **Examples**
  - HR AI Agent Idea
  - B2B Sales AI Agent Idea
  - Marketing AI Agent Idea

## 실행 방법

### 1. 파일 직접 열기

`index.html` 파일을 브라우저에서 직접 열면 됩니다.

### 2. 로컬 서버로 실행

권장 방식입니다.

```bash
cd app1
python -m http.server 8000
```

브라우저에서 아래 주소로 접속합니다.

```text
http://localhost:8000
```

## 파일 구조

```text
app1/
├── index.html   # 앱 진입점
├── style.css    # 화면 스타일
├── app.js       # 라우팅, 렌더링, 모달, 복사 기능
├── data.js      # 화면 콘텐츠 데이터
├── README.md    # 앱 설명 문서
└── .nojekyll    # GitHub Pages용 설정 파일
```

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript
- Marked.js: Markdown 렌더링
- DOMPurify: 렌더링 결과 sanitizing
- Lucide Icons: 아이콘
- Pretendard: 웹폰트

## 개발/수정 시 확인

JavaScript 문법 확인:

```bash
node --check app.js
node --check data.js
```

## 배포

정적 파일만으로 동작하므로 GitHub Pages, Netlify, Vercel, 사내 정적 웹서버 등에 그대로 배포할 수 있습니다.

GitHub Pages 배포 시 `app1` 폴더 내부 파일들을 배포 루트로 사용하세요.
