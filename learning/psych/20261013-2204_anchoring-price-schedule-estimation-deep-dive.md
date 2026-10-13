---
type: 학습노트
project: 클라우드학습
id: P014
date: 2026-10-13
status: 초안
model: claude-opus-5-5
source: https://arxiv.org/abs/1804.03919
tags: [psych, 앵커링, 기준점효과, 일정추정, 견적, 계획오류, 참조집단예측, 첫제안, 재현성]
---

# 앵커링 효과 (심화편): 먼저 들은 숫자가 견적·일정을 끄는 방식과 끊는 법

## ① 3줄 요약 (결론 먼저)
1. 앵커링은 재현 위기에서 살아남았다. 개발자 410명의 생산성 추정이 질문 속 숫자 하나로 갈렸고(d≈1.19)[1], Many Labs 1에서도 크게 재현됐다[10][11]. 단, '잠재의식 앵커'는 재현에 실패했다[10].
2. 일정 과소추정의 뿌리는 계획 오류(내부 관점)이고, 앵커링은 남의 숫자로 그것을 고정한다. 비전문가의 숫자라는 걸 알아도 끌려간다[1][2][4].
3. 아는 것만으로는 못 막는다. 편향 교육은 효과를 줄였을 뿐이다(d≈0.72)[1]. 숫자를 듣기 전 독립 추정, 반대 근거, 과거 실적 분포라는 절차가 답이다[4][6].

기초 사례(1974년 원실험, 부동산 중개인, 사회보장번호 앵커 재현 논란)는 [「가치 사다리」 노트 6절](../money/20261010-0736_value-ladder-product-design.md) 참고.

## ② 핵심 개념 7가지

**1) IT 견적: 비전문가의 숫자도 닻이 된다**
Shepperd 등이 개발자 410명에게 지난 생산성이 시간당 1줄(LOC)보다 많았는지, 또는 200줄보다 적었는지 물은 뒤 추정하게 하자 두 집단 차이가 약 350%였다(robust d≈1.19)[1]. 고객에게 추정 능력이 없다고 알려 줘도 고객의 기대 기간이 추정을 끌었고, 당사자들은 영향을 부인하거나 '조금'이라 했다(Jørgensen·Sjøberg 2004). 경험 없다고 밝힌 사람의 '두 달쯤'도 같았다(Aranda·Easterbrook 2005)[1][2].

**2) 반론: 표본은 작았고 현장에선 약해진다**
초기 연구는 연구당 20명 안팎이라 검정력이 낮았다[2]. Gren 등의 실험 6개(N=461)에선 '폐기' 표시 요구사항만 보여도 공수가 과대추정됐지만, 현장 설정에선 효과가 작아졌다[2]. 과소추정은 공학·경영 연구에선 흔해도 심리학 연구에선 아니었다. 공수와 완료일을 섞은 연구도 많았다[3].

**3) 계획 오류와 무엇이 다른가**

| 구분 | 계획 오류 | 앵커링 |
|---|---|---|
| 출발점 | 머릿속 최선 시나리오 | 먼저 접한 숫자 |
| 방향 | 대체로 과소추정 | 닻 쪽(위·아래) |
| 처방 | 외부 관점 | 독립 추정·반대 고려 |

Flyvbjerg 정리에 따르면 둘은 겹친다. 기획자는 최선안이나 자기 조직의 좁은 경험에 닻을 내린다. 도시철도 경험을 닻 삼아 고속철을 계획한 홍콩의 한 운영사는 비용·일정을 크게 넘겼다[4].

**4) 가격의 닻: 첫 제안과 정밀도**
Galinsky·Mussweiler의 실험 3개에서 먼저 제안한 쪽이 더 좋은 결과를 얻었고, 첫 제안은 최종가를 강하게 예측했다. 그러나 받는 쪽이 상대의 대안·유보가격이나 자기 목표가에 집중하면 그 이점이 사라졌다[6]. 비전문가에겐 정밀한 가격일수록 닻이 강했다. 부동산 중개인 400명 사전등록 연구는 정밀 앵커의 이점을 재현했지만, 과하게 정밀한 가격은 전문가에게 역효과였다[7]. 협상 전반은 P011 노트.

**5) 전문가도 예외가 아니다**
경력 법률가들은 주사위로 정한 구형에도 끌려갔고, 경력은 효과를 줄이지 못했다[8]. 법률 판단 29개 연구(N=8,549) 메타분석에선 통제집단 유무에 따라 d=0.58~0.91이었으나 출판 편향 흔적이 있다[9].

**6) 재현성 성적표**
Many Labs 1(36개 표본, 6,344명)은 16개 현상 중 14개를 재현했고 앵커링은 매우 큰 효과로 재현됐다[10][11]. 잠재의식 앵커는 사전등록 재현 2건에서 실패했다[10]. '앵커에 약한 사람'을 재는 개인차 점수는 신뢰도가 매우 낮거나 0이었고, 미리 경고해도 효과가 났다[12]. 사람 선별보다 절차 설계가 답이다.

