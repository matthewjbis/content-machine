# n8n workflow management

This folder holds JSON exports of workflows running on this VPS's n8n instance
(n8n.mattbis.com). The live instance runs in Docker, container name: `n8n-docker-caddy-n8n-1`.

## To pull the latest workflows from the live instance:
docker exec n8n-docker-caddy-n8n-1 n8n export:workflow --all --output=/tmp/workflows/
docker cp n8n-docker-caddy-n8n-1:/tmp/workflows/. /opt/content-machine/workflows/

## To sync changes to the live instance:
docker cp /opt/content-machine/workflows/<file>.json n8n-docker-caddy-n8n-1:/tmp/workflows/<file>.json
docker exec n8n-docker-caddy-n8n-1 n8n import:workflow --input=/tmp/workflows/<file>.json

## Workflow before importing an update to an ACTIVE workflow:
1. Deactivate it in the n8n UI first (known bug: cron triggers can double-fire on import)
2. Import
3. Reactivate

## Credentials are referenced by ID, not included in exports — don't recreate them,
reference existing credential IDs already in the n8n instance.
