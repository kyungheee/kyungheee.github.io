---
title: "자율주행 차량용 인공지능이 공유 저장소 시스템에 발생시키는 I/O 분석"
date: 2024-06-24
pubtype: "Paper & Presentation"
featured: true
description: "이 논문은 자율주행 차량 내 공유 저장소 시스템에서 나타날 수 있는 I/O 작업 패턴과 이에 대응하는 저장 장치의 응답 특성을 분석한다. 특히 자율주행 관련 AI 모델로 SAM, OpenCOOD 및 V2VNet을 선 정하고, 이들이 발생시키는 데이터 읽기 및 쓰기 작업의 빈도와 지연시간 변동성을 분석했다. 이러한 분 석은 각 모델의 데이터 처리 요구 사항에 기반하여 실험적으로 저장 장치의 성능을 최적화하는 방향을 제시하며, 이를 기반으로 공유 저장소 시스템을 개선하여 자율주행 차량이 요구하는 실시간성을 유지하 는 데 사용될 수 있다."
tags: ["Computer Vision","Autonomous Vehicle","Storage System"]
image: "/img/KCC_포스터.jpg"
link: "https://aiml-k.github.io/uploads/files/kcc2024/KCC2024_SharedStorage_RKLLJL.pdf"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---
{{< figure src="/img/KCC_포스터.jpg" alt="KCC 포스터" class="img-right" >}}

This talk looked at Liberty Mutual’s transformation to Continuous Integration, Continuous Delivery, and DevOps. For a large, heavily regulated industry, this task can not only be daunting, but viewed by many as impossible. Often, organizations try to reduce the friction through micro-fixes, but Eddie’s team asked how to change the culture to reduce the friction and concluded with the following final points:

- Don’t mandate DevOps. Give employees the chance to master their discipline with examples to set and follow.
- Favor deep end-to-end accomplishments over broad but incremental steps forward. Focus on taking the right teams far before encouraging broad adoption.
- Centralize the platforms and tools that your teams shouldn’t be thinking about. Provide foundational services/commodities and let teams stay on purpose.
- Incorporate contributions from everyone; don’t stifle autonomy. Stay open to new ways of working.
- Challenge security policies, but respect intentions. Find new ways to enforce concerns without abandoning precaution.

{{< youtube id="FsfKsqI07jM" t="80" width="600px" >}}
