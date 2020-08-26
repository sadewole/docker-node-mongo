# Docker Node MongoDB Example

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build

# To push to dockerhub
docker login

docker tag {image-name} {docker-hub-username}/{default-repo-folder-name}:{image-name}

docker push {docker-hub-username}/{default-repo-folder-name}:{image-name}

```
