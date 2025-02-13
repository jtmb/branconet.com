<h1 align="center">
  <a href="https://github.com/jtmb">
    <img src="https://avatars.githubusercontent.com/u/86915618?v=4" alt="Logo" width="" height="125">
  </a>
</h1>

<div align="center">
  <b>jtmb-dev</b> - A personal site.
  <br />
  <br />
  <a href="https://github.com/jtmb/jtmb-dev/issues/new?assignees=&labels=bug&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/jtmb/jtmb-dev/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  .
  <a href="https://hub.docker.com/repository/docker/jtmb92/jtmb-dev/general">Docker Hub</a>
</div>
<br>
<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
    - [Docker Image](#docker-image)
    - [Running on Docker Compose](#running-on-docker-compose)
- [License](#license)

</details>
<br>

### <h1>About </h1>

A personal dev website.


### <h2>Getting Started</h2>
### [Docker Image](https://hub.docker.com/r/jtmb92/jtmb-dev)
```docker
 docker pull jtmb92/jtmb-dev
```
### Running on Docker Compose  
Run on Docker Compose (this is the recommended way) by running the command "docker compose up -d".  
```yaml
---
services:
  jtmb-dev:
    image: jtmb92/jtmb-dev:latest
    ports:
      - "8080:80"
```
## License

This project is licensed under the **GNU GENERAL PUBLIC LICENSE v3**. Feel free to edit and distribute this template as you like.

See [LICENSE](LICENSE) for more information.