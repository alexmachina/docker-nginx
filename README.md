# Static Website Docker Image
```bash
podman run -d -p 80 --name website -v /home/alex/code/sample/website:/var/www/html/website:Z alexxmde/nginx nginx
```
