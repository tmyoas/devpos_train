Devops Train
---

Training container using docker-compose.

# Required Setting
 * Nexus
```bash
echo 'UID=0' > .env
echo 'GID=0' >> .env
```
or

```bash
sudo chown -R 200:200 /docdata/nexus-data
```
