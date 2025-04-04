---
title: Coffee Brew Recipe
url: https://brewratio.benolabs.com
tags: ["python", "FastAPI", "Traefik", "Cloud Deployment", "MySQL", "Cloudflare DNS"]
---

Coffee Brew Recipe is a web app developed for coffee enthusiasts who want to perfect their brewing techniques. Whether you're a casual drinker or a passionate barista, this app provides a platform to record your coffee brews and improve consistency in brewing that perfect cup of coffee.

### **Technology Stack:**
- **Python:** The backend of the application is built using a modern webframework FastAPI, leveraging python libraries including pydantic for data validation and jinja2 templating engine.
- **Traefik:** Traefik load balancer and reverse proxy
- **MySQL Backend Database:** The Web app is connected to a MySQL database to store and manage the Application data
- **Cloud Deployment:** Built and deployed to the Digital Ocean VPS
- **DNS Security** Built using Cloudflare DNS, traffic is proxied through Cloudflare, Cloudflare can automatically stop DDoS attacks from reaching the origin server

![Coffee Brew Recipe](/coffeebrewrecipe2.png)