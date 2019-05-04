# Zappa Commit Alarm


## Getting Started
```zsh
$ git clone https://github.com/LuceteYang/express-skeleton.git your-project-name
$ cd your-project-name
$ cp github.ini.copy github.ini
$ cp gmail.ini.copy gmail.ini
# gmail github 계정 수정
$ cp gmail.ini.copy gmail.ini
$ pip install zappa
$ zappa deploy production

# 두번째 부터는 update로 배포를 진행합니다.
$ zappa update production
```

## Reference
1. https://github.com/phillyai/commit-twitter-bot
2. https://github.com/geekhub-lab/commit-alarm
3. https://mingrammer.com/dev-commit-alarm-bot/

#### zappa
4. http://dveamer.github.io/backend/FlaskZappaAWSLambda.html
5. https://velog.io/@city7310/%EB%B0%B1%EC%97%94%EB%93%9C%EA%B0%80-%EC%9D%B4%EC%A0%95%EB%8F%84%EB%8A%94-%ED%95%B4%EC%A4%98%EC%95%BC-%ED%95%A8-9.-Compute-Engine-%EA%B2%B0%EC%A0%95%EA%B3%BC-Hello-World-%EC%84%9C%EB%B2%84-%EB%B0%B0%ED%8F%AC