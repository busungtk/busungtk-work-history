# busungtk-work-history - 작업 히스토리 대시보드

GitHub 활동 기반 생산성 대시보드

## 기술 스택
- **Frontend**: Static HTML + Tailwind CSS CDN + Chart.js CDN + vanilla JavaScript
- 빌드 도구 없음

## 프로젝트 구조
```
index.html     # 대시보드 (임베디드 스타일/스크립트)
data.json      # GitHub 활동 데이터 (GitHub Actions 생성)
scripts/       # 데이터 생성 스크립트
```

## 주요 기능
- GitHub 생산성 대시보드 (커밋/PR/이슈)
- 주간 목표 추적 및 달성률
- 작업 유형 분석 파이차트
- 시간대별 히트맵
- 커밋 타임라인 (레포별 필터링)

## 배포
- **GitHub Pages**: https://busungtk.github.io/busungtk-work-history/

