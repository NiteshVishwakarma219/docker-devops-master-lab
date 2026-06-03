# Custom Website Deployment Using Docker

## Objective

Deploy a custom HTML website inside an Nginx container.

---

## Files

### index.html

```html
<h1>Docker Portfolio Project</h1>
```

---

## Command Used

```bash
docker run -d --name website -p 8090:80 -v ${PWD}:/usr/share/nginx/html nginx
```

---

## Verification

```text
http://localhost:8090
```

---

## Screenshots

- custom-website-volume.png
- volume-inspect.png

---

## Skills Learned

- Volume Mounting
- Static Website Hosting
- Data Persistence

---

## Outcome

Successfully hosted a custom website using Docker volume mounting.