---
title: "5 빌드 관리"
excerpt: ""
permalink: /docs/zh/5_/
redirect_from:
  - /theme-setup/
toc: false
toc_sticky: false
sidebar:
  nav: "zh"
---

---
도커\(Docker\) 이미지에 대한 빌드 작업을 관리한다.

어플리케이션을 다운로드, 소스 파일을 빌드, 이미지 파일을 생성하여 Harbor 레지스트리에 업로드한다.

### a\) 좌측 메인 메뉴 → 빌드 를 클릭하여 해당 페이지로 이동한다.
![]({{ site.baseurl }}/assets/KR/{{ site.version }}/5_1.png)

| **목록** | **설명** |
| :---: | :--- |
| + | 빌드 생성 버튼 |
| Filter | 검색을 통해 필요한 빌드 조회 |
| 빌드명 | 빌드의 이름 |
| 이미지명 | 저장된 도커 이미지 이름 |
| 이미지 사이즈 | 저장된 도커 이미지의 크기. MB단위로 표기 |
| 최근 액션 | 빌드의 상태를 표시 |
| 상태 | 빌드의 실행 상태를 표시 |
| 날짜 | 빌드가 실행된 날짜를 표시 |
| ![]({{ site.baseurl }}/assets/action-menu.png) | 빌드 액션 메뉴(작업 설정 편집, 히스토리, 빌드 실행, 빌드 취소, 로그 보기, 작업 삭제) |
