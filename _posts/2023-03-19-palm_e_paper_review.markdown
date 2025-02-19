---
layout: post
title:  "[Paper Review]PaLM-E : An Embodied Multimodal Language Nodel"
date:   2023-03-19 00:00:01 +0530
categories: Robotics LLM
---

이번에 구글 리서치에서 Multimodal Language Model을 기반으로 한 로봇제어 논문을 발표했습니다.
로보틱스 분야의 꿈이라고 생각되어왔던 '대화로 소통하고 혼자 생각하고 행동할 수 있는 로봇'이 LLM 발전에 힘입어 머지않았다는게 눈에 보입니다.

본 포스트에서는 해당 논문을 리뷰하도록 하겠습니다.

PaLM-E
---
보통 이름을 보면 해당 논문이 무엇을 목적으로 하는지 혹은 어떠한 원리인지 대략적으로 알 수 있지만, 이번 논문에서 PaLM은 어디서 왔으며 Embodied는 뭘 나타내는지 직관적으로 와닿지는 않습니다.
시작에 앞서 이부분에 대해 간략하게 소개하고 넘어가도록 하면, PaLM은 Pathways Language Model로 Google이 2021년에 소개한 [Pathways](https://blog.google/technology/ai/introducing-pathways-next-generation-ai-architecture/) 아키텍처를 기반으로 하는 Large Language Model을 의미하며, 해당 LLM 모델을 바탕으로 로봇이나 에이전트가 '물리적인 환경'에서 '구체화'되는 것을 목표로 학습시킨 모델이기 떄문에  PaLM-E 라고 이름지어졌습니다.