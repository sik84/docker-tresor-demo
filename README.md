# docker-tresor-demo
Demo: NGINX mit Docker und .dockerignore

# 🚀 Einfaches Docker Image – Push auf Docker Hub

Ein minimaler Workflow zum Erstellen und Hochladen eines Docker Images auf Docker Hub.

## 📦 Schritte im Überblick

### 🔨 1. Image bauen
```bash
docker build -t <Benutzername>/<image-name>:<tag> .
```

```
docker build -t meinname/mein-image:latest .
```

---

###  2. Lokale Images anzeigen
```docker images
```

---

### 3. Image auf Docker Hub pushen

```docker push <Benutzername>/<image-name>:<tag>
```

---

### 4. Image von Docker Hub ziehen

```docker pull <Benutzername>/<image-name>:<tag>
```

---

### ✅ Vorteile
Plattformunabhängiges Deployment

Einfaches Teilen von Images

Ideal für Tests, Lernzwecke und DevOps-Workflows

Hinweis: Erstelle vorher ein Repository auf hub.docker.com, falls noch nicht geschehen.