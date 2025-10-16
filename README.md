# TP Docker

## 🔹 Challenge 1 – NodeJS + Redis (`app01`)
**Objectif :** Déployer une appli NodeJS reliée à Redis.  
**Commandes :**
```bash
cd app01  
docker compose up -d  
docker compose ps  
docker compose logs -f  
docker compose down -v  
```
**Accès :** http://localhost:8080  
**Capture :** 

<img width="353" height="107" alt="image" src="https://github.com/user-attachments/assets/2c1a8c74-e0b9-4a9e-878f-3addb9414f8b" />


---

## 🔹 Challenge 2 – WordPress + MariaDB + PhpMyAdmin (`app02`)
**Objectif :** Déployer un WordPress avec sa base et PhpMyAdmin.  
**Commandes :**
```bash
cd app02  
docker compose up -d  
docker compose down -v  
```
**Accès :**  
- WordPress → http://localhost:8081  
- PhpMyAdmin → http://localhost:8090  

**Captures :**  
<img width="1536" height="1024" alt="screenshot-2025-10-16_15-32-30" src="https://github.com/user-attachments/assets/2a5c8adc-6a25-406d-b8af-2ad6129b2079" />
<img width="1536" height="1024" alt="screenshot-2025-10-16_15-46-33" src="https://github.com/user-attachments/assets/17245a7b-fb64-48f8-b311-f90bdc400e5c" />