**7) 대응: 교육은 절반, 나머지는 절차**
2~3시간 워크숍 후 효과는 d≈0.72, 편차는 약 3분의 1로 줄었지만 주로 높은 앵커 쪽이었고 무작위 배정도 아니었다[1]. Flyvbjerg는 유사 완료 사업의 기저율에 먼저 닻을 내리라며, 외부 관점을 "an anchor that is meaningful"이라 한 Tetlock·Gardner의 말을 인용한다[4]. 공공 IT 1,355건 예비 분석: 전형적 사업은 예산 내였지만 일정은 평균 24% 늘었고, 18%는 비용 25% 초과, 기간 1년당 비용 위험 4.2%p 증가(미국 자료 중심)[5].

## ③ 조차장 적용 3가지
1. **사업관리 보고**: 일정 산정 회의에서 발주처·상급자의 희망 기한을 듣기 전에 팀원 3명이 WBS 공수를 각자 적는다. 유사 사업 5~10건의 '실적÷계획' 배수를 붙이고, 보고서는 '독립 추정 / 참조 집단 보정 / 요청 기한' 세 칸으로 나눈다[1][4][5].
2. **후배 멘토링**: 두 조에 "장비 교체가 2일보다 오래 걸릴까?"와 "20일보다 짧을까?"를 묻고 소요일을 적게 한 뒤 평균을 비교한다. 교육해도 반쯤 남는다는 [1]을 보여 주고 '독립 추정→반대 근거 3개→과거 실적' 체크리스트를 팀 표준으로 정한다.
3. **강의료 책정**: 기관이 예산을 말하기 전에 준비 시간·교재 개발 근거를 붙여 먼저 제안한다[6]. '34만 5천 원' 정도의 정밀함은 괜찮지만 원 단위 금액은 피한다[7]. 상대가 먼저 숫자를 던지면 미리 적어 둔 목표가와 상대의 대안을 보며 대화한다[6].

## ④ 오늘 바로 해볼 연습 (10분)
다음 달 작업 하나를 고른다. ① 3분: 들은 숫자는 가리고 3~5개로 쪼개 최선·보통·최악 공수를 적는다. ② 4분: 비슷한 작업 3건의 '실적÷계획' 배수를 구한다. ③ 3분: 처음 들은 숫자가 틀렸을 이유 3가지를 쓰고 최종 추정을 한 줄로 남긴다.

## ⑤ 퀴즈 3문
1. 편향 교육의 효과는[1]? (가) 앵커링 제거 (나) 줄었지만 남음 (다) 없음
   - 정답: (나). 해설: d 1.19→0.72. 주로 높은 앵커 쪽만 줄었고 무작위 배정이 아니었다.
2. 고객이 "두 달이면 되죠?"라고 한 뒤 팀 추정이 두 달 근처로 모였다. 원인과 처방은?
   - 정답: 앵커링. 해설: 계획 오류는 외부 숫자 없이도 생기는 낙관이다. 숫자를 듣기 전 독립 추정과 참조 집단 비교가 처방이다.
3. 틀린 것은? (가) 고전적 앵커링은 Many Labs 1에서 재현 (나) 잠재의식 앵커는 재현 실패 (다) 개인차 점수로 앵커에 약한 사람을 가려낼 수 있다
   - 정답: (다). 해설: 신뢰도가 매우 낮거나 0이었다[12].

## ⑥ 더 공부할 거리
- Halkjelsvik·Jørgensen, 『Time Predictions』(2018, 오픈액세스) — https://doi.org/10.1007/978-3-319-74953-2
- Flyvbjerg·Gardner, 『How Big Things Get Done』(2023): 참조 집단 예측 대중서

## ⑦ 출처
1. ✔ Shepperd 외, "An Experimental Evaluation of a De-biasing Intervention for Professional Software Developers"(2018) — https://arxiv.org/abs/1804.03919
2. ✔ Gren 외, "Is it Possible to Disregard Obsolete Requirements?"(2021, 초록·서론) — https://arxiv.org/abs/2103.13265
3. ✔ Halkjelsvik·Jørgensen, "From origami to software development"(2012, 초록) — https://pubmed.ncbi.nlm.nih.gov/22061688/
4. ✔ Flyvbjerg, "Top Ten Behavioral Biases in Project Management"(2021) — https://arxiv.org/abs/2202.00125
5. ✔ Budzier·Flyvbjerg, "Overspend? Late? Failure? What the Data Say About IT Project Risk in the Public Sector"(2012) — https://arxiv.org/abs/1304.4525
6. ✔ Galinsky·Mussweiler, "First offers as anchors"(2001, 초록) — https://pubmed.ncbi.nlm.nih.gov/11642352/
7. ✔ Frech 외, "How and Why Different Forms of Expertise Moderate Anchor Precision in Price Decisions"(2019, 초록) — https://pubmed.ncbi.nlm.nih.gov/31044670/
8. ✔ Englich 외, "Playing dice with criminal sentences"(2006, 초록) — https://pubmed.ncbi.nlm.nih.gov/16382081/
9. ✔ Bystranowski 외, "Anchoring effect in legal decision-making"(2021, 초록) — https://pubmed.ncbi.nlm.nih.gov/33734746/
10. ✔ Röseler 외, "Evidence against subliminal anchoring"(2021) — https://pmc.ncbi.nlm.nih.gov/articles/PMC7567524/
11. ✔ McShane 외, "Large Scale Replication Projects in Contemporary Psychological Research"(2018) — https://arxiv.org/abs/1710.06031
12. ✔ Weber·Röseler, "Testing the Reliability of Anchoring Susceptibility Scores"(2025) — https://pmc.ncbi.nlm.nih.gov/articles/PMC11960557/
