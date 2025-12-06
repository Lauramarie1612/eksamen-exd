# eksamen-exd

# Akvarie - Interaktiv Startskærm og Fiske-Pacman Spil

**Multimediedesign - Tema 3 (EXD)**
**Udvikler:** Laura Marie Bech Jensen (2025)

Dette projekt består af to sammenhængende digitale oplevelser:

1. **En interaktiv startskærm**, hvor brugeren kan udforske akvariet (havunivers), klikke på fisk, høre lyd, se talebobler og åbne/lukke en skattekiste.

2. **Et spil (Fiske-Pacman)**, hvor man styrer en fisk, samler mad, undgår en fjende og får point med visuel +1 og lyd-feedback.

Projektet er udviklet med fokus på **Experience Design**, **brugervenlighed**, **tilgængelighed** og **visuel feedback**.

# Optimeringer lavet i dette EXD projekt

- Forbedring af kisten i figma
- POP UP effekt +1 point og lyd på point
- SHAKE animation ved game over
- Lavet den farlige fisk om til en haj og gjort den langsommere
- Gør knapperne mere CTA
- Forbedret mappe struktur
- Nemo fisk om til GIF inde i Photoshop
- Tilføje Favicon

# 1. Startskærm (index.html)

Den interaktive startskærm lader brugeren møde karakterer fra havet og lære noget om dem gennem en informationbobel

### Funktioner på startskærmen

- Klik på en fisk, så bliver der vist **talebobler** med information
- Havfruen bevæger munden når hun snakker (åben/lukket animation)
- Hver fisk afspiller sin **egen lyd** (information) + en "blob" effekt ved klik
- En **skattekiste** der kan åbnes og lukkes via klik
- Baggrundsmusik

### Filen bruger:

- **HTML**: Strukturering af figurer, koraller, kiste, knap til spillet
- **CSS**: Animationer, responsivt loyut, positionering
- **JavaScript**:
- Event listeners på fiskene
- Lydafspilning i række følge
- Toggle af kiste
- Havfrue mund animation
- Taleboble-system
- Luk boble ved klik undenfor (ikke på en fisk)

# 2. Fiske- Pacman
