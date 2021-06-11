# 프로젝트 설명 📌

<br/>

![Designers-logo2](https://user-images.githubusercontent.com/60308568/121653668-e85b2980-cad7-11eb-8529-0064ead2bd6c.png)

  저가 자주 이용하는 미용실의 사장님께서는 번거롭게 모두 전화를 이용하여 고객 예약 및 문의를 처리하고 있었습니다. 저는 이에 의문이 들어 네이버 예약이나 카카오헤어를 사용하면 되지 않느냐는 의문이 들어 그 분께 여쭤보았습니다.
 
  사장님께서는 네이버나 카카오헤어는 블랙리스트 관리가 안되고, 고객 포인트나 메모 등 여러 기능들이 빠져있어 단골 위주로 장사하는 그 가게에서는 사용하지 못한다고 답변하셨습니다.
 
  이 외에도 프리랜서 미용사의 경우 미용실과 계약을 하고 그 미용실의 이름으로 고객 유치를 하기 때문에 해당 미용실을 그만 둘 시에 고객 관리가 매우 어려워진다고 하셨습니다.
 
  이러한 고충을 가지고 있는 프리랜서 미용사, 혹은 단골을 주고객으로 가진 미용사분들을 위한 고객 관리 웹 애플리케이션입니다.

<br/>
<br/>

# 기술 스택 🎛

#### Front-end
+ React, Redux
+ Axios, Tailwind css

#### Back-end
+ Spring, Lombok, JUnit4
+ JPA, MySQL, H2

#### Etc
+ Docker

<br/>
<br/>

# 실행 방법 💻

<br/>

준비물 : Docker

1. 터미널에서 해당 프로젝트 폴더의 mini-project로 진입합니다.
2. docker를 이용해 해당 Container를 build합니다. 명령어는 다음과 같습니다.
  ```
  docker-compose up --build
  ```
3. 해당 컨테이너가 정상적으로 실행되었다면, localhost:3031 포트를 이용해 접속 가능합니다.

<br/>
<br/>

# 기능 Overview 📃

<br/>

- 로그인, 회원가입, 마이페이지
- 유저 세션 유지
- 예약 관련 CRUD
- 디자이너의 스케줄 확인, 고객 관리 CRUD
- 좋아요 관련 CRUD
