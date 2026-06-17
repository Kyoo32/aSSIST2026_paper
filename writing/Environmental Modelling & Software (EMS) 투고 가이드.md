# Environmental Modelling & Software (EMS) 투고 가이드

> ISSN 1364-8152 · Elsevier · International Environmental Modelling & Software Society 공식 저널
> 편집장(Editor-in-Chief): Daniel P. Ames (Brigham Young University)
> ISO 4 약어: *Environ. Model. Softw.*
> 발행: 월간(Monthly) · 오픈액세스: 하이브리드
> 공식 Guide for Authors: https://www.sciencedirect.com/journal/environmental-modelling-and-software/publish/guide-for-authors
> 투고 시스템(Editorial Manager): https://www.editorialmanager.com/envsoft/default.aspx

---

## 1. 저널 스코프 (Aims & Scope)

환경 시스템(대기·물·토지)을 표현·이해·예측·관리하는 능력을 향상시키는 모델링과 소프트웨어의 발전을 다룬다. 다음 세 가지를 주로 게재한다.

1. 다학제 이슈를 위한 일반(generic) 프레임워크 및 기법
2. 환경 모델·소프트웨어·정보/의사결정지원 시스템의 개발·평가·응용
3. 환경 시스템의 통합 모델링·평가·관리 관련 이슈와 방법 (모델·데이터·절차의 품질보증 및 평가 포함)

> **카이님 연구 적합성 메모**: PCMCI+/LPCMCI 기반 인과 발견 파이프라인은 항목 2의 "방법 개발 + 재현 가능한 소프트웨어/파이프라인" 프레이밍이 가장 강하다. 서울 대기질 적용은 환경 시스템 응용 + 도메인 지식 대비 검증(RQ1)으로 묶고, differencing 방법론 연구는 일반 기법(항목 1)으로 포지셔닝 가능.

---

## 2. 논문 유형 (Article Types)

- **Full Length Article** (정규 연구논문)
- **Review Article**
- **Short Communication**
- **Original Software Publication** (소프트웨어 자체 발표 — 코드/재현성 강조 연구에 유리)
- **Position Paper / Introductory Overview** (초청제, by invitation)
- **EnviroFutures / Opinion Papers**: 초청제. 권장 분량 4,000단어 이내, 그림 2개 이내.
- 기타: Case Report, Data, Micro-article, Practical Guideline, Protocol, Replication Study, Short Survey, Video

> 특별호(VSI) 투고 시 Editorial Manager에서 해당 article type 코드를 선택해야 함.

---

## 3. 초록 · 하이라이트 · 키워드

### Abstract
- **150단어 이내** (엄격 제한)
- 연구 목적 / 주요 결과 / 핵심 결론을 간결하게
- 단독으로 읽혀도 이해되도록 작성 (stand-alone)
- 비표준 약어 지양, 불가피하면 첫 등장 시 정의

### Highlights (필수 — 별도 파일)
- 파일명에 `highlights` 포함, 편집 가능한 형식으로 제출
- **3~5개 bullet**, 각 **최대 85자(공백 포함)**
- 새로운 결과와 새로 사용한 방법을 포착

### Keywords
- **1~7개**, 영어
- "and", "of"가 들어가는 다단어 키워드 지양
- 약어는 해당 분야에서 확립된 경우에만 사용

### Graphical Abstract (선택, 권장)
- 531 × 1328 px (h × w) 이상, 5 × 13 cm 크기에서 읽혀야 함
- 선호 파일형식: TIFF, EPS, PDF, MS Office
- 생성형 AI 사용 시 Elsevier GenAI 정책 준수

---

## 4. 원고 구조 (Article Structure)

일반적인 Elsevier 표준 구조를 따른다.

1. Introduction
2. Material and Methods
3. Theory / Calculation
4. Results
5. Discussion
6. Conclusions
7. Appendices (필요 시)

**Essential title page information**: 제목, 저자·소속, 교신저자 정보, 현주소 등.

