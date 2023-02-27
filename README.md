# Ansible Collections

This repository contains Ansible collections.

---

## Usage

### Install collections

```bash
ansible-galaxy collection install -r requirements.yml
```

#### `requirements.yml` file example:

```yaml
---

collections:
    - https://github.com/zcubbs/ansible-collections/releases/download/v1.0.0/zcubbs-general-1.0.0.tar.gz
```

---

## Releases

https://github.com/zcubbs/ansible-collections/releases

---

## Ansible Collection - General

### Roles

- [x] pip - Install and configure pip
- [x] certbot - Install and configure Certbot
- [x] haproxy - Install and configure HAProxy
- [ ] nginx - Install and configure NGINX
- [ ] apache - Install and configure Apache
- [x] ping - Ping hosts

---
## Ansible Collection - Cloud Native

### Roles

- [x] k3s - Install and configure k3s
- [x] traefik - Install and configure Traefik
- [x] cert-manager - Install and configure cert-manager
- [x] helm - Install and configure Helm
- [x] argocd - Install and configure ArgoCD

### Playbooks

None

### Modules

None

---

## Ansible Collection - Docker

### Roles

- [x] docker - Install and configure Docker and Docker Compose
- [x] docker-login - Login to Docker registry
- [x] docker-logout - Logout from Docker registry
- [x] deploy-image - Deploy Docker image

### Playbooks

None

### Modules

None
