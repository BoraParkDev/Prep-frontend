## Prep Project

[데모 영상](https://drive.google.com/file/d/1WS_sMDCiSXfQGuiVfNW02JQXhA6RRGI5/view?usp=sharing) | 
[웹 사이트](http://18.221.140.44:8000)

### [팀명] : Prep(프렙)

- 프립 (https://www.frip.co.kr) 클론 프로젝트
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 위 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 프로젝트 선정이유

- 액티비티를 소개, 공유, 판매하는 플랫폼 웹 
- 판매부터 추천기능, 원하는 액티비티 저장 및 참여 후 후기를 남길 수 있는 등 다양한 서비스를 제공합니다.<br/>
  따라서 다양한 서비스를 제공하는 만큼 여러 기능들을 홈페이지 내에서 적용해보기에 적합하다고 생각하였습니다.

### 개발 인원 및 기간

- 개발기간 : 2021/11/15 ~ 2021/11/26
- 개발 인원 : 프론트엔드 3명, 백엔드 2명
- 팀원 : 권민석, 박보라, 양성호, 이용건, 장연정
- [프론트 github 링크](https://github.com/wecode-bootcamp-korea/26-2nd-Prep-frontend)
- [백엔드 github 링크](https://github.com/wecode-bootcamp-korea/26-2nd-Prep-backend)

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : JavaScript, React.js, React Hooks, styled-components, React-router-dom v6, AWS(EC2)
> - Back-End : Django, Python, MySQL, jwt, bcrypt, AWS(EC2, RDS)
> - Common : Git, Github, Slack, Trello, dbdiagram, postman

### 구현 기능

> Sign Up/In

- 카카오 API 연동을 통한 소셜 로그인 구현

> List Page

  - children 속성을 사용한 모달창 구현
  - 동적 라우팅(query parameter)
  - limit&offset 값 설정을 통한 pagination 구현
  - 카테고리 필터링 기능
  - 가격순, 별점순 등 세부 필터링 기능
  - input의 type:range를 활용하여 가격 범위 조정
  - checkbox 스타일 지정 및 state, props로 상태관리
  - DB 연동된 백엔드 API 주소 데이터 시각화

<br>

## Reference

- 이 프로젝트는 [프립](https://www.frip.co.kr) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
