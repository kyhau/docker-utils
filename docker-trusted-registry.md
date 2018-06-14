# Docker Trusted Registry

### TODO


#### docker hub

The most common public repository for published Docker images.


#### Overlay Network

Overlay Network allows Docker Trusted Registry components running on different nodes to communicate and replicate
Docker Trusted Registry data.
```
dtr-ol
```


Endpoints exposed by Docker Trusted Registry that can be used to assess the health of a Docker Trusted Registry replica
```
/health
/nginx_status
/api/v0/meta/cluster_status
```