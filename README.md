# 🥄 FoCo
### "현지인이 추천하는 맛집 사이트"
**FoCo**는 **Food + Recommendation**의 합성어로 여행객을 대상으로 현지인들만 아는 맛집을 소개해주는 사이트입니다.   
유저 프로필에 등록한 국가에만 게시글을 등록할 수 있고 북마크를 통해 게시글을 저장하고, 저장된 게시글을 검색할 때 mood(식당 분위기)와 foodtype(음식 종류)등으로 검색할 수 있습니다.
마음에 드는 글에는 좋아요를 누를 수 있고, 각 국가별로 좋아요 순으로 나열된 리뷰를 보며 검증된 정보를 얻을 수 있습니다.
<br/>

## 🥨프로젝트 소개
#### 📁 [API 문서](https://documenter.getpostman.com/view/16841571/2s8Z6u5usD)
#### 🎬 [시연영상 보러가기](https://drive.google.com/file/d/1mi7RB3sVGbb3CG__09OEOTuenbuUF3ju/view?usp=sharing)
#### 📌 세부항목보기
<details><summary>회원가입, 로그인, 로그아웃</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213431633-48c932c5-f428-460e-b277-6a5079ea48ec.gif)
- input 작성 시 실시간 유효성 검사를 진행하며 UX 개선
</details>

<details><summary>프로필 변경</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424786-d4abbd4d-268b-41b4-8d0f-bb2ce0dd93e6.gif)
- 이미지 미리보기를 통해 변경 전 확인 가능
- input 작성 시 실시간 유효성 검사를 진행하며 UX 개선
</details>

<details><summary>비밀번호 변경</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424776-1e340e6c-a080-4008-b9b5-11d6b249f3a1.gif)
- 현재 비밀번호를 확인한 후 비밀번호 변경 진행
- input 작성 시 실시간 유효성 검사를 진행하며 UX 개선
</details>

<details><summary>비밀번호 찾기</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424782-e761ff13-7003-4c8e-9fe0-adba03156079.gif)
- nodemailer를 이용해 기능 구현
- input 작성 시 실시간 유효성 검사를 진행하며 UX 개선
</details>

<details><summary>회원탈퇴</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424792-24d5b894-b02c-4df0-89be-158a173c57db.gif)
- 비밀번호 검증 후 confirm으로 이중확인 후 퇄퇴 진행
</details>

<details><summary>메인페이지, 나라 조회</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424759-88a4f4f8-439d-4aed-9a77-84738898ff03.gif)
- 세계지도를 클릭하거나 검색을 통해 원하는 나라의 지정된 위경도로 이동이 가능하며, 해당 나라에 작성된 게시물을 좋아요 순으로 확인 가능
- 게시글 선택 시, 해당 위치의 도시 숟가락 색이 변경
- 게시물 오른쪽 상단 클릭 시, 모달창으로 세부 내용 확인이 가능
- 유저가 원하는 게시글에 좋아요를 누를 수 있으며, 좋아요 갯수를 통해 검증된 정보 확인 가능
</details>

<details><summary>나라별 세부조회</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424765-c5a5aa0d-dcdd-4729-9c5a-4246ebfb45b2.gif)
- 좋아요 순으로 정렬된 창의 오른쪽 상단 버튼을 클릭하면 해당 국가의 게시글만 있는 페이지로 이동
</details>

<details><summary>나라별 필터 기능</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424768-3bbc72d7-a4b1-4db1-b5eb-cf4232c825c6.gif)
- 필터링 기능을 통해 국가별로 유저들이 작성한 태그들을 모아 저장된 도시, 식당의 분위기, 음식타입으로 여러개의 태그를 넣어 검색 가능
</details>

<details><summary>북마크, 북마크 필터</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424770-0e2d5fb4-cbc1-4a82-9717-de4cd843c2c4.gif)
- 원하는 게시글을 북마크 버튼을 통해 저장 가능
- 필터링 기능을 통해 저장된 게시글 중 원하는 게시글만 검색 가능
</details>

<details><summary>게시글 작성</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424796-8bf25871-c493-4820-8178-da51f830ae5b.gif)
- 주소 작성 시 AutoComplete기능으로 관련 주소 목록이 나오면서 보다 편리한 UX 경험을 완성 
- `browser-image-compression` 으로 이미지 리사이징을 통해 로딩 속도 개선

