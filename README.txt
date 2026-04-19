PWA Launcher - file pronti

1) Apri index.html
2) Cerca APP_CONFIG
3) Sostituisci:
   - mainUrl con il link reale AppSheet o altro gestionale
   - i quickLinks con i tuoi link reali
4) Se vuoi, cambia il nome app in APP_CONFIG.appName
5) Sostituisci le icone nella cartella icons
6) Carica tutto su GitHub nel repository
7) Attiva GitHub Pages sul branch principale

Struttura:
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png
- icons/apple-touch-icon.png

Nota:
Questo launcher NON usa iframe per AppSheet.
Apre il gestionale direttamente nel browser, soluzione in genere più stabile.
