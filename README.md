# Ruboty [![Build Status](https://travis-ci.org/sorah/probot.svg?branch=master)](https://travis-ci.org/sorah/probot)
Ruboty on somewhere.

## Setup
```
$ heroku create
$ heroku config:set \
  REDIS_URL="..." \
  SLACK_ROOM="general" \
  SLACK_PASSWORD="..." \
  SLACK_TEAM="..." \
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


