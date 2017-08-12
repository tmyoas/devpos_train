# Devops Train
---

Training container using docker-compose.

## Required Setting
### Nexus
* Reference: https://github.com/sonatype/docker-nexus

```bash
sudo chown -R 200:200 /docdata/nexus-data
```
Because of difference between host-user (The case of Amazon linux, ec2-user) and container-user (According to reference, UID=200, GID=200).
