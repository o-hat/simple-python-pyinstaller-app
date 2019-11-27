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

2. jenkins的安装插件


3. github账号的token、及作用域

4. 配置项目的web hook

5. 设置jenkins的账号、项目设置