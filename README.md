# Zermelo-Roosters
Deze plugin werd gebouwd om roosterwijzigingen uit Zermelo weer te geven in een Drupal 7 elo.

De plugin dient als volgt geïnstalleerd te worden:
1. Maak een nieuwe map 'zermelo_roosters' in de map $drupal7root$/sites/all/modules
2. Upload de twee bestanden uit de GitHub-repository
3. Schakel de module via de Drupal administratie interface in (Modules pagina)
4. Configureer de module via de Drupal administratie interface (Instellingen->Webservices->Zermelo Roosters)
5. Configureer het 'blok' van de module via de Drupal administratie interface (Structuur->Blokken)
   De standaard locatie is 'Eerste zijbalk'. Via de instellingen kunt u ook een titel aan het blok toevoegen.

De vereiste Zermelo API-key kan aangemaakt worden via de Zermelo beheerconsole.
Het is nodig op te merken dat deze API-key de volgende gebruikersrollen nodig heeft:
- Leerlingen van les bekijken:           Hele portal
- Docenten van les bekijken:             Hele portal
- Lesgroepen van les bekijken:           Hele portal
- Vakken van les bekijken:               Hele portal
- Lokalen van les bekijken:              Hele portal

- Mededelingen bekijken:                 Hele portal

- Persoonsgegevens adressen bekijken:    Ja
- Persoonsgegevens namen bekijken:       Ja

- Gebruikersrechten gebruikers bekijken: Ja
- Gebruikersrechten API tokens bekijken: Hele portal

Mocht het met de bovenstaande instructies niet lukken om de plugin werkend te installeren, schroom dan niet om contact op te nemen.
