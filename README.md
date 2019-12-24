# tecobrary-services-integration
테코브러리의 서비스 (Slackbot, ELK) 통합을 위한 레포지토리입니다. 


## 실행 방법
``` shell
ELK_VERSION=[ELK_스택_버젼] SLACK_AUTH_TOKEN=[슬랙_토큰] REQUESTED_CHANNEL=[희망도서_요청_알림_채널_ID] ENROLLED_CHANNEL=[희망도서_도착_알림_채널_ID] MYSQL_URL=[MYSQL_URL_입력] MYSQL_PORT=[MYSQL_PORT_입력] docker-compose up
```
