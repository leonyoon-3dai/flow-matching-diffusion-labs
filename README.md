# Flow Matching and Diffusion Models — 한국어 주석판 실습 노트북

MIT 6.S184 *Generative AI with Stochastic Differential Equations* 강의의 실습 노트북 3개에 **한국어 설명**을 추가한 저장소입니다. 원본 코드는 그대로 두고, 각 셀 앞에 한국어 요약/해설 마크다운 셀을 삽입했습니다.

## 노트북 목록

| # | 파일 | 주제 |
|---|---|---|
| 1 | [`lab1_odes_and_sdes.ipynb`](./lab1_odes_and_sdes.ipynb) | 상미분방정식(ODE)·확률미분방정식(SDE) 시뮬레이션 — Euler / Euler–Maruyama, 브라운 운동, Ornstein–Uhlenbeck 과정 |
| 2 | [`lab2_flow_matching_and_score_matching.ipynb`](./lab2_flow_matching_and_score_matching.ipynb) | 흐름 일치(Flow Matching)와 점수 일치(Score Matching) — 조건부/주변 벡터장, 가우시안 확률 경로, 2D 토이 분포 학습 |
| 3 | [`lab3_conditional_generative_model.ipynb`](./lab3_conditional_generative_model.ipynb) | 이미지용 조건부 생성 모델 — MNIST, Diffusion Transformer(DiT), VAE 기반 Latent Diffusion, Classifier-Free Guidance |

## 원본 출처

- Lab 1, 2: 강의 Google Drive 배포본
- Lab 3: [원본 Colab](https://colab.research.google.com/drive/1wKeiJBN4HS-7dsHQk_zd22Zfoc3ieJn9)
- 강의 홈: MIT 6.S184 (Peter Holderrieth, Ezra Erives 등)

원본 저작권은 강의 저자에게 있으며, 이 저장소는 학습용 한국어 주석을 덧붙인 버전입니다.

## 한국어 주석 표기 규칙

- 기존 영문 마크다운 셀 앞에는 `> 🇰🇷 **한국어 설명**`으로 시작하는 번역/요약 셀을 추가했습니다.
- 핵심 코드 셀(클래스·함수 정의 등) 앞에는 `> 🇰🇷 **코드 설명**`으로 시작하는 해설 셀을 추가했습니다.
- 단순 `import`·보일러플레이트 셀에는 주석을 생략했습니다.
- LaTeX 수식과 코드는 원본 그대로 유지했습니다.

## 사용 방법

```bash
git clone https://github.com/leonyoon-3dai/flow-matching-diffusion-labs.git
cd flow-matching-diffusion-labs
# Jupyter 환경에서 .ipynb 파일을 열거나, Colab에 업로드하여 실행
```
