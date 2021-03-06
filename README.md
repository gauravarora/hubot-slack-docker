# Dockerized and Slack-integrated Hubot

[![Docker Hub](https://img.shields.io/badge/docker-ready-blue.svg)](https://registry.hub.docker.com/u/chihchun/hubot-slack/)
[![](https://images.microbadger.com/badges/image/chihchun/hubot-slack.svg)](https://microbadger.com/images/chihchun/hubot-slack "Get your own image badge on microbadger.com")
[![Join the chat at https://gitter.im/chihchun/hubot-slack-docker](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/chihchun/hubot-slack-docker?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Setup a hubot from https://slack.com/services/new/hubot and assign the API token to the following command

```
docker pull chihchun/hubot-slack
docker run -e HUBOT_SLACK_TOKEN=xoxb-1234567890-XXXXXXXXXXXXXXXXXXXXXXXX -d chihchun/hubot-slack
```

# Hubot Scripts
* hubot-diagnostics
* hubot-help
* hubot-heroku-keepalive
* hubot-google-images
* hubot-google-translate
* hubot-pugme
* hubot-maps
* hubot-redis-brain
* hubot-rules
* hubot-shipit
* hubot-moretext
* hubot-standup-alarm
* hubot-victory

## Reference
* Bot Users | Slack https://api.slack.com/bot-users
