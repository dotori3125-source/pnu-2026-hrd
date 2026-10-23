# 2026학년도 부산대학교 교직원 직무연수 종합 안내 포털

부산대학교 교직원 직무역량 강화 및 법정의무교육 이수를 지원하는 2026년도 직무연수 종합 안내 웹사이트입니다.

- **웹사이트 바로가기**: [https://dotori3125-source.github.io/pnu-2026-hrd/](https://dotori3125-source.github.io/pnu-2026-hrd/)
- **구글 스프레드시트 실시간 연동**: 구글 시트 원본 데이터가 수정되면 새로고침 시 웹사이트에 즉시 반영됩니다.

## 주요 기능
- **메인 페이지 (`index.html`)**:
  - 32개 교육과정 전수 실시간 파싱 및 통계 대시보드
  - 10개 교육 분야별 탭 및 키워드 실시간 검색
  - 대상(전 직원/실무자/관리자/신규자), 이수구분(필수/권장/선택), 방식(온라인/집합/혼합) 다중 필터
- **상세 페이지 (`detail.html`)**:
  - `?code=PNU-2026-XXX` 파라미터 기반 개별 연수 상세 안내
  - 학습목표 체크리스트, 커리큘럼 타임라인, 동일 분야 연관 연수 추천
  - 우측 스티키 카드: 정원, 일정, 담당부서 전화 바로걸기, 수강신청 바로가기 CTA

## 기술 스택
- Vanilla HTML5 / Modern CSS / ES6+ JavaScript
- Google Sheets GViz CSV API (`&headers=1`) + PapaParse
- FontAwesome 6 + Pretendard Web Font
- GitHub Pages
