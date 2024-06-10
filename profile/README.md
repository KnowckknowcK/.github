#  똑똑(Knowck-Knowck)
### 현대인을 위한 문해력 향상 서비스
![Slide 16_9 - 1 (2)](https://github.com/KnowckknowcK/.github/assets/104684033/a9d1f427-573d-4abb-8249-6170785cf828)


## 목차
- :smile:[프로젝트 소개](#프로젝트소개)
- :sunglasses:[팀원 소개](#팀원소개)
- :bell:[배포 링크](#배포링크)
- :point_right:[데모 영상](#데모영상)
- :computer:[레포지토리 링크](#레포지토리링크)
- :clipboard:[노션 링크](#노션링크)
- :page_facing_up:[API 명세](#API명세)
- :bookmark_tabs:[개발 문서](#개발문서)


<br/><br/>

## 프로젝트소개
자극적인 디지털 매체의 노출로 인해 문해력이 저하된 현대인들에 도움을 주기 위한 애플리케이션입니다.<br/>
다양한 주제의 글을 **읽고**, 글에 대해 **생각하고**, 글을 **요약**하는 일련의 과정을 통해 **문해력을 증진**시키고,<br/>
또한 글에 대한 자신의 생각과 여러 다른 사람의 생각을 나눔으로써 디지털 소통 능력을 함양하고자 하는데 목표가 있습니다.

<br>

주요 **기능적** 목표
- 매일 업데이트되는 기사 데이터를 수집하여 사용자에게 제공한다.
- 사용자가 글을 읽고 글에 대한 요약을 작성한다.
- 사용자가 작성한 요약을 open AI 서비스를 이용해 평가한다.
- 사용자들간 서로의 생각을 나누기 위한 대화를 가능하게 한다.
- 동기부여를 위해 결과와 지속성에 대한 여러 통계치를 제공한다.

<br>

주요 **기술적** 목표
- React를 이용하여 프론트엔드를 구현하고, PWA(프로그레시브 웹 앱)을 통해 모바일 환경에서 이용가능하게 한다.
- Spring boot를 이용하여 백엔드를 구현하고 애플리케이션의 안정성을 위해 주요 기능들에 대한 테스트 코드를 작성한다. 또한 OCP 원칙을 지키는 코드를 작성하여 다른사람이 이해하기 쉽도록 하고, 향후 유지보수 비용을 최소화한다.
- Google Oauth 로그인을 이용한다.
- 기사 데이터 수집을 위해 크롤러를 만들어 자동화하고, 이를 관리하기 위한 모니터링 시스템을 구축한다.
- 여러 사람의 동시 개발을 편리하게 하기 위해 CI/CD 파이프라인을 구축하여 테스트과정과 배포과정을 자동화한다.


<br/>

## 팀원소개
| 강현수 | 권수현 | 김민주 | 박세연 | 주보경 |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| [<img src="https://github.com/Richter3766.png" width="100px">](https://github.com/Richter3766) | [<img src="https://github.com/kwonssshyeon.png" width="100px">](https://github.com/kwonssshyeon) | [<img src="https://github.com/minju26.png" width="100px">](https://github.com/minju26) | [<img src="https://github.com/adorableco.png" width="100px">](https://github.com/adorableco) | [<img src="https://github.com/jupyter1234.png" width="100px">](https://github.com/jupyter1234) | 
| 프론트엔드•백엔드 | 프론트엔드•백엔드 | 프론트엔드•백엔드 | 프론트엔드•백엔드 | 프론트엔드•백엔드

<br/>

## 배포링크
https://www.knowckknowck.com

<br/>

## 데모영상
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/watch?v=Lyn3a4ZAVWc)

<br/>


## 레포지토리링크
파트별 자세한 내용은 각 레포지토리에 작성해두었습니다.(뱃지를 클릭하여 이동합니다.) <br> <br> 
**프론트엔드** : [![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://github.com/KnowckknowcK/FE) <br>
**백엔드**     : [![Spring](https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)](https://github.com/KnowckknowcK/BE) <br>
**크롤링서버** : [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://github.com/KnowckknowcK/Crawling_server)

<br/>

## 노션링크
[<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">](https://amethyst-slice-a85.notion.site/2-6-8f5096b15ce44b119c6a277bf4aace85?pvs=4)

<br>

## API명세

[<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black">](https://api.knowckknowck.com/api-docs)

<br>

## 개발문서

### 요구사항 분석
[![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://docs.google.com/spreadsheets/d/1SjBQ8adlV7ZN8iKeuNuK-pwtOkQoSDBIt8UmwQ9o7Xo)

### 회의록
[<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">](https://amethyst-slice-a85.notion.site/2ec4fcebc0254ce9a76c7ddf0866ed67?v=cae5dc719d3a48e8a932d10d0d2123a2)

### 트러블슈팅
[<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">](https://amethyst-slice-a85.notion.site/498b5fc3d35246e8a044fcf73daf4ed1?v=cb37065c7eec4a4d907d4af4b6c698e1)

### 협업컨벤션
[<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">](https://amethyst-slice-a85.notion.site/5936e1c6d55342bebc02f727c524a276)
