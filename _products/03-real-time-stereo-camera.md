---
title: "Real-Time Stereo Camera (FPGA-Based)"
date: 2026-01-27 
# header:
#   teaser: "/assets/images/RTStereoCamera.jpg"  # 제품 사진 경로
excerpt: "FPGA 하드웨어 가속 기반 실시간 스테레오 매칭 카메라"
categories:
  - Hardware
tags:
  - FPGA
  - Stereo Vision
  - Disparity Map
  - Real-Time
---
<img src="{{ '/assets/images/RTStereoCamera.jpg' | relative_url }}" class="align-center">

### ## 주요 특징 (Features)
* **FPGA 기반 하드웨어 가속**: 고성능 FPGA를 활용하여 복잡한 스테레오 매칭 연산을 실시간으로 처리합니다.
* **Trellis Dynamic Programming**: 고급 동적 계획법 알고리즘을 적용하여 정밀하고 안정적인 변위 맵(Disparity Map)을 생성합니다.
* **Systolic Array 구현**: 병렬 처리 아키텍처인 시스톨릭 어레이를 통해 연산 효율을 극대화하고 지연 시간을 최소화했습니다.
* **다층 실시간 매칭**: Multi-layered 리얼타임 이미지 매칭을 통해 깊이(Depth) 정보의 정확도를 높였습니다.

### ## 기술 사양 (Specifications)
| 항목 | 사양 |
|:---|:---|
| **핵심 알고리즘** | Trellis Dynamic Programming |
| **하드웨어 아키텍처** | Systolic Array (FPGA Implementation) |
| **주요 출력** | Real-time Stereo Disparity Map |
| **처리 방식** | Multi-layered Stereo Matching |

---

### ## 활용 분야 (Applications)
* **3D 거리 측정 및 인식**: 산업 현장에서의 객체와의 거리 측정 및 장애물 회피
* **자율 주행 로봇(AMR)**: 주변 환경의 깊이 정보를 실시간으로 파악하여 안전한 경로 생성
* **고속 공정 자동화**: 3차원 위치 정보가 필요한 자동화 라인의 시각 센서