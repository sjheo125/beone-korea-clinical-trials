# BeOne 임상 데이터 교차 비교 — Q2 2026 Clinical Trials Appendix vs. 의약품안전나라(nedrug)

작성일: 2026-10-13

## 0. 비교 대상

| 자료 | 기준일 | 범위 |
|---|---|---|
| **A.** `Q2_2026_earnings_-_Clinical_Trials_Appendix_-_FINAL.pdf` | As of 2026-07-24 (발표 2026-08-05) | 글로벌 프로토콜 단위 (NCT, 단계, 대상자 수, 상태) + 상업화 제품 권리 |
| **B.** `BeOne_nedrug_20261013_임상시험정보검색.xlsx` | 2026-10-13 검색 | 의뢰자 = 비원메디슨코리아 유한회사, **21건** (국내 승인일 2023-11-23 ~ 2026-10-02), 전부 '국외개발' |
| **C.** `BeOne_nedrug_20261013_의약품등제품정보목록.xlsx` | 2026-10-13 검색 | 업체 = 비원메디슨코리아(유), **3개 품목** |

> 판정 기준: nedrug `모집중`·`승인완료` ↔ Appendix `Enrolling`·`Dose Escalation/Expansion`, nedrug `모집완료` ↔ `Maintenance`, nedrug `종료` ↔ `Closeout` 또는 파이프라인 제외.

---

## 1. 핵심 요약

1. **매칭률**: nedrug 21건 중 **16건이 Appendix 프로토콜과 1:1로 매칭**됨. 미수록 5건은 신규 과제 1건(BG-C477 2상)과 종료·제외 과제 4건(BGB-53038, BGB-A3055, BG-60366, BGB-A445/LC-203)임.
2. **국내 진행 중 15건** (모집중 12, 승인완료 2, 모집완료 1) / 종료 6건.
   - 3상 8건: 혈액암 6건 (sonrotoclax 4, tacabrutideg 2), 고형암 2건 (BGB-43395, tislelizumab SC)
   - 2상 1건, 1상 6건
3. **확인이 필요한 차이 2건**
   - ⚠ **BG-C477 (CEA ADC) 2상, 2026-10-02 국내 승인** → Appendix와 8월 파이프라인 모두 BG-C477은 *Phase 1 (101)* 로만 표기됨. 공시 이후 **새로 시작된 2상(CEA 고발현 비편평 NSCLC, 단일군)** 으로 보이며, Q3 실적 발표에서 "New to Phase II"로 반영될 가능성이 높음.
   - ⚠ **BG-C137 (FGFR2b ADC) 1상** → nedrug에는 '**종료**'로 나오지만 Appendix는 *Dose Escalation*(진행 중)이고 8월 파이프라인에도 남아 있음. **국내 사이트만 종료(국가 철수)** 했을 가능성이 있으므로 확인이 필요함.
4. **Sonrotoclax 글로벌 3상 CELESTIAL 4건(301·302·303·304)에 한국이 모두 참여** → 반면 국내 품목허가는 없음(BEQALZI 미허가). 국내 허가 신청은 Medical Affairs·RA의 다음 과제가 될 것으로 보임.
5. **BGB-43395-302 (KANDELA-302)**: Q2에 "New to pivotal"로 올라온 과제임. **국내 승인(2026-04-09)이 글로벌 공시(2026-08-05)보다 앞서** 한국이 초기 참여국에 포함된 것으로 보임. 국내 실시기관 **25곳**으로 BeOne 국내 임상 중 최대 규모 → 사이트 관리·MSL 지원 부담이 가장 큼.

---

## 2. 시험별 1:1 비교 (B ↔ A)

