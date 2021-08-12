TriggerTest

## jenkins 서버 URL에 localhost가 들어가서 안됨

jenkins 시스템설정에서 jenkins Location을 수정해서 해결



## github의 webhook 설정을 수정해보았지만...

jenkins의 token이 잘못 들어가있었나보다. 

jenkins에서 생성한 triggertoken을 다시 생성해서 넣어주니 

에러메세지가 fail to connect에서

response 404로 바꼇다!

## webhook URL에 아이디와 비밀번호를 추가해줬다

jenkins의 token을 넣어줬는데 필요한가,,?싶지만



## build trigger 수정

GitHub hook trigger for GITScm polling 체크박스 추가



## ssh-keygen 공개키를 deploy에 추가

## jenkins-plugin git-integration 추가

## webhook 프로젝트 URL 변경

## http://i5a109.p.ssafy.io:8000/github-webhook

## http://i5a109.p.ssafy.io:8000/github-webhook/

github webhook에서 에러는 안난다.