# Depth-estimation-with-ORB-SLAM2-
https://github.com/Taeyoung96/Depth-estimation-with-ORB-SLAM2.git 설치 방법
https://taeyoung96.github.io/slamtip/ORBwithWeb/
실행 환경 : 우분투 18.04, opencv 3.2.0, realsense 2.0 sdk 
맞닥뜨린 에러들 : 
1. open cv 버전
2. Makefile:83: recipe for target 'all' failed
   make: *** [all] Error 2 : include/ 폴더 안에 있는 System.h에 #include <unistd.h>를 추가해 줍니다.
3. https://taeyoung96.github.io/slamtip/ORBwithWeb/의 3번 후 realsense 2.0 sdk설치(https://velog.io/@mqui/ubuntu-18.04%EC%97%90-realsense-SDK%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0)를 하고 4번 하고 sh.build.sh 해주면 끝