![image](https://user-images.githubusercontent.com/103574215/213435290-f6864f76-52f6-4ff3-b242-78d379d6aa30.png)
</details>

<details><summary>현지인 검증</summary>
    
![image](https://user-images.githubusercontent.com/103574215/213424799-59b992ad-c8e8-482e-b7d7-c5c89878cf19.gif)
- ‘현지인 맛집 추천 사이트’ 라는 방향성을 위해 프로필에 등록된 나라가 아닌 다른 나라 가게의 게시글은 업로드 불가
</details>



## 🍕 개발기간
2022년 12월 11일 ~ 2022년 12월 29일 (약 3주)

## 🍔 멤버구성 및 역할

| Name | Position | Role | 
| ------ | ------ | ----- |
| 홍희선 | Frontend | 팀장, main map, ranking, contents, multiSelectbox, dropdown 등 담당, 모든 페이지 총괄 및 해결 |
| 강민희 | Frontend | review, post modal, autocomplete 담당 |
| 김혜지 | Frontend | Bookmark, modal, route 담당 |
| *이화정 | Frontend | [Login](https://github.com/kailey224/FoCo/tree/main/client/src/component/Login), [Resister](https://github.com/kailey224/FoCo/tree/main/client/src/component/Register), [Account](https://github.com/kailey224/FoCo/tree/main/client/src/component/Account), [Forgot Password](https://github.com/kailey224/FoCo/tree/main/client/src/component/ForgotPassword), [Header](https://github.com/kailey224/FoCo/tree/main/client/src/component/Header) 등 유저 관련 기능 담당|
| 한승주 | Backend | Only One, 단 하나의 백엔드 |

## 🍟 개발 환경
Front
<img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
<img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
<img alt="Axios" src="https://img.shields.io/badge/-Axios-5A29E4?style=flat-square&logo=Axios&logoColor=white" />
<img alt="styled components" src="https://img.shields.io/badge/-styled components-DB7093?style=flat-square&logo=styled-components&logoColor=white" />

Back
<img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
<img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white" />
<img alt="Nodejs" src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=Node.js&logoColor=white" />
<img alt="Express" src="https://img.shields.io/badge/-Express-000000?style=flat-square&logo=Express&logoColor=white" />

Deploy / Tool
<img alt="NGINX" src="https://img.shields.io/badge/-NGINX-009639?style=flat-square&logo=NGINX&logoColor=white" />
<img alt="PM2" src="https://img.shields.io/badge/-PM2-2B037A?style=flat-square&logo=PM2&logoColor=white" />
<img alt="Amazon AWS" src="https://img.shields.io/badge/-Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white" />
<img alt="Yarn" src="https://img.shields.io/badge/-Yarn-2C8EBB?style=flat-square&logo=Yarn&logoColor=white" />
<img alt="ESLint" src="https://img.shields.io/badge/-ESLint-4B32C3?style=flat-square&logo=ESLint&logoColor=white" />
<img alt="Prettier" src="https://img.shields.io/badge/-Prettier-F7B93E?style=flat-square&logo=Prettier&logoColor=white" />

Communication
<img alt="GitLab" src="https://img.shields.io/badge/-GitLab-FC6D26?style=flat-square&logo=GitLab&logoColor=white" />
<img alt="Jira" src="https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=Jira&logoColor=white" />
<img alt="Postman" src="https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white" />
<img alt="Notion" src="https://img.shields.io/badge/-Notion-000000?style=flat-square&logo=Notion&logoColor=white" />
<img alt="Figma" src="https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white" />

## 🍖 개발 규칙
### 커밋컨벤션
- `feat`: 기능 추가
- `fix`: 버그 고친 경우
- `design`: css 등 사용자 UI 디자인 변경
- `docs`: 문서를 수정한 경우
- `style`: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- `rename`: 파일 혹은 폴더명 수정하거나 옮기는 경우
- `remove`: 파일을 삭제하는 작업만 수행한 경우
- `refactor`: 코드 리펙토링
### 브랜치
`master`
`dev`
`feature/FE/기능명`
`featrue/BE/기능명`
### 코딩컨벤션
- 변수명 `camelCase`
- components 이름은 `Pascalcase`
