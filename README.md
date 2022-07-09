# test_ajax
## Allumer le serveur
### Prérequis
Le serveur Node.js doit préablement être allumé: 
https://github.com/leonardfrot/test_web_services

### Avec Xampp
https://www.apachefriends.org/fr/download.html<br/>
Clone ce repository dans `xampp/htdocs`.<br/>
Allumer le serveur Apache. <br/>
Le site est disponible à http://localhost/test_ajax/.

## Fonctions
Il a été préparé dans le but de tester le scraping sur un site qui n'utilise pas de Framework moderne.
Il fait un appel vers le serveur Node.js et remplace la value du titre.
Si le scraper récupère l'ancienne valeur, le scraper ne fonctionne pas, dans le cas inverse, il fonctionne.

## Résultat
Selenium, Puppeteer, Playwright marche parfaitement.<br/>
Pyppeteer qui ne marchait pas avec le site en React marche également sur ce site.
