# Inhoudstafel
[Algemene Info](#algemene-info)

[Functionele Vereisten](#functionele-vereisten)

[Modules](#modules)

# Algemene Info
## Inhoud

Deze pagina bevat alle documentatie over het project 'Win It'.

# Functionele Vereisten

- De gebruiker moet zich kunnen registeren en moet kunnen inloggen.
- De gebruiker moet de mogelijkheid hebben om zijn gebruikersdata te wijzigen.
- De gebruiker heeft de keuze om een "Winbox" aan te maken. Hij/zij kan hiervan de instellingen zelf bepalen (aantal spelers, inzet & etc)
- Langst de andere kant kan een gebruiker ook deelnemen aan een winbox.
- Als een gebruiker deelneemt aan de winbox moet hij een [spel](#spel) spelen waardoor hij deze winbox kan winnen.
- De gebruiker moet winboxen kunnen raadplegen volgens zijn voorkeuren (prijs & etc).
- De gebruiker kan premium of gold abonnementen aanvragen
- De gebruiker moet coins kunnen aankopen
- De gebruiker moet zijn coins kunnen inruilen voor geld
- De gerbuiker moet zijn hisotriek kunnen zien (winboxen, coins aankopen/verkopen & etc)

# Spel

De gebruiker speelt een quiz waarmee hij/zij punten kan winnen.
De persoon met de meeste punten wint de winbox.
De score wordt beïnvloed door de snelheid waarmee hij/zij deze oplost.

# UI & UX

## Pages
- Feed
    - Feed instellingen
- Beschikbare boxen (die waar jij inzit en die nog bezig zijn)
- Winbox toevoegen
- Historiek van winboxen waar je aan hebt meegedaan, aankopen/verkopen coins, winnen van games & etc
    - Meer info over bepaalde transactie (aankopen/verkopen, winbox historiek & etc)
- Shop (abonnement aankopen & coins aankopen)
- Coins inruilen voor geld
- Profiel pagina met al zijn gegevens
    - Subpagina met tegels (change userinfo, change paypal adress)

# Modules
## Core Service

[Github Repo](https://github.com/loganbogaert/Winit)

Deze service is de core.

## Paypal Service

[Github Repo](https://github.com/loganbogaert/Winit-third-party-microservice)

Deze service houdt zich bezig met paypal transactions.

## Frontend

[Github Repo](https://github.com/loganbogaert/winitFrontEnd/)


&copy; Logan Bogaert en Jarno Bogaert