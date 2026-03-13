# KOICA Kyrgyz ICT Education Center Local Tender

## Project summary
- **기관:** KOICA Office in the Kyrgyz Republic
- **사업명:** The Design and Author Supervision Services for the Construction of ICT Education Center for “The Project for Capacity Building of National Information for Digital Transformation in the Kyrgyz Republic”
- **현재 단계:** `approved`
- **공고번호:** `L2026-00007-1`
- **Notice ID:** `L2026-00007`
- **국가/지역:** 키르기스스탄 / Bishkek
- **분야:** 디지털 전환 / 국가 정보화 역량 강화 / ICT 교육센터 / 설계·감리
- **게시일:** 2026-02-23
- **마감일:** 2026-04-16 15:00
- **검토 채널:** current Telegram channel
- **원문 접근:** KOICA local bid detail POST flow

## Why this repo exists
이 저장소는 해당 KOICA 현지입찰 건이 단순 수집 단계에서 끝나지 않고,
**원문/첨부/초기 분석을 실제 검토 가능한 수준으로 정리할 가치가 있다**고 판단되어 생성한 private repo다.

이번 샘플은 GitHub-first 파이프라인의 첫 실전 적용 사례이기도 하다.
즉 수집 직후 repo를 생성하고, 원문과 첨부, brief, 상태 추적을 모두 이 repo 안에 누적하는 운영 모델을 검증하기 위한 기준 샘플이다.

## Current status
- 첨부파일 목록 추출 완료
- Playwright + DEXT5 기반 첨부 다운로드 성공
- 첨부 원문 **14 / 14 다운로드 완료**
- `ITB`, `BDS`, `ToR` 텍스트 추출 완료
- 초기 opportunity brief 작성 완료
- 상태 추적용 GitHub issue 생성 완료
- 현재 판단: **watchlist 상단 ~ manager-review 후보**

## One-line view
디지털 전환 / 국가 정보화 역량 강화 / ICT 교육센터라는 전략 신호는 강하지만,
실제 범위는 **설계·엔지니어링·감리** 중심이라 유비온 단독 core fit은 조건부다.

## Key facts
- **Invitation No.:** `KG-2026-01`
- **Employer:** `KOICA Office in the Kyrgyz Republic`
- **Project purpose:** `New Construction of ICT Education Center`
- **Plot location:** `Ch. Aitmatov Avenue, 104v, Bishkek`
- **Plot area:** `1.0 ha`
- **Gross floor area:** `1,179 m2 (±5%)`, two-story building
- **Construction budget limit:** `USD 1,704,050`
- **Deliverable language:** English and Russian

## RFP / ToR key takeaways
### What the service actually covers
- ICT 교육센터 신축을 위한 **설계 및 Author Supervision 서비스** 조달
- 단순 개념 설계가 아니라 **survey + layout option + detailed design + construction document + bidding support + author’s supervision**까지 포함
- 설계 패키지에는 아래 영역이 광범위하게 포함됨
  - structural
  - architectural
  - interior
  - plumbing / sanitary
  - mechanical
  - electrical
  - HVAC
  - ICT
  - firefighting

### Required design phases
- Preliminary design
- SD (Schematic Design)
- DD (Design Development)
- CD (Construction Document)

각 단계마다 KOICA 및 관련 주체 승인과 제출이 필요하다.

### Important submission / operating implications
- 산출물은 **영어 및 러시아어** 기준 제출 필요
- 계약 전 `Design Implementation Plan` 제출 요구가 보임
- PM 및 참여 엔지니어 인력의 CV/자격 자료 제출 요구가 보임
- 설계 완료 목표는 계약 효력 발생일 기준 **9개월 이내**
- 현지입찰 특성상 현지 등록, 법적 요건, 파트너 조건을 별도 점검해야 함
- 공사 발주 이전 단계의 설계/감리와 입찰지원 성격이 강함

### Additional RFP signals
- KOICA/CM 구조 하에서 consultant가 contractor 선정 지원과 공사 단계 기술행정 지원까지 관여
- 발주 준비를 위한 addenda 작성, bidder document review, contractor unit price review까지 범위가 확장됨
- 기대 인력 수준이 높아 PM(Architect 15년+), Architect 10년+, 다수 기술엔지니어 7년+ 수준의 team 구성이 암시됨

### Why this matters for Ubion
- `디지털 전환`
- `국가 정보화 역량 강화`
- `ICT 교육센터`
라는 구조는 강한 전략 시그널이다.
- 다만 실제 과업은 교육 플랫폼 구축보다 **건축/설계/감리 프로젝트 관리형**에 더 가깝다.
- 따라서 유비온 단독보다는 **설계/감리 파트너와의 협업 또는 sub/consortium 구조**가 현실적이다.

## Fit assessment
### Strategic fit
**medium-high**
- 디지털 전환 + 국가 정보화 + ICT 교육센터라는 방향은 유비온 관심 사업군과 직접 연결된다.

### Business fit
**medium**
- 교육 관련 키워드는 강하지만, 실제 계약 범위가 설계·감리 중심이다.

### Execution fit
**conditional**
- 에듀테크 단독 수행형 사업이 아니라, 엔지니어링/설계 역량이 필요한 구조다.

