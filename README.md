### docker 빌드와 실행

`docker build -f Dockerfile.dev -t jaeha/next ./`

`docker run jaeha/next`

### 포트 매핑

`docker run -p 3000:3000 jaeha/next`
