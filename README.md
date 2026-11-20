# CKAD hands-on – Companion Code

Companion code for the book **CKAD hands-on** (German edition: *CKAD zum Anfassen*) – Certified
Kubernetes Application Developer, practical exam preparation. Part of Thomas Zachmann's IT Drills series.

Book page: https://itdrills.com/books/ckad · German edition: https://it-trainingslager.de/buecher/ckad

## Contents

- `notes-api/` – a small Go API (Go 1.27) that you build into an image yourself in the book
  (you write the Dockerfile on Day 2), push to the local registry and carry through all
  training days.

All keys and passwords in the book (e.g. `lab-key-123`) are lab values – never use them in
production.

Tested with kubeadm v1.37.2, containerd v2.4.2, Calico v3.33.1, Traefik v3.7.19 and
podman 4.9.3 on Ubuntu 24.04.

## Quick start

```bash
git clone https://github.com/thomaszachmann/ckad-zum-anfassen
cp -r ckad-zum-anfassen/notes-api ~/ckad/notes-api
```

## Disclaimer

This project is not affiliated with the Linux Foundation or the CNCF. CKAD is a trademark
of the Linux Foundation.
