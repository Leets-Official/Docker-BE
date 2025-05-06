## 주제 : 도커를 사용해 봅시다

도커는 요즘 개발에 안쓰이는 곳이 없을 정도로 많이 쓰이고 있는데요! 

이번주차는 도커를 실제로 실행시키는 겁니다.

아마 4주차 과제로 모두 Spring 어플리케이션이 하나씩 있으실텐데요. 

이걸 docker image로 만들고 실제로 실행시키는 것이 이번 주차 과제입니다.

## 요구사항

**수행 조건** 

1. 로컬환경에서 docker를 이용하여 서버를 띄웁니다.
2. Spring application과 mysql 모두 docker 환경에서 구동되어야 합니다. 

**과제 제출 조건**

1. docker ps -a 명령어를 이용하여 현재 실행중인 컨테이너를 스크린샷 찍어 pr에 첨부합니다.
2. postman과 같은 api 테스트 도구를 이용하여 api를 직접 보내보고 결과를 스크린샷으로 첨부합니다.

아마 처음에는 docker 이미지를 만드는 과정부터 막힐 것이라고 생각이 들어요
이런저런 자료를 다 참고해도 괜찮습니다. 한 번 해내면 다음에는 쉬우니까요.

## 제출 방법
- README 파일에 도커를 띄운 사진을 첨부한 후 PR을 올려주세요!

## 실행 결과
## 도커 컨테이너
![docker ps -a](https://github.com/user-attachments/assets/7fb0db42-9b86-4876-add9-87045b43ca72)

### 2. API 테스트 결과 (Postman)
- Todo 생성 API 요청 및 응답
![todo]<https://github.com/user-attachments/assets/f04bd86e-1d02-4228-b771-cbac76d2c9ed>