> **카이님 연구용 구조 제안**
> - Methods에 인과 발견 알고리즘(PCMCI+/LPCMCI), CI test, effect-size cutoff(|val|>0.10), 전처리(differencing) 조건을 명확히 분리 기술
> - 신뢰도 등급 매트릭스(reliability grading)는 Results의 핵심 표로
> - Negative control / 도메인 지식 대비 검증은 별도 소절로 (저널이 "모델·데이터·절차의 품질보증 및 평가"를 명시적으로 중시)
> - 재현성: 코드·데이터 가용성 진술 필수 (tigramite 버전 명시)

---

## 5. "Your Paper Your Way"

- 1차 심사 단계에서는 **단일 Word 또는 PDF 파일**로 제출 가능 (엄격한 포맷팅 불필요)
- 채택(accept) 후 정식 포맷으로 변환
- 단, 참고문헌은 검토자가 따라갈 수 있도록 충분한 정보 포함 권장

---

## 6. 심사 프로세스 (Peer Review)

- 투고 원고는 먼저 **Editor-in-Chief 및 lead editor**가 검토
- 다음과 같은 문제는 **외부 심사 없이 reject(desk reject)** 될 수 있음:
  - 스코프 부적합
  - 기타 형식·품질 결격 사유
- 특별호/article collection도 정규 심사와 동일 절차 (guest editor가 심사 의뢰 및 결정 권고, 최종 감독은 저널 editor)
- 편집위원 본인 관련 투고는 독립적으로 심사
- 결정에 대한 **공식 appeal** 가능 (Elsevier Appeal Policy, 건당 1회, 결정은 최종)

> **심사 기간 참고**: 한 투고자 보고 사례에서 1차 리뷰 라운드에 약 47.7주가 소요된 바 있음(개별 사례, 평균치 아님). 일정에 여유를 두는 것을 권장.

---

## 7. 인용 스타일 (Citation Style)

- Elsevier(Environmental Modelling and Software) 스타일 = **저자-연도(author-year)** 방식
- 본문 인용 후 알파벳순 reference list
- 저널 article identifier가 있으면 page range 대신 사용 가능
- 보고서는 기관(부서/기관명)을 저자로 표기
- 일부 웹 출처는 bibliography 대신 본문 내 직접 표기
- 참고문헌 도구(Zotero/EndNote/Paperpile 등)용 스타일 파일 사용 권장
  - 스타일 파일 다운로드: https://paperpile.com/s/environmental-modelling-and-software-citation-style/

---

## 8. 투고 전 체크리스트

- [ ] 원고가 스코프(특히 모델/소프트웨어 발전 기여)에 명확히 부합하는가
- [ ] Abstract 150단어 이내
- [ ] Highlights 3~5개, 각 85자 이내, 별도 파일 (`highlights` 파일명)
- [ ] Keywords 1~7개, 영어, 다단어 지양
- [ ] (선택) Graphical abstract 규격 충족
- [ ] 표준 구조(Intro–Methods–Results–Discussion–Conclusions)
- [ ] 재현성: 코드/데이터 가용성 진술, 사용 라이브러리·버전 명시
- [ ] 이해상충(Declaration of competing interests) 진술
- [ ] 생성형 AI 사용 시 Elsevier GenAI 정책에 따른 명시
- [ ] Editorial Manager 제출, (특별호일 경우) 올바른 article type 선택

---

## 9. 오픈액세스 · APC

- 하이브리드 오픈액세스 저널 (구독형 또는 OA 선택)
- 일부 기관(예: 네덜란드 VSNU 협약 대학들)은 교신저자 APC 100% 할인 적용
- 정확한 APC 및 할인 가능 여부는 소속 기관 라이브러리/Elsevier에 확인

---
*본 문서는 공개된 EMS Guide for Authors 및 관련 출처를 기반으로 정리한 요약입니다. 투고 직전 반드시 공식 Guide for Authors 최신본을 확인하세요.*
