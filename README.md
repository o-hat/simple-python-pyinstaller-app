# simple-python-pyinstaller-app

1. 安装kenkins

```bash
docker run \
  --rm \
  -u root \
  -p 9009:8080 \
  -v jenkins-data:/var/jenkins_home \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v "$HOME":/home \
  jenkinsci/blueocean
```