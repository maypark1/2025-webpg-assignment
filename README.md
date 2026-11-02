
# YURA NEKO — Artist Website

> 2025 웹 프로그래밍 팀 프로젝트 

가상 아티스트 **YURA NEKO**를 주제로 제작한 아티스트 공식 웹사이트 콘셉트 프로젝트입니다.

음악과 영상, 아티스트 굿즈, 콘서트 투어 정보를 하나의 웹사이트에서 확인할 수 있도록 구성했습니다. HTML, CSS, JavaScript를 활용하여 페이지별 UI와 인터랙티브 기능을 구현했습니다.

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## Features

### 1. HOME
- 아티스트의 콘셉트를 반영한 메인 페이지
- 이미지 중심의 비주얼 레이아웃
- CSS 애니메이션을 활용한 텍스트 흐름 효과

### 2. MUSIC & VIDEOS
- 앨범 아트워크를 활용한 음악 갤러리
- HTML5 Video 요소를 이용한 영상 재생
- Grid 레이아웃 및 Hover 인터랙션

### 3. SHOPPING
- 아티스트 관련 굿즈 목록 제공
- 티셔츠, 모자, 신발, LP 카테고리별 페이지
- 상품 이미지, 이름 및 가격 표시
- CSS Hover 효과를 활용한 상품 UI

### 4. TOURS
- 아티스트의 콘서트 투어 소개
- 투어 선택 시 배경 이미지 전환 및 Fade 효과
- 투어별 상세 설명과 포토 갤러리
- 이미지 클릭 시 확대 모달 표시
- Intersection Observer를 활용한 스크롤 애니메이션

## Project Structure

```text
2025-webpg-dongyang-/
├── index.html
├── asset/                         # 이미지, 영상 및 기타 리소스
├── css/
│   ├── navstyle.css
│   ├── mainPageStyle.css
│   ├── MandAHead.css
│   ├── shopping_nav_section_all.css
│   ├── photostyle.css
│   └── tour.css
├── html/
│   ├── mainpage.html
│   ├── music_album.html
│   ├── shopping_nav_section_all.html
│   ├── shopping_nav_section_tshirt.html
│   ├── shopping_nav_section_cap.html
│   ├── shopping_nav_section_shoes.html
│   ├── shopping_nav_section_lp.html
│   ├── photomain_final.html
│   ├── photosub_final1.html
│   ├── photosub_final2.html
│   └── photosub_final3.html
└── README.md
```

## Getting Started

별도의 프레임워크나 패키지 설치 없이 웹 브라우저에서 실행할 수 있습니다.

**1. 저장소 복제**

```bash
git clone https://github.com/maypark1/2025-webpg-dongyang-.git
```

**2. 프로젝트 폴더 이동**

```bash
cd 2025-webpg-dongyang-
```

**3. 실행**

프로젝트 루트의 `index.html` 파일을 웹 브라우저에서 실행합니다.

> 이미지와 영상이 정상적으로 표시되도록 `asset`, `css`, `html` 폴더의 상대 경로를 유지해야 합니다.

## Implementation

### Page Navigation
- 공통 Navigation Bar를 통한 페이지 이동
- iframe을 활용한 메인 콘텐츠 전환
- HTML과 CSS 파일 분리를 통한 스타일 관리

### Interactive UI
- JavaScript 이벤트 리스너를 활용한 사용자 인터랙션
- CSS Transition을 이용한 Hover 및 Fade 효과
- DOM 조작을 통한 이미지 확대 모달 구현
- Intersection Observer API를 활용한 스크롤 기반 애니메이션

## Team

| 이름 | 담당 업무 |
|------|-----------|
| 백지원 | 팀장, 프로젝트 관리, 음악 및 영상 페이지, 발표 |
| 남준우 | 쇼핑 페이지, 발표 |
| 박정훈 | 네비게이션 제작 |
| 박찬미 | 메인 페이지, 투어 페이지, 웹페이지 및 PPT 디자인 |
- 박재현: ~~메인 페이지 제작~~ **중도 하차**
- 조장현: ~~메인 페이지, 발표~~ **실종**

## Collaboration

- GitHub 브랜치를 활용한 파트별 개발
- HTML과 CSS 파일 분리
- 공통 `asset/` 디렉터리를 통한 리소스 관리
- 팀원별 기능 구현 후 통합

## Project Information

- **프로젝트명:** YURA NEKO
- **진행 연도:** 2025
- **프로젝트 유형:** 웹 프로그래밍 팀 프로젝트
- **개발 방식:** HTML / CSS / Vanilla JavaScript
- **Repository:** https://github.com/maypark1/2025-webpg-dongyang-

---

© 2025 YURA NEKO. All Rights Reserved.
