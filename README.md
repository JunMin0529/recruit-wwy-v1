<img src="https://capsule-render.vercel.app/api?type=waving&color=DCDCDC&height=300&section=header&text=We%20Want%20You.&fontSize=90&fontColor=0099FF" />

# 시연 영상
![video](https://github.com/user-attachments/assets/39a48db4-4f4a-43e1-b091-0eba6d330dee)

# 목차
1. [💡 프로젝트 소개](#프로젝트-소개)
2. [📝 프로젝트 후기](#프로젝트-후기)
3. [🗂️ ERD](#erd)
4. [👥 팀원](#팀원)
5. [🧠 핵심 기능](#핵심-기능)
6. [🖼️ 화면 구성](#화면-구성)
7. [🔧 보완할 점](#보완할-점)
8. [📏 코드 컨벤션](#코드-컨벤션)

# 프로젝트 소개

### 웹 설명

WWY는 구직자와 기업을 이어주는 채용공고 웹 사이트 입니다.
<br>
원티드와 프로그래머스의 채용공고 페이지를 벤치마크하여 제작하였습니다.

### 프로젝트 기간

    2025. 04. 11 ~ 2025. 05. 02


# 프로젝트 후기
- 설계, 개발, 테스트 등 전반적인 과정을 경험하며 개발자로서 한 단계 성장할 수 있었습니다.
- 팀원들과의 협업 과정에서 효과적인 소통과 역할 분담이 프로젝트 완성도에 얼마나 중요한지 몸소 느낄 수 있었습니다.
- 일정 관리에 대한 경험이 부족해 계획한 기능을 모두 구현하지 못한 점이 아쉬웠고, 이를 계기로 Notion을 활용한 주간 단위 일정 관리와 기능 우선순위 시각화를 시작하게 되었습니다. [일정관리 예시](https://getinthere.notion.site/1858a08b6c0d81fca4bee9d709a4d4cf?source=copy_link)
- JavaScript로 즐겨찾기 기능을 구현하면서, 클릭 시 즉시 사용자에게 반응이 나타나도록 하는 방법에 대해 잘 알지 못했습니다. 그러다 AJAX라는 구체적인 기술을 처음 접했고, 비동기 통신의 개념도 함께 배우게 되었습니다. 이를 프로젝트에 직접 적용하여 기능 구현에 성공했습니다. 이 경험을 통해 새로운 기술을 빠르게 습득하고 실무에 적용하는 자신감을 얻었으며, 앞으로도 현업에서 요구하는 다양한 기술을 적극적으로 배우고 활용해 프로젝트 완성도를 높이고자 합니다.
- 채용 웹사이트를 만들면서 생각보다 비동기 처리가 필요한 부분이 많다는 것을 느꼈습니다. 푸시 알림, 실시간 알림, 채용 정보 수정 등 사용자와 빠르게 상호작용해야 하는 기능이 많았기 때문입니다. 이를 계기로 비동기 처리에 강점을 가진 Node.js를 알게 되었고, 이후에는 Node.js를 공부하여 이러한 기능들을 더욱 유연하고 효율적으로 구현해보고 싶다는 생각을 하게 되었습니다.

  
### 사용 기술

<div>
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Java.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Bootstrap.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/JavaScript.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/HTMLCSS.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Ajax.png?raw=true" width="80">
</div>

### 협업 도구

<div>
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Github.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Notion.png?raw=true" width="80">
</div>

<br>

# ERD
<img src="README/wwy-v1-ERD.png">

# 팀원

|                                                          문정준                                                           |                                                           편준민                                                            |                                                       서회정                                                        |                                                        손영민                                                        |
|:----------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/human-mjj/recruit-wwy/blob/master/README/240125_ynn1.png?raw=true" alt="문정준" width="150"> |  <img src="https://github.com/JunMin0529/recruit-wwy-v1/blob/master/README/unnamed.png?raw=true" alt="편준민" width="150"> | <img src="https://github.com/human-mjj/recruit-wwy/blob/master/README/image.png?raw=true" alt="서회정" width="150"> | <img src="https://github.com/human-mjj/recruit-wwy/blob/master/README/Screenshot_38.png?raw=true" alt="손영민" width="150"> |
|                                                           팀장                                                           |                                                            팀원                                                            |                                                        팀원                                                        |                                                        팀원                                                         |
|                                           [GitHub](https://github.com/Sxias)                                           |                                           [GitHub](https://github.com/JunMin0529)                                           |                                      [GitHub](https://github.com/clubnerdy)                                      |                                      [GitHub](https://github.com/son7571)                                      |

<br>



<br>

# 핵심 기능

## 유저 관련 기능

- 로그인
- 회원가입
- 회원수정

## 채용 관련 기능

### 구직자

- 이력서 관리
- 이력서 지원
- 채용 공고 즐겨찾기
- 채용 공고 추천받기

### 기업

- 채용 공고 관리
- 지원 현황 관리
- 구직자에게 채용 공고 추천하기
- 이력서 즐겨찾기

### 공통

- 이력서 또는 채용 공고 매칭

# 화면 구성

### 메인화면

<img src="README/project/main.png">

### 회원가입

<img src="README/project/singup.png">

### 로그인

<img src="README/project/login.png">

### 구직자 마이페이지

<img src="README/project/usermypage.png">

### 기업 마이페이지

<img src="README/project/commypage.png">

### 추천

<img src="README/project/recommend.png">



# 보완할 점
- 오류 발생 시 클라이언트 측에 상세한 피드백을 전달하지 못한 점
- 채용 공고 목록 화면에 즐겨찾기 기능이 누락된 점
- SNS 회원가입 기능이 구현되지 않은 점
- 이메일 중복 체크 및 입력값 유효성 검사 등 보안 관련 처리가 미흡했던 점

# 코드 컨벤션

https://getinthere.notion.site/Code-Convention-1d58a08b6c0d805db749d4db6cfc9637?pvs=4
