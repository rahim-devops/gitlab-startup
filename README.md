# gitlab-startup

i want to install locally in my Ubuntu virtual machine (vmware) the following :
coredns, nginx, gitlab using docker compose and over HTTPS ( SSL/TLS ).
This is my services folder structure:
.
├── certs
│   ├── cert.crt
│   └── key.key
├── coredns
│   ├── Dockerfile
│   ├── README.md
│   ├── config
│   │   ├── Corefile
│   │   └── devops.dz.hosts
│   └── docker-compose.yml
├── gitlab
│   ├── README.md
│   ├── docker-compose.yml
│   └── sample.env
└── nginx
    ├── README.md
    ├── conf.d
    │   └── gitlab.devops.dz.conf
    ├── docker-compose.yml
    ├── html
    │   └── index.hmlt
    └── nginx.conf

