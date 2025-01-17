# Anleitung WordPress 
In dieser Anleitung geht es darum, wie man in diesem Projekt das WordPress projekt mit Docker miteinander Teilt.

https://chatgpt.com/c/678a8136-9b68-800f-b9e9-2043fd36ab35

### Fortschritt mit deinem Freund teilen (Datenbankexport)
1. Öffne Terminal 
2. docker-compose up -d
3. docker exec wordpress_db mysqldump -uwp_user -pwp_password wp_database > wordpress_db.sql
4. Pushe wordpress_db.sql

### Inport
1. Öffne Terminal 
2. docker exec -i wordpress_db mysql -uwp_user -pwp_password wp_database >  wordpress_db.sql
3. Password = wp_password
4. Warten




