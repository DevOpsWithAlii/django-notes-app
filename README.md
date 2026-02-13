# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React


## 📊 Monitoring & Observability (Grafana + Prometheus)

The project includes a complete monitoring setup using **Prometheus, Grafana, cAdvisor, Node Exporter, and MySQL Exporter** to visualize application, container, and database metrics.

### 🔹 Docker & Container Monitoring
![Container Monitoring](https://github.com/DevOpsWithAlii/django-notes-app/blob/main/staticfiles/media/Screenshot%20(352).png)

### 🔹 Prometheus  Monitoring
![Prometheus Monitoring](https://github.com/DevOpsWithAlii/django-notes-app/blob/main/staticfiles/media/Screenshot%20(353).png)

### 🔹 cADvisor monitoring
![cADvisor Monitoring](https://github.com/DevOpsWithAlii/django-notes-app/blob/main/staticfiles/media/Screenshot%20(354).png)


## Installation.
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
