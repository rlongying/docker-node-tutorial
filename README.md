
# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

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
```

> the node app code is cloned from [bradtraversy](https://github.com/bradtraversy/docker-node-mongo), 
> while following his docker tutorial on [YouTube](https://www.youtube.com/watch?v=hP77Rua1E0c)