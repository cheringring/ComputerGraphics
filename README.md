# Computer_Graphics
[2023-2]

Window 버전으로 개발했습니다.
<br>

1. freeglut 공식 사이트에서 Windows용 freeglut MSVC Package 를 다운로드
https://www.transmissionzero.co.uk/software/freeglut-devel/

2. open GL 라이브러리 설치
   opengl 이라는 폴더를 만들고 freeglut 폴더를 opengl 폴더에 복사
   폴더 위치는 자신이 알아볼 수 있는 위치에 !

3. visual Studio 랑 OpenGL 연동하기
   1) Debug x86 설정
   2) opengl 내 include 경로 복사 
     ![image](https://github.com/user-attachments/assets/aa313786-41ef-42eb-94af-828fb6b092db)



  3) 포함 디렉토리에 include 경로 추가
    ![image](https://github.com/user-attachments/assets/50a05f4a-d7c7-4f0f-a585-509d271b8acc)


  4) 라이브러리 lib 경로 복사
     ![image](https://github.com/user-attachments/assets/3d448166-3f78-4245-aaa3-99593f73e730)



  5) 라이브러리 디렉토리 lib 경로 추가
     ![image](https://github.com/user-attachments/assets/0948fe8d-ad33-4577-b135-bc0aebc790a9)


  include, lib 를 다 추가하면 이렇게 된다.

  6) 현재 프로젝트 열어서 dull 추가
      opengl 폴더에 있는 bin 폴더 내 freeglut.dll를 복사 -> 현재 프로젝트 폴더 열어서 복사
     
 ![image](https://github.com/user-attachments/assets/3d138455-b95c-47ed-bf94-b8cdb7597f1c)




  8) 디버그 / 릴리즈 용 구분 dull
     freeglut.dll 복사해서 freeglutd.dll 생성
     ![image](https://github.com/user-attachments/assets/d913ea5a-193b-4ce6-b07e-496037a01077)



9) 속성 -> 링커 -> 입력 -> 추가 종속성
     ![image](https://github.com/user-attachments/assets/edf92438-a657-471d-952a-9eb0f4e272e6)



