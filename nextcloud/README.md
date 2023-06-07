# Nextcloud deploy files
This directory includes the following files for deploying nextcloud:
- `nextcloud-pv.yaml`: Configure PV & PVC for nextcloud.
- `nextcloud-values.yaml`: Helm chart deploy settings
    - Install: `helm install my-release nextcloud/nextcloud -f nextcloud-values.yaml`
    - Update settings: `helm upgrade my-release nextcloud/nextcloud -f nextcloud-values.yaml`
- `nextcloud-ingress.yaml`: Ingress settings to expose services.
