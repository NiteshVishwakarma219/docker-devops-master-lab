# Nginx Container Deployment

## Objective

Deploy a web server using Docker.

---

## Commands Used

```bash
docker pull nginx

docker run -d --name mynginx -p 8080:80 nginx
```

---

## Verification

Accessed Nginx web server through browser.

```text
http://localhost:8080
```

---

## Screenshots

- nginx-running.png
- nginx-browser.png

---

## Skills Learned

- Container Deployment
- Port Mapping
- Web Server Hosting
- Docker Networking Basics

---

## Outcome

Successfully deployed and accessed an Nginx web server using Docker.