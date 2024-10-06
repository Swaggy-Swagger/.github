
# Swaggy Swagger
<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/1650bb7d-cdf0-485c-8cc8-9617d8ea7472" width="500" alt="Swaggy-Swagger-Logo" />
</p>
<br/>
<p align="center">
  <a href="https://jitpack.io/#Swaggy-Swagger/swagger-custom-java" target="_blank"><img src="https://jitpack.io/v/Swaggy-Swagger/swagger-custom-java.svg" alt="Jitpack Release"/></a>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/LICENSE" target="_blank"><img src="https://img.shields.io/github/license/Swaggy-Swagger/swagger-custom-java?logo=github&color=blue" alt="License"/></a>
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java?ref=badge_shield" target="_blank"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java.svg?type=shield&issueType=license" alt="Fossa License Scan" /></a>
<a href="https://app.fossa.com/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java?ref=badge_shield&issueType=security" target="_blank"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java.svg?type=shield&issueType=security" alt="FOSSA Status"/></a>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java"><img src="https://img.shields.io/github/v/release/Swaggy-Swagger/swagger-custom-java?logo=github" alt="github release"/></a>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java"><img src="https://img.shields.io/github/release-date/Swaggy-Swagger/swagger-custom-java?color=blue&logo=github" alt="github last release date" /></a>
<br>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java/graphs/contributors" target="_blank"><img src="https://img.shields.io/github/contributors-anon/Swaggy-Swagger/swagger-custom-java?logo=github&color=blue" alt="github contributors" /></a>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java"><img src="https://img.shields.io/github/stars/Swaggy-Swagger/swagger-custom-java?logo=github" alt="github stars" /></a>
  <a href="https://github.com/Swaggy-Swagger/swagger-custom-java"><img src="https://img.shields.io/github/discussions/Swaggy-Swagger/swagger-custom-java?logo=github&color=blue" alt="github discussions" /></a>
</p>
<br/>


<br/>

## Overview
**Swaggy-Swagger** is a library designed to enhance the functionality 
and user experience of the popular API documentation tool, Swagger.  

This project addresses common pain points faced by developers, 
improving the Swagger UI and adding new features to make API documentation more intuitive and effective.</br>


#### Demo Video
<div>
<a href="https://www.youtube.com/watch?v=oD8ShZGQrqo"><img src="https://img.shields.io/badge/YOUTUBE-FF0000?style=for-the-badge&logo=YouTube&logoColor=white&link=https://www.youtube.com/watch?v=oD8ShZGQrqo"/></a>
</div>


#### [ReadMe in Korean 한국어 버전 보기](https://github.com/Swaggy-Swagger/.github/tree/main/profile#%EA%B0%9C%EC%9A%94)


## Features
### Enhanced UI/UX
#### Sidebar Navigation
- A new sidebar allows for quick navigation to specific API sections, improving accessibility and ease of use.
<p>
    <img src="https://github.com/user-attachments/assets/b09bf788-df68-4975-82cf-dc623d8e4ddc" alt="Image 1" width="65%">
    <img src="https://github.com/user-attachments/assets/c39f7cda-b13f-49d4-b277-4fa7f175557b" alt="Image 2" width="30%" align="top">
</p>

#### Horizontal Layout
- The default vertical layout has been changed to a horizontal format, enabling easier viewing of parameters and responses, and reducing the need for scrolling.
  <p>
  <img width="50%" alt="스크린샷 2024-08-28 오후 11 24 29" src="https://github.com/user-attachments/assets/c1181e35-da40-4124-b56c-d1bd9ea35c76">
  <img width="48%" src = "https://github.com/user-attachments/assets/8bf549d0-3f8f-4f99-8669-8b36cbef356c" align="top">
  </p>

### Change Tracking and Visualization
- Server-Side Change Management: Every server restart triggers the storage of Swagger snapshots in JSON format. These snapshots are versioned, and changes are logged.  
  

