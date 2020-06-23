# Git based knowledge base
> dan-maximov's collection

## Requirements

- UNIX Based system / WSL2
- Docker
- Git

## Steps to start

1. Pull repo
2. Execute `docker build -t gollum .` in repository root to build docker image
3. Execure `docker run -v /`pwd`:/wiki -p 4567:80 gollum` in repository root to start Gollum
4. Visit localhost:4567