# GUYSHOUSE Project

## 🎇 팀명 : 남의집

> 취향 공유 커뮤니티 서비스 [남의집](https://naamezip.com/)을 모티브로 제작하게 된 남의집(GUYSHOUSE) 팀의 프론트엔드 레포지토리 입니다.
> 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
<br/><br/><br/>

## 📅 개발 기간 및 개발 인원

- 개발 기간 : 2021/12/13 ~ 2021/12/24
- 개발 인원 <br/>
  👨‍👧‍👦 **Front-End** 3명 :
  [김상훈](https://github.com/Ho0on), [김태영](https://github.com/Moro-yong), [황성재](https://github.com/seongjae0325)<br/>

  👨‍👧‍👦 **Back-End** 3명 :
  [고민혁](https://github.com/MinhyukK0), [박세용](https://github.com/se-yong), [유민혁](https://github.com/MinHyeouk)<br/>
<br/><br/><br/>

## 🎬 프로젝트 구현 영상

- 🔗 [영상 링크] : https://www.youtube.com/watch?v=F6Sg-UZp1NY
<br/><br/><br/>


## ⚙ 적용 기술

- **Front-End** : JavaScript(ES6), React.js, StyledComponent, HTML5/CSS3
- **Back-End** : Django(Pyhton 3.8), Mysql5.7, AWS(EC2, S3, RDS), Bcrypt / JWT
- **Common** : Git, Github, Slack, Trello, Postman, Notion

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://dbdiagram.io/d/61b6b6908c901501c0ecdb28)
<br/><br/><br/>

## 💻 구현 기능

### FRONTEND

### 나의 작업

> 카카오 소셜 로그인
- kakao developers 문서 참고
- Kakao SDK for JavaScript를 이용한 로그인,로그아웃, 연결 끊기 기능 
- 카카오 access_token을 fetch로 전달 및 로그인 토큰 localStorage에 저장
- .env에 환경변수 저장 및 사용

![](https://images.velog.io/images/sad_wf/post/3b39521f-b514-4884-ba5d-7b5760cf9649/kakaologin.gif)

<br><br><br>
> 프로그램 예약 페이지
- textarea를 map()으로 반복 및 textarea Auto Height 적용
- textarea 내부 텍스트 Count
- state의 값에 따라 조건부 버튼 활성화
- 동적 라우팅, useParams 사용하여 데이터 가져오기

![](https://images.velog.io/images/sad_wf/post/84cd1bbb-bba3-4caf-97d5-3d88cf6024c1/%E1%84%8B%E1%85%A6%E1%84%8B%E1%85%A3%E1%86%A8%E1%84%91%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%8C%E1%85%B5.gif)

<br><br><br>
> 마이페이지
- state 값을 변경하여 3가지 요소 중 한 가지만 active되도록 onClick 이벤트 작성

![](https://images.velog.io/images/sad_wf/post/65f4915f-a8ce-4837-aace-c7fc57a57a11/ezgif.com-gif-maker.gif)

#### 김상훈

> Nav
> 
> 호스트 등록 페이지
> 
> 호스트 관리 페이지
> 
> 호스트 프로그램 생성 페이지

#### 황성재

> 메인 리스트페이지
> 
> 프로그램 상세페이지

## ❗ Reference

- 이 프로젝트는 [남의집](https://naamezip.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 모두는 copyright free 사이트들의 이미지들을 취합한 이미지들로 제작되었습니다.
