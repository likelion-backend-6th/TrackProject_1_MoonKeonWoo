# 도서 대출 웹 서비스
## 진행상황
1. 메인페이지 
    - http://127.0.0.1:8000/
2. 도서 상세 페이지
    - http://127.0.0.1:8000/books/1/
3. 회원 가입
    - http://127.0.0.1:8000/accounts/signup/
4. 로그인
    - http://127.0.0.1:8000/accounts/login/
5. 로그아웃
   - 로그인하면 로그인/회원가입이 로그아웃으로 표시
6. 내 대출 목록
    - http://127.0.0.1:8000/books/my_rentals/
7. 도서 대출
   - 도서 상세 페이지에서 대출 버튼을 클릭하면 내 대출 목록 페이지로 이동
## 20230905
1. github repo 생성
2. git clone 
3. dev branch 생성
4. venv 가상환경 생성
5. .gitignore 파일 생성
6. requirements.txt 생성
7. startproject 
   - python manage.py runserver 동작 확인
8. startapp accounts
9. 회원가입 구현
   - config.urls 'accounts/'
   - accounts.urls 'signup/'
   - SignUpView 
   - accounts.forms
10. postgreSQL
    - psycopg2 설치
    - migrate
11. CustomUser 모델 생성
12. CustomUser, UserAdmin 관리자 사이트 등록
    - createsuperuser 오류 발생
      - "date_of_birth" 칼럼(해당 릴레이션 "accounts_customuser")의 null 값이 not null 제약조건을 위반했습니다.
13. CustomUserCreationForm 생성
    - shell에서 import한 후에 출력해서 확인
14. SignUpView
## 20230908
1. login/logout
2. book 앱 생성
3. homepage 제작
