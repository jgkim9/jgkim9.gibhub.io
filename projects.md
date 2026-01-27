---
title: "Project"
layout: single
permalink: /projects/
classes: wide
sort_by: date 
sort_order: reverse
---
<style>
  /* 1. 리스트 항목 전체 여백 (더 촘촘하게) */
  .archive__item {
    margin-left: 25px !important; /* 항목 간 외부 간격 최소화 */
    margin-bottom: 0.2em !important; /* 항목 간 외부 간격 최소화 */
    padding-bottom: 0.4em !important; /* 구분선과의 간격 좁힘 */
    border-bottom: 1px solid #eeeeee !important;
  }

  /* 2. 제목 스타일 (글자 크기 유지, 상하 여백 제거) */
  .archive__item-title {
    margin-top: 0.1em !important;
    margin-bottom: 0 !important; /* 제목 바로 아래 설명글이 붙도록 설정 */
    font-size: 1.00em !important; /* Products 페이지와 맞추기 위해 살짝 조절 */
    line-height: 1.2 !important;
  }
  
  .archive__item-title a {
    color: #4979ae !important;
    text-decoration: underline !important;
    text-underline-offset: 3px;
  }

  /* 3. 설명글(excerpt) 스타일 (간격 및 폰트 최소화) */
  .archive__item-excerpt {
    margin-top: 0.1em !important; /* 제목 바로 아래 아주 살짝만 띄움 */
    margin-bottom: 0.1em !important;
    font-size: 0.9em !important;
    color: #666 !important;
    line-height: 1.4 !important; /* 줄 간격 축소 */
  }

  /* 4. 기타 실적 박스 여백 조절 */
  .extra-projects-box {
    margin-top: 25px; /* 리스트 끝난 후 간격도 줄임 */
    padding: 12px;
    background-color: #fcfcfc;
    border: 1px solid #e5e5e5;
    font-size: 0.95em;
    color: #555;
    text-align: center;
  }
</style>

VisionST는 AI 비전 인식, 특수 환경 모니터링, 산업용 자동화 솔루션 분야에서 독보적인 기술력을 보유하고 있습니다. 아래는 그동안 수행해온 주요 프로젝트들의 기록입니다.
 

<div class="entries-list">
  {% for project in site.projects %}
    <article class="archive__item">
      <h2 class="archive__item-title">
        <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
      </h2>
      {% if project.excerpt %}
        <div class="archive__item-excerpt">
          {{ project.excerpt | strip_html | truncate: 160 }}
        </div>
      {% endif %}
    </article>
  {% endfor %}
</div>

<div class="extra-projects-box">
  <i class="fas fa-plus-circle" style="color: #666;"></i> 기타: 다수의 프로젝트 수행 및 현장 적용 실적 보유
</div>