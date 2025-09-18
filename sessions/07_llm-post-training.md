# 한눈에 알아보는 LLM post-training

## 발표자
- 조재경 | SK텔레콤 AI LLM Research

## 시간
- 14:30 ~ 15:10

## 세션 개요
SFT, RLHF, DPO, KD, Reasoning, RLVR 등 LLM 파인튜닝 기법 소개

## 강의 내용
### 확장되는 LLM 생태계 : 빠르고 쉽게 확정
- LLM을 사용하는 사람들
- LLM API를 활용해 서비스를 만드는 사람들
- LLM을 만드는 사람들

### 1. LLM Post-training 개념
- LLM 지식을 사람이 유용하게 사용할 수 있도록 학습
- Pre-training: 일반 지식 학습
- Post-training: 실제 사용 목적에 맞게 지식 조정
- **SFT (Supervised Fine-Tuning)**: 긍정적 답변만 학습, 인간 선호 맞춤
- **RLHF (Reinforcement Learning with Human Feedback)**: 선호도 데이터 → Reward Model 학습 → 강화 학습
- **DPO (Direct Preference Optimization)**: 선호도 기반 학습
- **KD (Knowledge Distillation)**: 고성능 모델 지식 작은 모델로 전이

### 2. 2025년 LLM Post-training 트렌드
- 단계적 사고(think step by step) 활용 → 모델 응답 개선
- RLHF 주의점: 학습 불안정, reward hacking 가능
- RLVR: 정답 기반 강화 학습
- Reasoning + RLVR: 복잡 문제 해결 능력 향상
  - 예: 국제수학올림피아드 문제, Git 이슈 해결

### 3. 향후 방향성
- Pre-training → Post-training → Frontier 돌파
- 고품질 합성 데이터 생성 및 데이터 분포 조정
- Pre-training 세밀하게 조정 → 모델 성능 극대화