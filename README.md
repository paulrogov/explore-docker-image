# Docker image explorer
**Useful to explore base images**  
Starts a container using an image specified in a [Dockerfile](Dockerfile).

```bash
# 1. start a container
docker-compose up -d

# 2. attach terminal to it
docker exec -ti sample bash

# 3. explore:

# OS
cat /etc/issue
# users
lslogins
# groups
cat /etc/group
```
