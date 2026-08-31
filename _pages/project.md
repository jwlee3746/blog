---
title: "선별 프로젝트"
permalink: /Project/
layout: single
comments: false
author_profile: true
---

현재는 LLM이 실제 제품 안에서 안정적으로 동작하게 만드는 문제를 다룹니다. 이전에는 산학 협력 프로젝트로 생성 모델, 준지도 학습, 한국어 QA를 연구했습니다.

## LLM · 에이전트 시스템

### [jw-agent-playbook](https://github.com/jwlee3746/jw-agent-playbook)

LLM 에이전트의 프롬프트·하네스 전략과 반복해서 사용하는 설정을 정리한 저장소입니다.

### [LangChain deepagents SDK 0.7 업데이트 정리]({{ site.baseurl }}/Etc/deepagents-0-7/)

에이전트 하네스의 토큰 사용량, 미들웨어 구성, 파일시스템 도구와 백엔드 변경을 실제 마이그레이션 관점에서 정리했습니다.

## 산학 협력 프로젝트

### [MVM+ · 생성 모델에 metric 심기]({{ site.baseurl }}/Project/mvm-plus/)

Metric learning 기반 생성 모델을 설계하고 Average Hausdorff loss를 고안했습니다. 학부 산학 연계 인턴으로 수행한 별도 연구 개발 프로젝트입니다.

### KAIST × 네이버

두 학부 산학 협력 프로젝트를 하나의 묶음으로 정리했습니다.

- [네이버 쇼핑 이미지 준지도 분류]({{ site.baseurl }}/Project/naver-shopping-semisup/) — RandAugment와 변형 MixMatch로 top-1 정확도 56.42 → 69.62%
- [네이버 스니펫 오픈도메인 QA]({{ site.baseurl }}/Project/naver-snippet-qa/) — 90%가 unanswerable인 학습 데이터의 불균형을 보완해 test 점수 36.0 → 41.9
