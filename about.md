---
layout: single
title: "About"
author: Dayun Choi                    # authors.yml 파일에 존재하는 username 값
date: "2022-06-20 17:40"              # 최초 포스팅 날짜. 별도 정렬 순서가 없으면 이 값으로 정렬됨. 파일명에 기록되어있다면 생략 가능.
last_modified_at: "2025-09-24 16:20"  # 마지막 수정 날짜.
comments: false
---

최다윤 (Dayun Choi)  
E-mail : cdy3773@kaist.ac.kr | cdy1109@gmail.com


## Research interests
- Deep Learning-based Target Sound Extraction
- Deep Learning on Multimodal Systems
- Audio/Image Signal Processing & Computer Vision


You can scroll through my CV below and click links inside:

<div id="cv-container"></div>

<script>
  const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
  const container = document.getElementById("cv-container");

  if (isMobile) {
    container.innerHTML = `
      <iframe src="/assets/pdfjs/web/viewer.html?file=../pdf/CV_Dayun_Choi.pdf"
              width="100%" height="800px" style="border:1px solid #ccc;"></iframe>`;
  } else {
    container.innerHTML = `
      <iframe src="/assets/pdf/CV_Dayun_Choi.pdf"
              width="100%" height="800px" style="border:1px solid #ccc;" allowfullscreen></iframe>`;
  }
</script>