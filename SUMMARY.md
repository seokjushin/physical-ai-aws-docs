# Table of contents

* [Physical AI on AWS](README.md)

## Overview

* [Physical AI란?](overview/physical-ai.md)
* [왜 지금 Physical AI인가?](overview/physical-ai-1.md)
* [Physical AI 구현에 필요한 기술](overview/physical-ai-2.md)
* [왜 AWS를 선택해야 하는가?](overview/aws.md)
* [End-to-end Reference Architecture](overview/end-to-end-reference-architecture.md)

## Physical AI on AWS 구현 가이드 <a href="#physical-ai-on-aws-guide" id="physical-ai-on-aws-guide"></a>

* [1. 데이터 (Data)](physical-ai-on-aws-guide/1.-data/README.md)
  * [로봇 데이터 수집 파이프라인](physical-ai-on-aws-guide/1.-data/undefined.md)
  * [데이터 전처리 / 라벨링](physical-ai-on-aws-guide/1.-data/undefined-1.md)
  * [모범 사례](physical-ai-on-aws-guide/1.-data/undefined-2.md)
* [2. 학습 (Training)](physical-ai-on-aws-guide/2.-training/README.md)
  * [학습 방법](physical-ai-on-aws-guide/2.-training/undefined.md)
  * [학습 환경 구축](physical-ai-on-aws-guide/2.-training/undefined-1.md)
  * [NVIDIA GR00T N1](physical-ai-on-aws-guide/2.-training/nvidia-gr00t-n1.md)
* [3. 시뮬레이션 (Simulation)](physical-ai-on-aws-guide/3.-simulation/README.md)
  * [Isaac Sim 환경 구축](physical-ai-on-aws-guide/3.-simulation/isaac-sim.md)
  * [대규모 시뮬레이션](physical-ai-on-aws-guide/3.-simulation/undefined.md)
  * [NVIDIA Cosmos WFM on Amazon EKS](physical-ai-on-aws-guide/3.-simulation/nvidia-cosmos-wfm-on-amazon-eks.md)
* [4. Sim2Real](physical-ai-on-aws-guide/4.-sim2real.md)
* [5. 오케스트레이션 (Agentic Orchestration)](physical-ai-on-aws-guide/5.-agentic-orchestration.md)

## Robot Foundation Model

* [World Foundation Model](robot-foundation-model/world-foundation-model/README.md)
  * [NVIDIA Cosmos World Foundation Model](robot-foundation-model/world-foundation-model/nvidia-cosmos-world-foundation-model.md)
* [Robot Foundation Model](robot-foundation-model/robot-foundation-model/README.md)
  * [VLA (Vision-Language-Action) 모델](robot-foundation-model/robot-foundation-model/vla-vision-language-action/README.md)
    * [DeepMind RT-2](robot-foundation-model/robot-foundation-model/vla-vision-language-action/deepmind-rt-2.md)
    * [OpenVLA](robot-foundation-model/robot-foundation-model/vla-vision-language-action/openvla.md)
    * [Gemini Robotics](robot-foundation-model/robot-foundation-model/vla-vision-language-action/gemini-robotics.md)
    * [NVIDIA GR00T N1](robot-foundation-model/robot-foundation-model/vla-vision-language-action/nvidia-gr00t-n1.md)
