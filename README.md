# github-collabo

협업 및 깃허브 워크플로우 실습 프로젝트입니다.

---

## 📌 프로젝트 개요
- **목적**: GitHub 브랜치 전략(Branching Strategy) 및 Pull Request(PR) 협업 실습
- **구성 페이지**:
  - `about.html`: 팀 소개, 핵심 가치, 미션 설명 페이지
  - `contact.html`: 문의 폼 및 회사 정보 안내 페이지

---

## 📂 파일 구조
```text
github-collabo/
├── .gitignore
├── README.md
├── about.html      # 팀 소개 및 미션 페이지
└── contact.html    # 문의 폼 및 연락처 페이지
```

---

## 🛠 지금까지 작업 내용

### 1. 초기 프로젝트 설정
- 저장소 초기화 및 `.gitignore`, 기본 `README.md` 구성

### 2. 브랜치별 작업 및 협업
- **`AAA` 브랜치 작업**:
  - `contact.html` 생성 및 문의 폼 UI 구현 (이름, 이메일, 연락처, 문의 내용 입력 폼 및 회사 정보)
  - `main` 브랜치로 PR (#2) 생성 및 병합 완료
- **`BBB` 브랜치 작업**:
  - `about.html` 생성 및 팀 소개/미션/핵심 가치 UI 구현
  - 팀 소개 섹션의 핵심 가치 문구 수정 (`지속 가능한 성장` ➔ `지속 가능한 성장을 지향`)
  - `main` 브랜치로 PR (#1) 생성 및 병합 완료

### 3. 최신 변경사항 동기화
- `AAA` 브랜치로 전환 후 최신 `main` 브랜치 변경사항 병합 동기화 완료
