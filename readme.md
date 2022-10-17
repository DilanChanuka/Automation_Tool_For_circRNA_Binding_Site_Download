#This project created to download the circRNA binding sites from Circinteractome database ("https://circinteractome.nia.nih.gov/rna_binding_protein.html").
#Playwright (https://playwright.dev/) 

npm i -D playwright

npx playwright codegen "https://circinteractome.nia.nih.gov/rna_binding_protein.html"

node .\download.js
