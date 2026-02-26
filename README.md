### Setup For Local Machine Environment
- Ensure you have .env.local on your directory
- Build and the Image and Run the `containers` to docker
```bash
  user@ubuntu:~/$: docker-compose -f docker-compose.yml build
  user@ubuntu:~/$: docker-compose -f docker-compose.yml -p optimize_route up -d
```
OR
```bash
  user@ubuntu:~/$: docker-compose -f docker-compose.yml -p optimize_route up -d --build
```