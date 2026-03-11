# Source Access

## KOICA Local Tender Detail Access
- Endpoint: `https://nebid.koica.go.kr/oep/lobi/localBidManageDetail.do`
- Method: `POST`
- Fields:
  - `P_LOAZ_BID_PBLANC_NO=L2026-00007`
  - `P_PBLANC_ODR=1`
  - `resourceName=oep05001`

## Notes
- Direct GET to detail endpoint is not enough; POST detail flow is required.
- Attachments were downloaded successfully via Playwright + DEXT5 browser runtime automation.