| # | nedrug 상태 | 국내 승인일 | 제품 | 단계 | 대상 / 디자인 (nedrug 요약) | Appendix 프로토콜 | NCT | Appendix 상태 | 8월 파이프라인 | 판정 |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 승인완료 | 2026-10-02 | BG-C477 (CEA ADC) | 2상 | 기치료 CEA 고발현 비편평 NSCLC (EGFR 변이 없음), 단일군 공개 | **미수록** | – | – | Ph1 101만 표기 | ⚠ **신규 2상, 공시 미반영** |
| 2 | 승인완료 | 2026-08-05 | BG-75098 (CDK2 CDAC) ± BGB-43395 | 1상 | 진행성 고형암, 단독·병용 1a/1b | BG-75098-101 | NCT07226349 | Dose Escalation | Ph1 101 | ✅ 일치 (국내는 모집 전) |
| 3 | 모집중 | 2026-06-10 | BG-C477 (CEA ADC) | 1상 | 진행성 고형암 FIH 1a/b | BG-C477-101 | NCT06596473 | Dose Escalation | Ph1 101 | ✅ 일치 (한국은 글로벌보다 늦게 참여) |
| 4 | 모집중 | 2026-04-09 | BGB-43395 (CDK4i) | 3상 | 1L HR+/HER2- 유방암, +letrozole vs CDK4/6i+letrozole | BGB-43395-302 (KANDELA-302) | NCT07492641 | Enrolling | Ph3 302 | ✅ 일치 · 국내 25개 기관 |
| 5 | 모집중 | 2026-01-07 | Sonrotoclax (BCL2i) | 3상 | TN CLL, sonro+zanu vs ven+acala | BGB-11417-304 (CELESTIAL-TNCLL2) | NCT07277231 | Enrolling | Ph3 304 | ✅ 일치 |
| 6 | 모집중 | 2025-10-24 | BG-T187 (EGFR×MET×MET tsAb) | 1상 | 진행성 고형암, 단독·병용 | BG-T187-101 | NCT06598800 | Dose Escalation | Ph1 101 | ✅ 일치 |
| 7 | 모집중 | 2025-09-08 | Tislelizumab (PD-1) | 3상 | 1L 위/위식도접합부 선암, **SC vs IV** + 화학요법 | BGB-A317-316 | NCT07043400 | Enrolling | Ph3 316 SubQ | ✅ 일치 (Appendix에는 "SubQ Formulation"으로만 적혀 있고 적응증은 nedrug에서 확인됨) |
| 8 | 모집중 | 2025-07-30 | Tacabrutideg (BTK CDAC) | 3상 | R/R CLL/SLL vs **pirtobrutinib** | BGB-16673-304 (CaDAnCe-304) | NCT06973187 | Enrolling | Ph3 304 | ✅ 일치 |
| 9 | 모집중 | 2025-07-03 | Tacabrutideg (BTK CDAC) | 3상 | BTKi·BCL2i 모두 경치료한 CLL/SLL vs 연구자 선택(IdelaR/BR/VenR) | BGB-16673-302 (CaDAnCe-302) | NCT06846671 | Enrolling | Ph3 302 | ✅ 일치 |
| 10 | 종료 | 2025-06-20 | BGB-53038 (pan-KRAS) ± tisle | 1상 | KRAS 변이/증폭 고형암 | **미수록** | – | – | 미표기 | ✅ 정합 (파이프라인에서 제외된 과제) |
| 11 | 모집중 | 2025-05-20 | Sonrotoclax (BCL2i) | 3상 | R/R CLL/SLL, sonro+anti-CD20 vs VenR | BGB-11417-303 (CELESTIAL-RRCLL) | NCT06943872 | Enrolling | Ph3 303 | ✅ 일치 |
| 12 | 종료 | 2025-04-14 | BGB-A3055 ± tisle | 1상 | 진행성 고형암 | **미수록** | – | – | 미표기 | ✅ 정합 (제외 과제) |
| 13 | 종료 | 2025-03-27 | BG-60366 (EGFR CDAC) | 1상 | EGFR 변이 NSCLC | **미수록** | – | – | 미표기 | ✅ 정합 (제외 과제) |
| 14 | 종료 | 2025-03-04 | BG-68501 (CDK2i) | 1상 | 진행성 고형암 | BG-68501-101 | NCT06257264 | Closeout | 미표기 | ✅ 정합. CDK2 전략은 BG-75098(CDK2 CDAC, #2)로 넘어감 |
| 15 | 모집중 | 2025-01-24 | Sonrotoclax (BCL2i) | 3상 | R/R MCL, sonro+zanu vs 위약+zanu (이중눈가림) | BGB-11417-302 (CELESTIAL-RRMCL) | NCT06742996 | Enrolling | Ph3 302 | ✅ 일치 |
| 16 | 모집중 | 2025-01-07 | BGB-58067 (MTA-coop PRMT5i) ± tisle | 1상 | 진행성 고형암 | BGB-58067-101 | NCT06589596 | Dose Escalation | Ph1 101 | ✅ 일치 |
| 17 | 종료 | 2025-01-03 | BG-C137 (FGFR2b ADC) ± tisle | 1상 | 진행성 고형암 | BG-C137-101 | NCT06625593 | **Dose Escalation** | Ph1 101 (진행) | ⚠ **불일치: 글로벌은 진행 중, 국내는 종료** |
| 18 | 모집중 | 2024-09-20 | BGB-43395 (CDK4i) | 1상 | HR+/HER2- 유방암 및 고형암 | BGB-43395-101 | NCT06120283 | Dose Expansion | Ph1 101 | ✅ 일치 |
| 19 | 모집중 | 2024-09-19 | BGB-B2033 (GPC3×4-1BB) ± tisle ± bev | 1상 | 진행성 고형암 | BGB-B2033-101 | NCT06427941 | Dose Escalation | Ph1 101 / Ph2 101 3L+ HCC | ✅ 일치 (Appendix 표기는 Ph1, 자산 목록은 Ph1/2) |
| 20 | 모집완료 | 2023-12-06 | Sonrotoclax (BCL2i) | 3상 | TN CLL, sonro+zanu vs VenO | BGB-11417-301 (CELESTIAL-TNCLL) | NCT06073821 | Maintenance | Ph3 301 | ✅ 일치 |
| 21 | 종료 | 2023-11-23 | BGB-A445 (OX40) + BGB-15025 (HPK1i) | 2상 | anti-PD-(L)1 경치료 NSCLC, 다중군 | **미수록** (= BGB-LC-203, NCT06029127, CT.gov상 Completed) | – | – | 미표기 | ✅ 정합 |

---

## 3. 반대 방향: Appendix에는 있으나 nedrug(의뢰자 비원메디슨코리아)에서는 검색되지 않는 과제

| 구분 | 과제 (Appendix 상태) | 해석 |
|---|---|---|
| Zanubrutinib | 306 MANGROVE·308 MAHOGANY·LTE1 (Maintenance), 309 pMN (Ph2/3, Maintenance) | 국내 승인 시점이 검색 범위(2023-11 이후)보다 이전이거나, 한국이 참여하지 않았을 수 있음 |
| Sonrotoclax | 103 AML/MDS, 105 MM t(11;14), 108 ramp-up (Enrolling) | 한국 미참여로 추정됨 |
| Tacabrutideg | 101·102·104 (Ph1/2 Enrolling), 303 (중국 전용), 107 CSU (I&I) | 101 CaDAnCe-101 등은 이전 승인분일 수 있음 |
| 고형암 Ph1 | BG-C9074(B7-H4 ADC), BGB-21447, BG-C0902, BG-C0979, BGB-B455, BG-75202, BON-110, BGB-26808 | BON-110(Huahui)·BG-75202-102는 Q2 신규 진입 과제로, 국내 신청 여부를 지켜볼 대상 |
| I&I | BG-A3004-101 (KLRG1, Enrolling) | 국내 미참여 |
| 파트너 주도 | Tarlatamab DeLLphi(Amgen), Zanidatamab HERIZON(Jazz/Zymeworks) | **의뢰자가 Amgen·Jazz 등이라 이번 검색 조건에서는 빠짐.** 한국 미참여로 단정하면 안 됨 |

> **검색 범위 한계**: B 파일에는 2023-11-23 이후 국내 승인 건만 있음. BRUKINSA·TEVIMBRA 허가의 근거가 된 이전 시험(ALPINE, RATIONALE 등)은 들어 있지 않으므로, 전체 이력이 필요하면 nedrug에서 기간 조건을 넓히거나 구 사명(베이진코리아)으로 다시 검색해야 함.

---

## 4. 제품 비교 (C ↔ A 'Commercial' 목록)

| Appendix 상업화 제품 | BeOne 권리 | 국내 허가 (nedrug) | 비고 |
|---|---|---|---|
| **BRUKINSA®** (zanubrutinib, BTKi) | Global | ✅ **브루킨사캡슐80mg**, 2022-02-24, 전문·수입(미국), ATC L01EL03 | 정제(BGB-3111-114: 주요국 승인, 일본 접수)는 국내 미허가 → 향후 LCM(제형 변경) 과제 |
| **TEVIMBRA®** (tislelizumab, PD-1) | Global | ✅ **테빔브라주**, 2023-11-20, 생물의약품·수입(중국·아일랜드), ATC L01FF09 | **SC 제형 3상(316)에 한국 참여 중** → 향후 SC 제형 허가로 이어질 수 있음 |
| **BEQALZI™** (sonrotoclax, BCL2i) | Global | ❌ **미허가** | 미국(R/R MCL)·중국(R/R MCL·CLL)에서 승인, EU(R/R MCL) 접수됨. **국내 3상 4건 진행 중** → 국내 허가 신청 시기 확인 필요 |
| **ZIIHERA®** (zanidatamab, HER2 bsAb) | APAC (일본·인도 제외) | ✅ **지헤라주300mg**, 2026-03-19, **희귀의약품**, 수입(중국), ATC L01FD07 | 근거 시험은 HERIZON-BTC-01(2L+ BTC)로 추정됨. 1L HER2+ GEA(ZW25-301)는 미국·중국 접수 → 국내 적응증 확대 후보 |
| IMDELLTRA, XGEVA, BLINCYTO, KYPROLIS (Amgen) / SYLVANT, QARZIBA (Recordati) / Novartis 5종 / POBEVCY / BAITUOWEI | **China only** | 해당 없음 | 한국 판권은 BeOne 소관이 아님 |

**정리**: BeOne이 국내에서 허가를 신청할 수 있는 제품은 4개(Global 3 + APAC 1)이고, 이 중 **3개가 허가됨**. 남은 1개는 **BEQALZI**이며, 국내 3상 참여 규모를 보면 다음 허가 후보 1순위임.

---

## 5. 국내 실시기관 집계 (진행 중 15건 기준, 중복 기재 제거 후)

| 기관 | 참여 시험 수 | | 기관 | 참여 시험 수 |
|---|---|---|---|---|
| 서울대병원 | 14 | | 서울성모병원 | 9 |
| 세브란스병원 | 14 | | 국립암센터 | 6 |
| 분당서울대병원 | 13 | | 부산대병원 | 4 |
| 삼성서울병원 | 13 | | 화순전남대·성빈센트 | 각 3 |
| 서울아산병원 | 12 | | 기타 20개 기관 | 1~2 |

- 고유 실시기관은 **30곳**이고, 그중 **11곳은 BGB-43395-302에만 참여**하는 기관(지방 거점 병원 포함)임.
- nedrug 원자료에는 같은 기관이 두 번 들어간 행이 있음(BG-T187·BGB-58067·BGB-B2033의 삼성서울병원, BG-75098의 세브란스병원). 집계할 때 중복 제거가 필요함.

---

*Sources: A·B·C 파일 원문. #21 프로토콜 식별: [ClinicalTrials.gov NCT06029127](https://clinicaltrials.gov/study/NCT06029127)*
