# Ruboty [![Build Status](https://travis-ci.org/r7kamura/bobot.svg?branch=master)](https://travis-ci.org/r7kamura/bobot)
Ruboty on somewhere.

## Setup
```
$ heroku create
$ heroku config:set \
  REDIS_URL="..." \
  SLACK_ROOM="general" \
  SLACK_PASSWORD="..." \
  SLACK_TEAM="tqhouse" \
  SLACK_USERNAME="ellen" \
  SYOBOI_CALENDAR_CHANNEL_IDS="1,3,4,5,6,7,8,19,187" \
  TZ="Asia/Tokyo"
$ git push heroku master
$ heroku scale bot=1
```

## Deploy
```
$ git push heroku master
```

## Request
https://github.com/r7kamura/bobot/fork

## Contact
https://github.com/r7kamura/bobot/issues/new
