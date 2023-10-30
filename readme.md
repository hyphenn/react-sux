```bash
npm run build
docker build -f Dockerfile-nginx -t turtle .
docker run --rm -it -p 8080:80 turtle
```