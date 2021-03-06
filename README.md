# instagram-scraper-api
Scrapes instagram profiles via headless browser

# Instructions
```
docker-compose build  
docker-compose up  
```

API: `localhost:8080` 

`/user-profile/:username`  
- Scrapes instagram web profile via headless chrome and returns profile info

`/user-profile/queue/:username`  
- Queues background jobs to scrape profile

Kue UI: `localhost:3000`  
- UI to track status of background jobs

# Techonologies
Node.js  
[puppeteer](https://github.com/GoogleChrome/puppeteer)  
[kue](https://github.com/Automattic/kue)  
Redis  
Docker  
Kubernetes  
