# HA Connect – Home Assistant App (Add-on)

Öffentliches Repository für den Home-Assistant-App-Store.

Cloud/API-Code liegt **nicht** hier (privates Repo).  
Live-API: https://ha-connect.com

## Installation in Home Assistant

1. **Einstellungen → Apps → App-Store**
2. Rechts oben **⋮ → Repositories**
3. URL hinzufügen:

   ```text
   https://github.com/projex-aris/ha-connect-addon
   ```

4. App **HA Connect** installieren (lädt vorgebautes Image von GHCR – kein lokaler Build auf dem Pi)
5. Optionen:
   - `api_base`: `https://ha-connect.com`
   - `pairing_code`: Code aus dem Dashboard (https://ha-connect.com)
6. Starten und Logs prüfen

Image: `ghcr.io/projex-aris/ha-connect-addon` (amd64 / arm64 / armv7)

## Struktur

```
repository.yaml
ha_connect/
  config.yaml
  Dockerfile
  DOCS.md
  rootfs/...
```
