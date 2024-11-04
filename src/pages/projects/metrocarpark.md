---
title: Metro Car Park
url: https://metro.benolabs.com
tags: ["REST API, "Express.js", "Node.js", "Cloud Deployment", "Cloudflare DNS"]
---

The Metro Carpark app is a web app enables commuters and travellers to check real time data on the available parking spots, total occupied spots and view historical car parking data of Metro stations in New South Wales, Australia.

The app aims to save time and reduce stress for commuters by knowing exactly where to park before they set out on their journey. 

### **Key Features:**
- **Real-Time Parking Availability:** Instantly view the number of available parking spots at specific Metro stations. See which parking areas are occupied and which are free, allowing for efficient planning before you arrive.
- **Historical parking data:** Historic carpark data to view visual trends in parking availability and insights into the peak and off peak times during the day.

### **Technology stack:**
- **Javascript:** The backend of the application is built using a reliable webframework Express.js, leveraging Javascript libraries including Chart.js for visual graph data and Pug templating engine.
- **REST API:** The Car Park API from Transport Open Data (Transport for NSW), provides real time and historical occupancy of selected Park&Ride car parks.
- **Cloud Deployment:** Built and deployed to the Digital Ocean Cloud platform
- **DNS Security** Built using Cloudflare DNS, traffic is proxied through Cloudflare, Cloudflare can automatically stop DDos attacks from reaching the application and origin server
![Metro Carpark app](/metrocarpark.png)