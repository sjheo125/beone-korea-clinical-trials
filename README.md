# BeOne 국내 임상시험 현황 분석 (2026-10-13 기준)

BeOne Medicines의 Q2 2026 실적 발표 자료(Clinical Trial Appendix)와 글로벌 파이프라인을 식약처 **의약품안전나라(nedrug)** 공개 데이터와 비교해, 한국에서 진행 중인 임상시험과 국내 허가 현황을 정리한 개인 분석 자료입니다.

> ⚠️ 공개자료를 바탕으로 개인이 정리한 분석 자료이며, BeOne Medicines의 공식 자료가 아닙니다. 투자·의료 판단의 근거로 사용하지 마세요.

## 파일

| 파일 | 내용 |
|---|---|
| [`BeOne_Korea_진행중임상_OnePage_20261013.pdf`](BeOne_Korea_진행중임상_OnePage_20261013.pdf) | 국내 진행 중 임상 15건을 한 페이지(16:9)로 정리. 글로벌 파이프라인 형식(Phase별 열, 치료영역 색상)을 따름 |
| [`BeOne_Korea_진행중임상_OnePage_20261013.html`](BeOne_Korea_진행중임상_OnePage_20261013.html) | 위 PDF의 원본 HTML (수정용) |
| [`BeOne_임상비교_Appendix_vs_nedrug_20261013.md`](BeOne_임상비교_Appendix_vs_nedrug_20261013.md) | Appendix ↔ nedrug 비교 문서 (시험별 1:1 대조, 제품 비교, 실시기관 집계) |
| [`BeOne_임상비교_Appendix_vs_nedrug_20261013.xlsx`](BeOne_임상비교_Appendix_vs_nedrug_20261013.xlsx) | 같은 비교를 엑셀로 정리. 시트: 요약 · 시험별비교(21건) · Appendix전체대조(86건) · 제품비교(17종) · 실시기관(기관×시험 매트릭스). 집계 값은 수식으로 계산됨 |
| [`data/`](data/) | 의약품안전나라 검색 결과 원자료 (임상시험정보 21건, 의약품등제품정보 3건) |

## 주요 결과

- **국내 진행 중 임상 15건** (모집중 12 · 승인완료 2 · 모집완료 1), 종료 6건
  - 3상 8건: 혈액암 6건(sonrotoclax 4, tacabrutideg 2), 고형암 2건(BGB-43395, tislelizumab SC)
  - 2상 1건, 1상 6건
- nedrug 21건 중 **16건이 Appendix 프로토콜과 1:1로 매칭**됨
- 확인이 필요한 차이 2건
  - **BG-C477 2상**(2026-10-02 국내 승인): 8월 공시에는 1상만 있어 공시 이후 새로 시작한 2상으로 보임
  - **BG-C137 1상**: 국내는 '종료'인데 글로벌은 진행 중 → 한국 사이트만 종료됐을 가능성
- 국내 판권 보유 제품 4개 중 3개(브루킨사, 테빔브라, 지헤라)가 허가됨. **BEQALZI(sonrotoclax)는 미허가**이지만 국내 3상 4건이 진행 중
- 국내 실시기관 30곳. 서울대병원·세브란스병원이 각각 14건에 참여

## 데이터 출처

| 자료 | 기준일 | 비고 |
|---|---|---|
| BeOne Q2 2026 Earnings – Clinical Trial Appendix | As of 2026-07-24 (발표 2026-08-05) | BeOne IR 웹사이트 공개 자료. 저작권 때문에 원본은 저장소에 포함하지 않음 |
| BeOne Global clinical development pipeline | 2026-08-03 | 위와 같음 |
| 식약처 의약품안전나라 임상시험정보 검색 | 2026-10-13 검색 | 의뢰자: 비원메디슨코리아 유한회사 → [`data/`](data/) |
| 식약처 의약품안전나라 의약품등 제품정보 | 2026-10-13 검색 | 업체: 비원메디슨코리아(유) → [`data/`](data/) |
| ClinicalTrials.gov [NCT06029127](https://clinicaltrials.gov/study/NCT06029127) | – | nedrug No.21(BGB-A445 2상) 프로토콜 식별용 |

## 한계

- nedrug 검색 결과에는 **2023-11-23 이후 국내 승인 건만** 들어 있습니다. 그 이전 시험(ALPINE, RATIONALE 등)은 빠져 있습니다.
- 의뢰자 '비원메디슨코리아' 기준 검색이라, **파트너사가 주도하는 시험**(Amgen tarlatamab, Jazz zanidatamab 등)은 포함되지 않습니다. 목록에 없다고 한국 미참여로 단정할 수 없습니다.
- MOA·치료영역·대상 요약·판정은 원문을 대조해 작성자가 정리한 값입니다.
