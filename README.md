# .github

Omechu 조직의 GitHub 프로필 및 공용 설정을 관리하는 저장소입니다.

## Structure

```
.github/
├── profile/
│   ├── README.md              ← GitHub 조직 프로필에 표시되는 메인 README
│   └── assets/                ← 로고, 배너, 팀원 사진 등
├── ISSUE_TEMPLATE/
│   ├── bug_report.md          ← 버그 리포트 템플릿
│   ├── feature_request.md     ← 기능 제안 템플릿
│   ├── task.md                ← 일반 작업 템플릿
│   └── config.yml             ← 이슈 템플릿 설정
├── PULL_REQUEST_TEMPLATE.md   ← PR 템플릿
└── README.md                  ← 이 파일 (저장소 설명용)
```

## Brand Color

| 항목 | 값 |
|:-----|:---|
| Primary | `#FF6B35` |
| Dark Background | `#1A1A1A` |

## Banner Spec

디자이너에게 전달할 배너 규격:

| 항목 | 값 |
|:-----|:---|
| 사이즈 | **1280 x 320px** (4:1) |
| 포맷 | PNG |
| 브랜드 컬러 | `#FF6B35` |
| 배경색 | `#1A1A1A` |
| 파일 크기 | 1MB 이하 |

배너 수령 후 `profile/assets/banner.png`에 저장하고, `profile/README.md` 상단의 배너 주석을 해제하세요.
