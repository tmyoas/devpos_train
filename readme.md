# Devops Train
---

Training container using docker-compose.

## Required Setting
* If you use reverse proxy, you should erase about ports settings in docker-compose.yml (Because of deny access using http://IPaddress:port). 
### Nexus
* Reference: https://github.com/sonatype/docker-nexus
  * user: admin
  * pass: admin123
```bash
sudo chown -R 200:200 /docdata/nexus-data
```
Because of difference between host-user (The case of Amazon linux, ec2-user) and container-user (According to reference, UID=200, GID=200).

### SonarQube
* Reference: https://github.com/SonarSource/docker-sonarqube
  * user: admin
  * pass: admin
