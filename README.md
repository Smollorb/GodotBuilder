Pour les accès :

Créer un PAT avec read:packages et faire

```bash
echo "TON_PAT" | docker login ghcr.io -u smollorb --password-stdin
docker pull ghcr.io/smollorb/godot-builder:latest
```