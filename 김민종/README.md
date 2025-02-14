MinJong Kim  
===



# 3일차
1. DB 연동
 - mysql 연동하여 쿼리 날려서 확인해 보기

2. 이미지 업로드 (기존 코드 수정)
 - 이미지를 올리고 하단에 있는 옵션을 선택하여 이미지 확인 버튼을 누르면 원본 이미지와 처리된 이미지 로드  
 - 사이즈 변경 옵션은 체크박스가 활성화 될 때만 텍스트박스가 뜨도록 수정
  
  

# 개인 프로젝트

## 4일차 (2023-01-16)
1. 개인프로젝트 [상세](https://organized-jester-5db.notion.site/flask-9ec11aad59cf45b2b350d212a4c7c82c)
    - 회원가입 구현
    - 로그인, 로그아웃 구현 
    - 개인별 하고싶은 기능 구현 해보기 (경구약제 모델 올려서 해보기, 이미지 크롭, 게시판)
    - 버그 수정 및 보완하기 

## 5일차 (2023-01-17)
1. 개인프로젝트 [상세](https://organized-jester-5db.notion.site/flask-9ec11aad59cf45b2b350d212a4c7c82c)
    - 회원가입 구현 
    - 로그인, 로그아웃 구현 
    - 개인별 하고싶은 기능 구현 해보기   
        - 이전에 했던 경구약제 모델 올려서 실행해보기(서비스)
    - 버그 수정 및 보완하기   
    
## 6일차 (2023-01-18)
1. 개인프로젝트 [상세](https://organized-jester-5db.notion.site/flask-9ec11aad59cf45b2b350d212a4c7c82c)
    - 개인별 하고싶은 기능 구현 해보기   
        - 이전에 했던 경구약제 모델 올려서 실행해보기(서비스)  
        - 게시판 만들기 (CRUD)
        - 로그인 form 전달 방식에서 ajax방식으로 전환하기  
        
    - 버그 수정 및 보완하기 **(keep ~ ing)**
      
## 7일차 (2023-01-19)
1. 개인프로젝트 [상세](https://organized-jester-5db.notion.site/flask-9ec11aad59cf45b2b350d212a4c7c82c)  
    - 개인별 하고싶은 기능 구현 해보기      
        - 게시판 pagination (flask_pagination 라이브러리 사용)  
                
    - 버그 수정 및 보완하기 **(keep ~ ing)**
        - POST 방식으로 데이터 주고 받는 URL들에 GET 방식(url직접입력)으로 요청을 보내면 Method Not Allowed가 발생하는데 이를 막기 위해 GET 방식으로 요청하면 이전 페이지로 강제 리다이렉트   
        - User, Database class 를 조금 더 객체지향적으로 설계  
        - html 파일 구조를 메인 / 게시판 / navbar로 나누어 보기 쉽게 하기  
        - html의 중복되는 영역을 하나로 만들고 jinja2 template의 include 속성을 사용하여 삽입하기(중복 코드 제거)  

## 8일차(개인 프젝 1 최종) (2023-01-20)
1. 개인프로젝트 [상세](https://organized-jester-5db.notion.site/flask-9ec11aad59cf45b2b350d212a4c7c82c)  

    - 버그 수정 및 보완하기 **(keep ~ ing)**
        - 404 Not Found 처리하기 (custom 404 error page 생성)
        - navbar가 스크롤해도 따라오지 않도록 상단 영역에 고정시키기
    
    - 개인 프로젝트 보고서 작성하기



## 개인 프로젝트 2 (streamlit 1일차) 2023-01-25
1. 한 것  
    - 경구약제 이미지 올려서 분석해보기
    - 배포해보기
    - [배포url](https://kim-min-jong-daily-pj-project-streamlitapp-8tm39q.streamlit.app/)    
    - 배포 시 주의 점 
        - opencv를 사용할 떄는 패키지를 opencv-python 이 아닌 opencv-python-headless를 적용해야 배포 시 문제가 생기지 않음. opencv-python을 적용하면 ImportError발생

2. 할 것
    - 약 정보 크롤링해서 보여주기
