## Prometheus Federation Minimal Demo

![img into](assets/images/case_intro_img.jpg)
### Requirements

- Docker, Ref「[Get Docker](https://docs.docker.com/get-docker/)」
- DingTalk WebHook AccessToken, Ref「[dingtalk-custom robot access](https://developers.dingtalk.com/document/robots/custom-robot-access)」

### Quick Start

1、get configs:

```shell
git clone https://github.com/yeshan333/prometheus-federation-minimal-demo.git
cd prometheus-federation-minimal-demo.git
```

2、edit the `configs/dingtalk/config.yml` & update the access token「your dingtalk robot」:

```yaml
targets:
  webhook1:
    url: https://oapi.dingtalk.com/robot/send?access_token=<dingtalk-robaot-access-token>
```

3、start docker service:

```shell
docker-compose up
```

Have fun!

