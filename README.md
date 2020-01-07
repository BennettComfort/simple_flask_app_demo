# simple_flask_app_demo
Creating a simple flask app using docker containers
----

.
├── README.md
├── api
│   ├── Dockerfile
│   ├── linkextractor.py
│   ├── main.py
│   └── requirements.txt
├── docker-compose.yml
└── www
    └── index.php

2 directories, 7 files
----

#### Pre-requisites:
1. docker must be installed on machine
2. Docker-Compose must be installed on your machine
3. Ports 5000 and ports 80 must not be currently in use

*If ports 5000 and ports 80 are currently in use and it's mandatory, replace ports in source code to ununesed ports*

#### Instructions:
RUN
1. `git clone https://github.com/BennettComfort/simple_flask_app_demo.git`
2. `cd simple_flask_app_demo`
3. `docker-compose up -d --build`

**Attempt api**
`curl -i http://0.0.0.0:5000/api/http://example.com/`

Open URL http://0.0.0.0:80/
^^^ Enter any URL you choose

#### Extras
Here is a link to my very not so elegant first attempt at docker and flask. https://github.com/BennettComfort/Simple-WebAPP-DevOps-POC

