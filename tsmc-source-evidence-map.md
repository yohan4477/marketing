# TSMC 밸류체인 — 출처 / 근거 지도

기준: 2025A ~ 2026 Current

---

## A. 1차 출처 — SEC / 기업 제출 서류

### 1. TSMC

출처: TSMC 2025 Form 20-F, TSMC 2026 1분기/2분기 실적 발표 및 경영보고서, 콘퍼런스 콜

알게 된 것:
- 2025년 최대 고객 = 19%
- 2025년 2위 고객 = 17%
- 상위 10개 고객 = 78%
- 고객 집중도 변화
- 주요 웨이퍼/소재 조달 구조
- 2026년 2분기 매출
- HPC 매출 비중
- N2/N3/N5/N7 매출 비중
- 2026년 설비투자 가이던스

근거 등급: **1차 / 기업 공시**

주의: TSMC 20-F는 19%, 17% 고객의 이름을 직접 공개하지 않는다. 따라서 NVIDIA/Apple 대응에는 별도 근거가 필요하다.

### 2. NVIDIA

출처: NVIDIA FY2026 Form 10-K

알게 된 것:
- NVIDIA가 웨이퍼 제조에 TSMC를 사용
- Samsung도 일부 파운드리 소스
- TSMC CoWoS 사용
- NVIDIA → TSMC 관계 직접 확인

근거 등급: **1차 / SEC 확인**

주의: NVIDIA 파운드리 지출 중 TSMC 비중은 공개되지 않는다.

### 3. AMD

출처: AMD FY2025 Form 10-K

알게 된 것:
- HPC 웨이퍼에 TSMC 사용
- FPGA에 TSMC 사용
- Adaptive SoC에 TSMC 사용
- 일부 12/14nm HPC 제품은 GlobalFoundries 사용

근거 등급: **1차 / SEC 확인**

해석: AMD의 선단 제품에서 TSMC 의존도가 높다는 점은 강하게 확인된다. 다만 AMD 전체 웨이퍼 지출 중 TSMC 비중은 미공개다.

### 4. Qualcomm

출처: Qualcomm FY2025 Form 10-K

알게 된 것 — 주요 파운드리 공급사:
- TSMC
- Samsung
- GlobalFoundries

근거 등급: **1차 / SEC 확인**

주의: Qualcomm → TSMC 정확한 조달 비중은 미공개다.

### 5. Marvell

출처: Marvell 2026 Form 10-Q (기간 종료일 2026-08-01)

핵심 공시 문구:

> "TSMC is currently our sole source foundry for all of our advanced process-node wafers."

알게 된 것:
- Marvell 선단 노드 웨이퍼 = TSMC 단독 공급
- 3nm 등 선단공정에서 TSMC 의존

근거 등급: **1차 / SEC 확인**

중요: "Marvell 모든 웨이퍼 = TSMC 100%"가 아니다. "선단 공정 노드 웨이퍼 = TSMC 단독 공급"이 정확한 표현이다.

---

## B. 업스트림 장비 — 1차 출처

### 6. KLA

출처: KLA FY2024 / FY2025 / FY2026 Form 10-K

알게 된 것:
- TSMC가 3년 연속 10% 초과 고객
- FY2026 대만 매출 = 26.8%
- FY2026 매출 ≈ $13.58B
- 최대 단일 고객 집중도 ≈ 19%

추론: TSMC 정체와 고객 집중도를 대조해 TSMC 관련 KLA 매출을 약 $2.6B 수준으로 추정한다.

근거 등급:
- TSMC 10% 초과 관계 = **1차 확인**
- 정확한 $2.6B = **도출값 / 확신도 높음**

### 7. Applied Materials

출처: Applied Materials FY2026 10-Q (1월 / 4월 / 7월 제출분)

알게 된 것:

| 기간 | 상위 고객 비중 |
|---|---|
| 2026 1분기 | 19%, 16% |
| 2026 상반기 | 21%, 15% |
| 2026 9개월 누계 | 20%, 14% |

또한 파운드리/로직 비중이 확대되고 있다.

근거 등급: 고객 집중도 = **1차 확인**

