# Bijlage III – Scheidingstekens in csv-bestand

Als uw csv-bestand niet op de juiste manier de gegevens scheidt, kan dit problemen opleveren tijdens de import op sbr-wonen.nl. Onderstaande (of een soortgelijke) melding geeft aan dat dit het geval is:

> _"Rij 1 voldoet niet aan de validatie. Er worden 27 parameters verwacht. Er zijn er 1 verstrekt. Rij overgeslagen."_

Nederlandstalige programma's gebruiken vaak puntkomma (semicolon) als scheidingsteken, omdat de komma als decimaalteken wordt gebruikt. Dit is bijvoorbeeld het geval bij geldbedragen. Ook wordt er vaak bij Nederlandse programma's geen gebruik gemaakt van dubbele aanhalingstekens.

Als dit op uw csv-bestand van toepassing is, dan is de makkelijkste oplossing om uw systeembeheerder te vragen om de landinstellingen en daarbij de scheidingstekens aan te passen in het configuratiescherm. Vervolgens kunt u een nieuw csv-bestand maken.

Een andere oplossing is om via een editor, zoals Kladblok, het probleem op te lossen door de volgende stappen uit te voeren:

{% hint style="warning" %}
**Let op!**

Deze methode is foutgevoelig, dus heeft niet onze voorkeur!
{% endhint %}

1. Open het csv-bestand in Kladblok: open Kladblok, klik in het menu op **Bestand** en selecteer **Openen**. Selecteer vervolgens het csv-bestand.
2. **Het aanpassen van de komma naar puntkomma (semicolon).** Klik in het menu op **Bewerken** in de menubalk en selecteer vervolgens **Vervangen**. In het veld **Zoeken naar** typt u `,` (zonder aanhalingstekens), u vult in het veld **Vervangen door** `;` (zonder aanhalingstekens).
3. **Het aanpassen van de punt naar komma bij geldbedragen.** Klik in het menu op **Bewerken** in de menubalk en selecteer vervolgens **Vervangen**. In het veld **Zoeken naar** typt u `.` (zonder aanhalingstekens), u vult in het veld **Vervangen door** `,` (zonder aanhalingstekens).
4. Na de bewerkingen moet u het bestand opslaan door in het menu op **Bestand** te klikken en vervolgens op **Opslaan**.
5. Vervolgens kunt u een nieuw csv-bestand aanmaken.
6. Uw csv-bestand is nu gereed om te importeren op sbr-wonen.nl voor de validatie.
