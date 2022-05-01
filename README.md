# helm-charts

## 기존 존재하는 차트 받아오기

```bash
helm pull bitnami/nginx
```

## values.yaml 존재한느 곳에서 charts 파일을 가지고 실행

```bash
helm install nginx . -f values.yaml
```