주의: AMAT는 해당 고객의 이름을 직접 공개하지 않는다. 따라서 "TSMC = 20%"는 확인된 사실이 아니고, "TSMC가 최대 고객일 가능성이 높다"가 추론이다.

### 8. Lam Research

출처: Lam Research FY2025 / FY2026 Form 10-K

알게 된 것 — 주요 고객: TSMC, Samsung, Micron, SK hynix

FY2026 고객 집중도: 16%, 15%, 12%, 12%

다만 숫자와 고객 이름을 직접 연결하지 않는다. 따라서 TSMC 비중은 12~16% 후보 구간에 있다.

Lam FY26 매출 ≈ $23.2B → TSMC 관련 매출 도출 구간 ≈ **$2.8B ~ $3.7B**

근거 등급:
- 거래 관계 = **1차 확인**
- 정확한 비중 = **미상**
- $2.8~3.7B = **도출 구간**

### 9. Entegris

출처: Entegris FY2025 Form 10-K

Entegris 매출에서 TSMC가 차지한 비중:

| 연도 | 비중 |
|---|---:|
| 2023 | 11% |
| 2024 | 16% |
| 2025 | 16% |

근거 등급: **1차 / SEC 확인**

중요: 이 숫자는 "TSMC가 Entegris 매출의 16%"라는 뜻이지, "TSMC 소재 구매의 16%가 Entegris"라는 뜻이 아니다.

### 10. Qnity

출처: Qnity FY2025 Form 10-K

알게 된 것:
- Samsung = 11%
- TSMC = 8%

근거 등급: **1차 / SEC 확인**

---

## C. 실리콘 웨이퍼

### 11. TSMC 과거 20-F

출처: TSMC Form 20-F

TSMC가 직접 공개한 주요 웨이퍼 공급사:
- Formosa SUMCO Technology
- GlobalWafers
- Shin-Etsu Handotai
- Siltronic
- Soitec
- SUMCO

이 6개 업체가 TSMC 웨이퍼 수요에서 차지한 비중:

| 연도 | 비중 |
|---|---:|
| 2021 | 96.0% |
| 2022 | 95.0% |
| 2023 | 96.2% |

근거 등급: **1차 / TSMC 공시**

주의 두 가지:
1. 6개 업체 **합계**다. Shin-Etsu = X%, SUMCO = Y% 같은 개별 공급사 비중은 알 수 없다.
2. 96.2%는 2023년 데이터다. 2026년 현재 비중으로 쓰면 안 된다.

---

## D. Bloomberg 공급망 데이터

### 12. Baines / Rolf / Germann (2026)

출처: Economic Geography, 2026년 게재. 기반 데이터는 Bloomberg Professional 공급망 관계 데이터.

TSMC 공급사 원가 익스포저:

| 공급사 | 비중 |
|---|---:|
| ASML | 15.2% |
| Applied Materials | 15.1% |
| Lam Research | 8.4% |
| Tokyo Electron | 5.4% |
| 합계 | 44.1% |

다운스트림:

| 고객 | 비중 |
|---|---:|
| NVIDIA | 19.0% |
| Apple | 17.0% |
| AMD | 5.2% |
| Qualcomm | 5.1% |

근거 등급: **2차 데이터셋 / 추정치**

매우 중요 — 왼쪽과 오른쪽 비율의 의미가 다르다.
- 공급사 → TSMC: 고객 원가 중 그 공급사와 연관된 비율
- TSMC → 고객: 공급사 매출 중 그 고객과 연관된 비율

따라서 ASML 15.2%는 ASML의 리소그래피 시장 점유율이 아니고, NVIDIA 19%는 NVIDIA 파운드리 조달 중 TSMC 비중이 아니다.

---

## E. 장비 시장 점유율

### 13. 유럽위원회 반도체 장비 분석

출처: European Commission Staff Working Document, 2026. 기반 벤치마크는 주로 2023년 반도체 장비 시장 데이터.

리소그래피:

| 업체 | 점유율 |
|---|---:|
| ASML | ~92% |
| ASML (EUV) | ~100% |

레지스트 처리 / 도포·현상:

| 업체 | 점유율 |
|---|---:|
| Tokyo Electron | ~92% |

