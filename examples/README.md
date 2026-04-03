# 예시 파일

## sample-audit/

검수 파이프라인(`/audit`)의 완성 결과물 예시입니다.

실제 분석 시 생성되는 폴더 구조와 동일합니다:

```
sample-audit/
├── _audit/
│   └── report.md          ← 종합 보고서 예시
└── _agency/
    └── client-brief.md    ← 제작팀 인계 문서 예시
```

### 참고
- 이 예시는 가상의 인테리어 사이트를 대상으로 한 샘플입니다.
- 실제 분석 시에는 `_audit/` 아래에 `scraped-data.json`, `screenshots/`, `derived/` 등 추가 파일이 생성됩니다.
- 자세한 사용법은 [SETUP-GUIDE.md](../SETUP-GUIDE.md)를 참고하세요.
