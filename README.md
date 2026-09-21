# github-collabo

회사 소개를 위한 정적 HTML 웹페이지 프로젝트입니다. 현재 `about.html` 페이지를 중심으로 회사의 방향과 핵심 가치를 소개하고 있습니다.

## 주요 페이지

| 파일 | 설명 |
| --- | --- |
| `about.html` | 회사 소개, 핵심 가치, 팀 소개, 미션 및 연락처 정보를 제공하는 페이지 |

## 프로젝트 구조

```text
.
├── about.html
├── README.md
└── .gitignore
```

## 실행 방법

`about.html`을 브라우저에서 직접 열어 확인할 수 있습니다.

또는 프로젝트 폴더에서 로컬 서버를 실행합니다.

```bash
python -m http.server 8000
```

이후 브라우저에서 다음 주소로 접속합니다.

```text
http://localhost:8000/about.html
```

## 기술 스택

- HTML5
- 반응형 viewport 설정
- HTML table 기반 레이아웃

## Git 협업 방법

```bash
git checkout -b feature/작업내용
git add .
git commit -m "작업 내용 작성"
git push origin feature/작업내용
```

작업 후 Pull Request를 생성할 때 변경 내용과 확인 방법을 함께 작성해주세요.

## 향후 개선 사항

- CSS 파일을 분리해 디자인과 반응형 레이아웃 개선
- 페이지 간 내비게이션 추가
- 한글 문구 및 인코딩 검수
- 접근성 및 브라우저 호환성 점검
- 문의 페이지와 실제 문의 전송 기능 추가

## 문의

프로젝트 관련 문의: `hello@example.com`
