# PTE DI 템플릿 퀴즈

PTE Academic **Describe Image** 섹션에서 자주 쓰이는 핵심 템플릿 표현을 퀴즈로 연습하는 단일 파일 웹앱입니다.

## 기능

- **5가지 유형**: 그래프 비교형 / 그래프 증감형 / Pie·Table / 순서도 / 사진
- **2가지 모드**: 타이핑 모드 (직접 입력) / 4지선다 모드
- **틀린 문제 풀**: 오답을 별도 보관 후 재도전
- **누적 통계**: 유형별 정답률을 localStorage에 영구 저장
- **다크모드 자동 지원**
- **모바일 반응형**

## 로컬 실행

별도 서버 불필요. `index.html` 파일을 브라우저로 열면 바로 실행됩니다.

```
index.html  →  (더블 클릭 또는 브라우저에 드래그)
```

## GitHub Pages 배포 방법

1. GitHub에서 새 repository 생성 (예: `di-quiz`)
2. 아래 명령어 실행:

```bash
git remote add origin https://github.com/[유저명]/di-quiz.git
git branch -M main
git push -u origin main
```

3. GitHub 저장소 → **Settings** → **Pages**
4. Source: `Deploy from a branch` → Branch: `main` / `/ (root)` → **Save**
5. 잠시 후 `https://[유저명].github.io/di-quiz/` 에서 접속 가능

## 파일 구조

```
di-quiz/
├── index.html   ← 앱 전체 (HTML + CSS + JS 단일 파일)
└── README.md
```