### Win potential
**unknown / conditional**
- 자격요건, 현지 파트너 조건, 실적 기준의 상세 확인이 필요하다.

### Effort efficiency
**medium**
- 첨부 확보와 문서 구조화는 잘 되었기 때문에 후속 검토 효율은 좋다.

## Main risks / caution
- 핵심 범위가 에듀테크 솔루션 개발이 아니라 설계·감리 서비스라는 점
- 영어 + 러시아어 제출 요구로 문서 준비 난이도가 높아질 수 있음
- 현지입찰 자격 및 현지 파트너링 요구를 놓치면 초기 판단이 왜곡될 수 있음
- 제목만 보면 “교육/디지털 사업”처럼 보이지만, 실제론 인프라/설계 성격이 훨씬 강함

## Key documents
### Source
- [`source/notice/source-access.md`](./source/notice/source-access.md)
- [`0. Cheklist for bidders documents.docx`](./source/attachments/0.%20Cheklist%20for%20bidders%20documents.docx)
- [`Section 1 - Instructions to Bidders (ITB).docx`](./source/attachments/Section%201%20-%20Instructions%20to%20Bidders%20(ITB).docx)
- [`Section 2 - Bid Data Sheet (BDS).docx`](./source/attachments/Section%202%20-%20Bid%20Data%20Sheet%20(BDS).docx)
- [`Section 4 - Request for Proposal (RFP).doc`](./source/attachments/Section%204%20-%20Request%20for%20Proposal%20(RFP).doc)
- [`Section 5 - Terms of Reference (ToR).docx`](./source/attachments/Section%205%20-%20Terms%20of%20Reference%20(ToR).docx)
- [`Section 6 (Annex 1) Space Program MM.pdf`](./source/attachments/Section%206%20(Annex%201)%20Space%20Program%20MM.pdf)

### Analysis
- [`analysis/opportunity-brief.md`](./analysis/opportunity-brief.md)
- [`analysis/project-status.md`](./analysis/project-status.md)
- [`analysis/rfp-key-takeaways.md`](./analysis/rfp-key-takeaways.md)
- [`analysis/manager-brief.md`](./analysis/manager-brief.md)
- [`analysis/qualification-compliance-summary.md`](./analysis/qualification-compliance-summary.md)
- [`analysis/scope-deliverables-summary.md`](./analysis/scope-deliverables-summary.md)

### PM
- [`pm/project-execution-plan.md`](./pm/project-execution-plan.md)
- [`pm/wbs.md`](./pm/wbs.md)
- [`pm/risk-issue-log.md`](./pm/risk-issue-log.md)
- [`pm/project-status.md`](./pm/project-status.md)
- [`pm/communication-log.md`](./pm/communication-log.md)
- [`pm/budget-tracker.md`](./pm/budget-tracker.md)
- [`pm/decision-log.md`](./pm/decision-log.md)

### Deliverables
- [`deliverables/deliverables-inventory.md`](./deliverables/deliverables-inventory.md)

### Meetings
- [`meetings/kickoff-meeting-notes.md`](./meetings/kickoff-meeting-notes.md)

### Archive
- [`archive/collection-log.md`](./archive/collection-log.md)

### Drafts
- [`drafts/newsletter-draft.md`](./drafts/newsletter-draft.md)
- [`drafts/proposal-draft-v0.1.md`](./drafts/proposal-draft-v0.1.md)
- [`drafts/full-proposal-body-draft.md`](./drafts/full-proposal-body-draft.md)
- [`drafts/proposal-package-plan.md`](./drafts/proposal-package-plan.md)

## Links
- KOICA list page: https://nebid.koica.go.kr/oep/lobi/localBidManageList.do
- Detail flow endpoint: `https://nebid.koica.go.kr/oep/lobi/localBidManageDetail.do`
- Repo URL: https://github.com/scottnaddle/oda-koica-kyrgyz-ict-education-center-l2026-00007
- Status issue: https://github.com/scottnaddle/oda-koica-kyrgyz-ict-education-center-l2026-00007/issues/1
- Newsletter recipient (default): `scott@naddle.net`

## Immediate next actions
1. `BDS / ITB` 기준으로 **입찰참가 자격요건 / 현지 등록 / 제출 규칙**을 더 구체적으로 추출
2. `RFP` `.doc` 본문까지 열어 **평가 포인트 / 과업 상세 / 제출 요구 문서**를 추가 요약
3. 영업관리자 기준으로 `watchlist` 유지인지 `manager-review` 승격인지 판단
4. 진행 결정 시 proposal 준비용 세부 issue 세트 생성

## Status history
- 2026-03-11: KOICA local bid 목록에서 후보 수집
- 2026-03-11: `L2026-00007-1`를 우선 검토 후보로 선택
- 2026-03-11: 첨부 14개 메타데이터 확인
- 2026-03-11: 첨부 14개 전체 다운로드 성공
- 2026-03-11: `ITB`, `BDS`, `ToR` 텍스트 추출 및 초기 brief 생성
- 2026-03-11: GitHub-first 파이프라인 샘플 repo 생성 및 push 완료
