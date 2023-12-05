# Ostoslista
Sovelluksen tarkoitus on olla käyttäjälle hyödyllinen ostoslistasovellus, jolla pystyy tehdä ja tarkastella ostoslistoja esimerkiksi kauppareissuja varten.

Sovelluksen käyttäjä pystyy
- Luoda käyttäjätilin ja kirjautua sisään
- Luoda ostoslistoja ja tarkastella niitä
- Lisätä ostoslistoihin tuotteita
- Tarkastella ostoslistan tuotteita
- Muokata ja poistaa ostoslistoja
- Muokata ja poistaa tuotteita ostoslistoissa

# Julkaisu
Backend ja frontend ovat julkaistu CSC:n Rahti-palvelun OpenShiftissa. Ne pyörivät siellä omissa Docker-konteissa.
- Frontend: https://haagaheliashoppinglist.rahtiapp.fi/
- Backend: https://shoppinglist-backend.rahtiapp.fi/

Backend käyttää Heroku-pilvipalvelussa olevaa PostgreSQL tietokantaa.

# Repositoriot
- Frontend: https://github.com/Team-WHITE-Ohjelmistoprojekti-2/shoppinglist-frontend
- Backend: https://github.com/Team-WHITE-Ohjelmistoprojekti-2/shoppinglist-backend

# Teknologiat
Sovellus sisältää erillisen frontendin ja backendin. Backendissä on REST API, jota frontend käyttää.

Tietokantana toimii PostgreSQL tuotantoympäristössä, ja H2 kehitysympäristössä.

- Frontend tehdään React-ohjelmistokirjastolla ja JavaScriptilla. Käytämme [Vite](https://vitejs.dev/) työkalua.
- Frontend käyttää Radix UI -komponenttikirjastoa, mistä saa responsiivisia käyttöliittymäkomponentteja.
- Backend tehdään Spring Boot -ohjelmistokehyksellä ja Javalla.
- Sovellus sisältää autentikaation, mikä käyttää JSON Web Tokenia (JWT).
- Docker ja Docker Compose sekä frontendilla, että backendilla.

# Timiin Backlogit ja Sprintti 
- Kaikki tarvittavat tiedot löytyvät Trellosta.
- https://trello.com/w/teamwhitebacklogssprint

# Tiimin jäsenet
- Juuso Hakala - https://github.com/hollowdll
- Leo Ahopalo - https://github.com/DiviXe
- Jouni Kaitasalo - https://github.com/jkaitasalo
- Ruichao Guan - https://github.com/mikkeGuan
- Topias Naskali - https://github.com/TopiasNaskali
- Oliver Roman - https://github.com/Gjubas