증착:

| 업체 | 점유율 |
|---|---:|
| Applied Materials | ~54% |
| Lam Research | ~14% |
| Tokyo Electron | ~13% |
| ASM | ~10% |

건식 공정 / 식각:

| 업체 | 점유율 |
|---|---:|
| Lam Research | ~44.5% |
| Tokyo Electron | ~21% |
| Applied Materials | ~18% |

습식 공정:

| 업체 | 점유율 |
|---|---:|
| SCREEN | ~35% |
| Tokyo Electron | ~21% |
| Lam Research | ~16% |

검사 / 계측:

| 업체 | 점유율 |
|---|---:|
| KLA | ~60% |
| Applied Materials | ~12% |
| ASML | ~6% |

레티클 검사:

| 업체 | 점유율 |
|---|---:|
| Lasertec | ~50% |
| KLA | ~43% |
| Zeiss | ~5% |

근거 등급: **2차 / 시장 점유율 데이터**

주의: 대부분 2023년 글로벌 시장 점유율이다. 따라서 "KLA가 TSMC 검사의 정확히 60%"라고 말할 수 없다. 정확한 표현은 "글로벌 검사/계측 시장에서 KLA가 약 60%이며, TSMC 기준 비중도 높을 것으로 추정되지만 정확한 값은 공개되지 않았다"이다.

---

## F. ZEISS → ASML

### 14. Bloomberg 공급망 관계 데이터 (2026년 Economic Geography 논문 경유)

알게 된 것:
- ZEISS → ASML 원가 익스포저 ≈ 28%
- ASML → TSMC 원가 익스포저 ≈ 15.2%

따라서 2단 체인이 중요하다.

```
ZEISS → ASML → TSMC
```

근거 등급: **2차 / Bloomberg 공급망 추정치**

---

## G. 숫자를 읽는 방법

### 확인된 것

- TSMC FY25 최대 고객 = 19%
- TSMC FY25 2위 고객 = 17%
- TSMC → NVIDIA 제조 관계
- TSMC → AMD 제조 관계
- TSMC → Qualcomm 관계
- Marvell 선단 노드 → TSMC 단독 공급
- Entegris 매출 중 TSMC = 16%
- Qnity 매출 중 TSMC = 8%
- KLA 매출 중 TSMC 10% 초과
- 웨이퍼 공급사 6곳 → 2023년 TSMC 웨이퍼 수요의 96.2%

### 확신도 높은 도출값 / 데이터셋

| 관계 | 값 |
|---|---:|
| NVIDIA → TSMC 매출 기여 | ≈19% |
| Apple → TSMC 매출 기여 | ≈17% |
| AMD | ≈5.2% |
| Qualcomm | ≈5.1% |
| ASML → TSMC 원가 익스포저 | ≈15.2% |
| AMAT → TSMC 원가 익스포저 | ≈15.1% |
| Lam → TSMC 원가 익스포저 | ≈8.4% |
| TEL → TSMC 원가 익스포저 | ≈5.4% |

### 글로벌 시장 점유율 — TSMC 기준 비중이 아님

| 항목 | 값 |
|---|---:|
| ASML 리소그래피 | ≈92% |
| ASML EUV | ≈100% |
| TEL 도포/현상 | ≈92% |
| AMAT 증착 | ≈54% |
| Lam 건식 식각 | ≈44.5% |
| KLA 검사/계측 | ≈60% |
| SCREEN 습식 공정 | ≈35% |
| Lasertec 레티클 검사 | ≈50% |

### 미상 — 주장하면 안 되는 것

- TSMC 리소그래피 조달 중 ASML 정확한 비중
- TSMC 식각 조달 중 Lam 정확한 비중
- TSMC 증착 조달 중 AMAT 정확한 비중
- TSMC 웨이퍼 조달 중 Shin-Etsu, SUMCO, GlobalWafers 각각의 정확한 비중
- NVIDIA 파운드리 조달 중 TSMC 정확한 비중
- AMD 파운드리 조달 중 TSMC 정확한 비중

---

밸류체인 본문은 [tsmc-value-chain.md](tsmc-value-chain.md) 참고.
