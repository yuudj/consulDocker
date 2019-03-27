# DOCKER COMPOSE FILE FOR CONSUL
Docker compose file for a development envirioment of[consul.io](consul.io)

**DONT USE FOR PRODUCTION!!!!!!** 
**The following ports must be available**
- 9300
- 9500
- 9600

*If you need to use diferent ports, change the docker-compose.yml*

```bash
git clone https://github.com/yuudj/consulDocker.git
cd consulDocker
docker-compose up -d
```
