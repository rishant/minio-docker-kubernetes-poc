# Project Structure

This project contains two separate folders: one for Docker configurations and another for Kubernetes configurations.

## Tree Structure

```
.
├── README.md
├── docker
│   ├── docker-compose.yml
│   ├── passwd-s3fs
│   └── ubuntu_s3fs
│       ├── Dockerfile
│       ├── requirements.txt
│       └── script.py
└── kubernetes
    ├── minio
    │   ├── deployment.yml
    │   ├── service.yml
    │   ├── pv.yml
    │   └── pvc.yml
    ├── ubuntu-s3fs
    │   ├── deployment.yml
    │   ├── Dockerfile
    │   ├── requirements.txt
    │   └── script.py
    └── ubuntu-volume
        └── deployment.yml
```