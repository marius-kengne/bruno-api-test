# Bruno - Test Avancé : API de citations

## Pré-requis
- Bruno CLI installé : https://www.usebruno.com/
- API disponible sur `http://localhost:5000`
- Nodejs

## Lancement des tests
```bash
npm install -g @usebruno/cli
cd collections/quotes_tests
bru run --env env --reporter-json results.json --reporter-junit results.xml --reporter-html results.html
```

## Scénarios testés
1. Création d'une citation à partir d’un fichier JSON externe
2. Vérification du code retour et stockage de l’`ID`
3. Requête GET avec l'`ID` pour vérifier que la citation a bien été créée
