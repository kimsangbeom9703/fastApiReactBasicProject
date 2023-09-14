# fastApiBasicProject

fastapi + react 기본적인 폴더 구조 

# fastapi 
```
  app:.
  ├─apis
  │  └─api.py
  ├─core
  │  └─config.py
  ├─crud
  │  └─crud.py
  ├─db
  │  ├─models
  │  │  └─model.py
  │  ├─schemas
  │  │  └─schema.py  
  │  └─connection.py
  │  └─session.py
  ├─routes
  │  └─router.py
  ├─tests
  │  └─test.py  
  └─main.py
  
  api     :   mvc패턴의 컨트롤러 (db의 데이터를 받아 가공한다)
  core    :   환경설정 정보 제공 .env파일 
  curd    :   orm 형식의 db쿼리문 저장 폴더
  db      :   db 연결 , 모델 정의 , 스키마 정의
  routes  :   url 로 api 나눈다.
  tests   :   test파일
  main.py :   fastapi 실행 및 메인
  ```
  from , import 부분을 잘 확인하자.
