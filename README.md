# PTE DI 템플릿 퀴즈

PTE Academic **Describe Image** 필수 표현을 랜덤 빈칸으로 반복 학습하는 단일 파일 웹앱.

## 기능

- **5가지 템플릿 유형**: 그래프 비교형 / 증감형 / Pie·Table / 순서도 / 사진
- **2가지 모드**: 타이핑 입력 / 드롭다운 4지선다
- **4단계 난이도**: 입문(3개) · 중급(5개) · 고급(8개) · 전체 빈칸
- **랜덤 빈칸**: 새 문제마다 다른 조합으로 출제 (고정구 + 변수 자리 모두 빈칸 후보)
- **오답노트**: 틀린 표현 목록 → 해당 템플릿으로 바로 재도전
- **통계**: 유형별 누적 정답률 바 차트 (localStorage 영구 저장)
- **다크모드 자동 지원** / **모바일 반응형**

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
