# Computer_Graphics
[2023-2]

![image](https://github.com/user-attachments/assets/5734fcfe-1464-4467-87b7-b55cc0d35264)


Window 버전으로 개발했습니다.
<br>

> setting
1. freeglut 공식 사이트에서 Windows용 freeglut MSVC Package 를 다운로드
https://www.transmissionzero.co.uk/software/freeglut-devel/

2. open GL 라이브러리 설치
   opengl 이라는 폴더를 만들고 freeglut 폴더를 opengl 폴더에 복사
   폴더 위치는 자신이 알아볼 수 있는 위치에 !

3. visual Studio 랑 OpenGL 연동하기
   1) Debug x86 설정
      
   2) opengl 내 include 경로 복사
      
      ![image](https://github.com/user-attachments/assets/b2ebb88f-71b4-409e-92a8-5c25702a532a)


   3) 포함 디렉토리에 include 경로 추가
    ![image](https://github.com/user-attachments/assets/e0e1540a-53c8-494d-9116-e943bf90ee4f)



  4) 라이브러리 lib 경로 복사
     
     ![image](https://github.com/user-attachments/assets/86673c8e-a358-4954-a0a0-1a5b979da2ec)




  5) 라이브러리 디렉토리 lib 경로 추가
     ![image](https://github.com/user-attachments/assets/b9bdf042-1c73-4a6a-b255-dc49a80bbafc)


  include, lib 를 다 추가하면 이렇게 된다.
  

  6) 현재 프로젝트 열어서 dull 추가
      opengl 폴더에 있는 bin 폴더 내 freeglut.dll를 복사 -> 현재 프로젝트 폴더 열어서 복사
     
   ![image](https://github.com/user-attachments/assets/c9c72192-6e99-4e30-999f-51311d69f8a4)




  7) 디버그 / 릴리즈 용 구분 dull
     freeglut.dll 복사해서 freeglutd.dll 생성
     ![image](https://github.com/user-attachments/assets/4a072691-ab0b-4318-bbd5-ae00975be67d)






