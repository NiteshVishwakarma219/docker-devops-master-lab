# Custom Python Docker Image

## Objective

Build a Docker image using a Python application.

---

## Application

```python
print("Docker DevOps Project")
```

---

## Dockerfile

```dockerfile
FROM python:3.11

WORKDIR /app

COPY . .

CMD ["python","app.py"]
```

---

## Build Image

```bash
docker build -t pythonapp .
```

---

## Run Container

```bash
docker run pythonapp
```

---

## Screenshots

- docker-build-success.png
- docker-image-created.png
- docker-container-output.png

---

## Skills Learned

- Dockerfile Creation
- Image Building
- Container Execution
- Python Containerization

---

## Outcome

Successfully containerized a Python application using Docker.