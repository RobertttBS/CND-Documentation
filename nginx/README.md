## Nginx Reverse Proxy config
This config is to reverse proxy to the following services:
- Kubernetes Ingress
    - Nextcloud: `/nextcloud -> 172.23.0.2:80/nextcloud -> my-release-nextcloud:8080`
    - Nextcloud Metric Export: `/_metrics -> 172.23.0.2:80/_metrics -> my-release-nextcloud-metrics:9205`
- Grafana: `/grafana -> localhost:3000`
