---
title: R & D
layout: projects
description: Projects by Belkirk College
publish_date: '2017-11-01T03:00:00.000+00:00'
menu:
  navigation:
    identifier: _projects
    weight: 3
  footer:
    identifier: _projects
    url: "/projects/"
    weight: 2

---

Our use of Docker and cloud containers allows for portability of our systems.  Strapi docker install setup is simple.

[https://www.youtube.com/watch?v=kazEAzGWuIc](https://www.youtube.com/watch?v=kazEAzGWuIc "https://www.youtube.com/watch?v=kazEAzGWuIc")

Dockerhub: >> [strapi/strapi](https://hub.docker.com/r/strapi/strapi "Docker")

Github: >> [github.com/strapi/strapi-docke](https://github.com/strapi/strapi-docker "github")r

[install Docker](https://docs.docker.com/engine/install/ "install Docker engine")

to start a Strapi server, run this command:

    docker run -it -p 1337:1337 -v `pwd`/project-name:/srv/app strapi/strapi