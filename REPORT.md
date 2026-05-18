CI/CD Pipeline per Web Application Statica
1. repository GitHub

il codice sorgente del progetto è disponibile al seguente link:

https://github.com/dani20041502/ci-cd-static-site

2. sito web live (GitHub Pages)

il sito statico è stato pubblicato automaticamente tramite GitHub Actions e risulta accessibile al seguente indirizzo:

https://dani20041502.github.io/ci-cd-static-site/

3. descrizione della pipeline CI/CD

il progetto implementa una pipeline CI/CD composta da tre fasi principali:

Quality Check (CI): verifica del codice HTML tramite HTMLHint e controllo dei link con Lychee.
Docker Build & Push: costruzione dell’immagine Docker e pubblicazione su GitHub Container Registry (GHCR).
Deploy (CD): pubblicazione automatica del sito su GitHub Pages.

la pipeline è progettata in modo tale che ogni fase dipenda dal successo della precedente, garantendo che solo codice valido venga distribuito.