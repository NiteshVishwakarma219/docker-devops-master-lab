# Docker Networking Lab

## Objective

Establish communication between multiple Docker containers.

---

## Network Creation

```bash
docker network create mynetwork
```

---

## Containers

```bash
docker run -d --name c1 --network mynetwork nginx

docker run -d --name c2 --network mynetwork ubuntu sleep infinity
```

---

## Connectivity Test

```bash
ping c1
```

---

## Screenshots

- network-created.png
- both-containers-running.png
- container-ping-success.png
- network-inspect.png

---

## Skills Learned

- Docker Networks
- Service Discovery
- DNS Resolution
- Container Communication

---

## Outcome

Successfully established communication between containers using Docker networking.