Forked from [jsonpath-online-evaluator](ashphy/jsonpath-online-evaluator)

去除了外部资源(css, js)文件依赖，适用于内网环境部署。

## Requirements
- node.js v16.17.1

## Build on your environment
Artifacts placed under the `build`.

```
  $ npm install
  $ npm start # Starting the dev server
  $ npm run build # Building the static files
```

## Run on docker

```bash
 $ docker build -t jsonpath-online-evaluator .
 $ docker run -d -p 8080:80 jsonpath-online-evaluator:latest
```