- Client-Side Change Indicators: APIs with recent changes are marked with a red dot. Hovering over the API reveals information about the changes (e.g. endpoints, parameters, request/response schemas)
 

  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/c36539b7-0e2d-474a-b074-59e007feef8a">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/9c6e1e6f-4949-4f05-a695-10332ce32720"> 
  </p>
  <img width="100%" src = "https://github.com/user-attachments/assets/bf1daf8d-17ca-411a-a4a4-3c2b4f1139c9">

- After checking changes, the red dot disappears (it reappears upon refreshing)


  <img width="100%" src = "https://github.com/user-attachments/assets/4b158a0c-9a46-4861-92c7-134083d5e83c">
  
### API Sorting By Line Number
- User-Defined Sorting: Swaggy-Swagger allows APIs to be sorted based on the line numbers in the code. This custom sorting improves readability and reflects the developer’s intent.

### Enjoy Swaggy Swagger 😎
  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/101098d5-8b3d-4886-a4c4-8e00006053e2">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/a007719b-be2b-41e5-ba56-fa1871bcfed3"> 
  </p>
  
## How to Use
- You can find detailed information on requirements and installation in the [Repository of Spring Boot Library](https://github.com/Swaggy-Swagger/swagger-custom-java)

## Ways to contribute

We always welcome your contributions! 
* If you would like to contribute to the frontend (UI), you can see [swaggy-ui](https://github.com/Swaggy-Swagger/swaggy-ui?tab=readme-ov-file#ways-to-contribute) for more details.  


* Else, if you want to contribute to the backend (server-side), please refer to [CONTRIBUTING.md](https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/CONTRIBUTING.md). 

## Contributors

Thank you to everyone who contributed to our project.

<a href="https://github.com/Swaggy-Swagger/swagger-custom-java/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Swaggy-Swagger/swagger-custom-java" />
</a>

_<div align=right>Made with <a href="https://contrib.rocks">contrib.rocks</a></div>_


## License
**Swaggy-Swagger** is licensed under the Apache License, Version 2.0.  
See the [LICENSE](https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/LICENSE) file for more details.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java?ref=badge_large)

## Contact
<a href="mailto:clcc001@naver.com"><img src="https://img.shields.io/badge/mail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=clcc001@naver.com"/></a>

<br/>

## 개요
**Swaggy-Swagger**는 인기 있는 API 문서화 도구인 Swagger의 기능과 사용자 경험을 향상시키기 위해 설계된 라이브러리입니다.  
이 프로젝트는 개발자들이 자주 겪는 문제점을 해결하며, Swagger UI를 개선하고, 보다 직관적이고 효과적인 API 문서를 만들기 위한 새로운 기능을 추가합니다.

#### 시연 영상 
<div>
<a href="https://www.youtube.com/watch?v=oD8ShZGQrqo"><img src="https://img.shields.io/badge/YOUTUBE-FF0000?style=for-the-badge&logo=YouTube&logoColor=white&link=https://www.youtube.com/watch?v=oD8ShZGQrqo"/></a>
</div>

#### [ReadMe in English 영어 버전 보기](https://github.com/Swaggy-Swagger/.github/tree/main/profile#overview)

## 기능 소개
### 향상된 UI/UX
#### 사이드바 내비게이션
- 사이드바를 추가해 사용자가 원하는 위치로 쉽게 이동할 수 있도록 하였습니다. 사이드바의 컨트롤러 태그를 통해 손쉽게 필요한 API로 이동할 수 있습니다.


<p>
    <img src="https://github.com/user-attachments/assets/b09bf788-df68-4975-82cf-dc623d8e4ddc" alt="Image 1" width="65%">
    <img src="https://github.com/user-attachments/assets/c39f7cda-b13f-49d4-b277-4fa7f175557b" alt="Image 2" width="30%" align="top">
</p>

#### 가로 레이아웃
- 기존 세로 레이아웃을 가로로 수정해, 개발자가 파라미터와 응답을 한눈에 확인할 수 있고, 스크롤 작업을 줄이고 가독성을 높일 수 있도록 개선했습니다.


  <p>

  <img width="50%" alt="스크린샷 2024-08-28 오후 11 24 29" src="https://github.com/user-attachments/assets/c1181e35-da40-4124-b56c-d1bd9ea35c76">
  <img width="48%" src = "https://github.com/user-attachments/assets/8bf549d0-3f8f-4f99-8669-8b36cbef356c" align="top">
  </p>

### 변경 사항 시각화 기능
- 서버 측 변경 사항 관리: 서버가 재시작될 때마다 스웨거의 스냅샷을 JSON 형식으로 저장합니다. 이 스냅샷은 현재 버전과 직전 버전으로 구분되어 저장되며, 변경 내역은 별도의 로그 파일로 기록됩니다.  


- 사용자 측 변경 사항 표시: 변경 사항이 있는 API 옆에 빨간 점으로 표시됩니다. 사용자가 마우스를 올리면, 엔드포인트, 파라미터, 응답 또는 요청 스키마 중 어떤 부분이 변경되었는지 상세 정보를 확인할 수 있습니다.
  

  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/c36539b7-0e2d-474a-b074-59e007feef8a">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/9c6e1e6f-4949-4f05-a695-10332ce32720"> 
  </p>
  <img width="100%" src = "https://github.com/user-attachments/assets/bf1daf8d-17ca-411a-a4a4-3c2b4f1139c9">

- 변경 사항 확인 후 빨간 점은 사라지고, 새로고침 시 다시 나타날 수 있습니다.


  <img width="100%" src = "https://github.com/user-attachments/assets/4b158a0c-9a46-4861-92c7-134083d5e83c">

### 작성 순서대로 API 정렬 
- 기존 스웨거에서는 API가 무작위 순서로 배열되어 원하는 API를 찾는 데 어려움이 있었습니다. 또한, 별도로 정렬 기준을 설정한다고 해도, 알파벳 순서로만 정렬이 가능하여 개발자의 의도를 반영하기 어려웠습니다.  


- 사용자 맞춤 API 정렬 기능: 개발자가 작성한 코드의 줄 번호를 기준으로 API 문서의 순서를 정렬해 가독성과 사용성을 높였습니다.


### Enjoy Swaggy Swagger 😎
  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/101098d5-8b3d-4886-a4c4-8e00006053e2">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/a007719b-be2b-41e5-ba56-fa1871bcfed3"> 
  </p>


## 사용 방법
- 요구사항과 사용방법에 대한 보다 더 상세한 정보는 [Repository of Spring Boot Library](https://github.com/Swaggy-Swagger/swagger-custom-java)에서 확인해주세요. 


## 컨트리뷰트하는 방법 

모든 컨트리뷰트를 환영합니다!

* 프론트엔드(UI)에 컨트리뷰트하고 싶으시다면, 더 자세한 정보는 [swaggy-ui](https://github.com/Swaggy-Swagger/swaggy-ui?tab=readme-ov-file#ways-to-contribute)를 확인해주세요.  


* 백엔드(서버 사이드)에 컨트리뷰트하고 싶으시다면, [CONTRIBUTING.md](https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/CONTRIBUTING.md)를 참고해주세요.  


## 컨트리뷰터 

스웨기 스웨거에 기여해주신 모든 분들께 감사드립니다. 

<a href="https://github.com/Swaggy-Swagger/swagger-custom-java/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Swaggy-Swagger/swagger-custom-java" />
</a>

_<div align=right>Made with <a href="https://contrib.rocks">contrib.rocks</a></div>_


## 라이센스 
**Swaggy-Swagger** 는 Apache License 2.0 버전 라이센스 하에 있습니다.
더 자세한 정보는 [LICENSE](https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/LICENSE)에서 확인해주세요.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java?ref=badge_large)


## 연락처 
<a href="mailto:clcc001@naver.com"><img src="https://img.shields.io/badge/mail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=clcc001@naver.com"/></a>
