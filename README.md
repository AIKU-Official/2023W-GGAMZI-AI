<br />
<div align="center">
  <a href="https://github.com/AIKU-Official/aiku-23-2-project-ggamzi">
    <img src="project_logo/logo.png" alt="Logo" width="300" height="300">
  </a>

  <h3 align="center">GGAMZI-AI</h3>

  <p align="center">
    Generate texts with your own handwriting style!
    <!--<br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>-->
  </p>
</div>

## Project Info
* 고려대학교 딥러닝 학회 AIKU 2023년 2학기 프로젝트
* 개발 기간 : 2023.09 ~ 2023.12

## About The Project
* 깜지 AI는 개개인의 손 글씨 스타일을 모사하여 원하는 내용을 생성하는 FFG(Few-shot handwriting Font Generation) task 수행 모델입니다.

<details>
  <summary>📌 Few-shot Font Generation Task </summary>
  <ol>
    추가적인 fine tuning 없이, 적은 개수의 글자 모양(glyph)만으로 새로운 폰트를 생성해내는 task로, 글자 모양(content)의 global한 특징과 reference style의 local한 특징을 유지하는 것이 핵심입니다.
  </ol>
</details>
<br />

* 깜지를 대신 작성해주는 생성 모델을 만들어보자는 동기에서 시작하였습니다.
* 한글이 아닌, 한자나 중국어 데이터에 특화되어 있는 선행 모델들의 한계점을 해결하고자 했습니다.

## Modeling
* MX-Font (ICCV 2021)을 차용하였습니다. <a href="https://github.com/clovaai/mxfont">Link</a>
* Training
  * Dataset
    - 무료 폰트 사이트에서 수집한 약 312개의 폰트 파일(.ttf)
    - 공개되어 있는 필기체 데이터셋 및 직접 수집한 손글씨 이미지 데이터 (.png, .jpeg)
  


