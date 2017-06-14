# gitstream.io

## Konzept

### Blog
*publish*  
Man kann Beiträge, News, usw. zu sich selbst oder seinen eigenen Projekten erstellen. Diese werden im Stream der Follower angezeigt.

### Stream
*read*  
"Newsfeed", "Pinnwand" zur Darstellung von Infos, News usw. von Benutzern und Projekten denen man folgt.

### Tagging und Mentioning
Erwähnen bzw. Adressieren von Benutzern oder Projekten.

### Messaging
*communicate*  
Man kann anderen Benutzern Nachrichten schreiben.

### MVP
Eigenes Github-Profil und seine Github-Projekte bewerben indem man dazu bloggt.

## Organisation und Tooling
github  
Slack/gitter  
Confluence  
JIRA  

### Betrieb

### Technologie-Stack

#### Webserver
caddy

#### Frontend
reactjs  
bootstrap

#### Persistierung
ElasticSearch

## TODO

### Github-API
 * Description
 * organization
 ** Deren Repos
 

### Message Persistence
 * Speichern und referenzieren mit Kurz-Ids
 * Images auf Sebastians docker repo pushen
 * travis CI Build

### Frontend
  * Neues Repo statt Fork (Unnötige history und Example)
  * Anfang: Speichern und Anzeigen von Messages mit dem message-persistence-service
  * Danach: Login und Githubanbindung
  * Webserver im gleichen Repo (Caddy in docker-compose)
  * Erste klare UI-Richtlinien erdenken

### Allgemein
  * Allgemeine docker-compose.yml mit allen Services + Frontend
  * Google Cloud
