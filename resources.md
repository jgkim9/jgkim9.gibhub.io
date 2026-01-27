---
title: "Technical Resources"
layout: single
permalink: /resources/
---

<style>
  /* 전체 컨테이너 여백 (왼쪽으로 shift) */
  .resource-container {
    padding-left: 25px; /* 왼쪽 시작 위치를 오른쪽으로 이동 */
    padding-right: 15px;
  }

  /* 1. 그리드 컨테이너 설정 */
  .resource-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px 30px; /* 항목 간 간격 확보 */
    margin-left: 0 !important;
    padding-left: 0 !important;
    list-style: none !important;
  }

  /* 2. 항목별 스타일 */
  .resource-item {
    padding: 6px 0;
    border-bottom: 1px solid #eeeeee;
  }

  /* 3. 제목 스타일 (Products 블루 적용) */
  .resource-title {
    display: block;
    font-size: 1.05em !important;
    font-weight: bold !important;
    line-height: 1.3 !important;
  }

  .resource-title a {
    color: #4979ae !important;
    text-decoration: underline !important;
    text-underline-offset: 4px;
  }

  /* 4. 하단 설명 텍스트 */
  .resource-desc {
    display: block;
    font-size: 0.85em !important;
    color: #888 !important;
    margin-top: 2px;
  }

  /* 5. 섹션 타이틀 (왼쪽 바 디자인 유지) */
  .section-title {
    margin-top: 2em;
    margin-bottom: 1em;
    padding-left: 12px;
    border-left: 5px solid #333;
    font-size: 1.25em;
    clear: both;
  }

  @media (max-width: 768px) {
    .resource-grid {
      grid-template-columns: 1fr;
    }
    .resource-container {
      padding-left: 15px; /* 모바일에서는 여백을 약간 줄임 */
    }
  }
</style>

<div class="resource-container">
  <p>VisionST의 제품 상세 사양서 및 기술 자료입니다. 각 항목을 클릭하면 상세 PDF 파일을 확인하실 수 있습니다.</p>

  <h3 class="section-title">📂 2선재 고속 모니터링 시스템 관련</h3>
  <ul class="resource-grid">
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/resources/SJ/SJ_AIComputer.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> AI 학습/인식용 컴퓨터</a></span>
      <span class="resource-desc">2선재 고속 모니터링 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/resources/SJ/SJ_SensorHoueing.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Sensor Housing</a></span>
      <span class="resource-desc">2선재 고속 모니터링 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/resources/SJ/SJ_HighSpeedCamera.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> High Speed Camera</a></span>
      <span class="resource-desc">2선재 고속 모니터링 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/resources/SJ/SJ_LEDLight.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> LED Spot Light</a></span>
      <span class="resource-desc">2선재 고속 모니터링 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/resources/SJ/SJ_MotorizedLens.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Motorized Lens</a></span>
      <span class="resource-desc">2선재 고속 모니터링 시스템용 사양서</span>
    </li>
  </ul>

  <h3 class="section-title">📂 출선구 영상분석 시스템 관련</h3>
  <ul class="resource-grid">
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/HighSpeedCamera.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> 출선구 고속카메라</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/MSCable.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> MS 커넥터 케이블</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/PanTiltMotor.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> 마이크로 팬틸트용 모터</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/Quartz.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Quartz</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/VortexCooler.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Vortex Cooler</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/ZLController.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Zoom Lens Controller</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
    <li class="resource-item">
      <span class="resource-title"><a href="{{ '/ZoomLens.pdf' | relative_url }}" target="_blank"><i class="far fa-file-pdf"></i> Zoom Lens</a></span>
      <span class="resource-desc">출선구 영상분석 시스템용 사양서</span>
    </li>
  </ul>
</div>