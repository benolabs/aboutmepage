---
title: Metro Car Park
url: https://metropark.benolabs.com
tags: ["REST API", "Express.js", "Node.js", "Traefik", "Cloud Deployment", "Cloudflare DNS"]
---

The Metro Carpark app is a web app enables commuters and travellers to check real time data on the available parking spots, total occupied spots and view historical car parking data of Metro stations in New South Wales, Australia.

The app aims to save time and reduce stress for commuters by knowing exactly where to park before they set out on their journey. 

### **Technology stack:**
- **Javascript:** The backend of the application is built using a reliable webframework Express.js, leveraging Javascript libraries including Chart.js for visual graph data and Pug templating engine.
- **REST API:** The Car Park API from Transport Open Data (Transport for NSW), provides real time and historical occupancy of selected Park&Ride car parks.
- **Traefik:** Traefik load balancer and reverse proxy
- **Cloud Deployment:** Built and deployed to the Digital Ocean Cloud platform
- **DNS Security** Built using Cloudflare DNS, traffic is proxied through Cloudflare, Cloudflare can automatically stop DDoS attacks from reaching the origin server

![Metro Carpark app](/metrocarpark.png)