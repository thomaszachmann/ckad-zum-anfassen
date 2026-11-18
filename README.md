# CKAD zum Anfassen – Begleitcode

Begleitcode zum Buch **CKAD zum Anfassen** – Certified Kubernetes Application Developer,
praxisnahe Prüfungsvorbereitung. Teil der Reihe IT-Trainingslager von Thomas Zachmann.

Buchseite: https://it-trainingslager.de/buecher/ckad

## Inhalt

- `notes-api/` – kleine Go-API (Go 1.27), die du im Buch selbst als Image baust
  (Dockerfile schreibst du an Tag 2), in die lokale Registry schiebst und durch alle
  Trainingstage begleitest.

Alle Schlüssel und Passwörter im Buch (z. B. `lab-key-123`) sind Laborwerte – nie in
Produktion verwenden.

Getestet mit kubeadm v1.37.2, containerd v2.4.2, Calico v3.33.1, Traefik v3.7.19 und
podman 4.9.3 auf Ubuntu 24.04.

## Schnellstart

```bash
git clone https://github.com/thomaszachmann/ckad-zum-anfassen
cp -r ckad-zum-anfassen/notes-api ~/ckad/notes-api
```

## Hinweis

Dieses Projekt steht in keiner Verbindung zur Linux Foundation oder zur CNCF. CKAD ist
eine Marke der Linux Foundation.
