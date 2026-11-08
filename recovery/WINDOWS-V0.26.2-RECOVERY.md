# Smart Keyboard Profiles — Windows herstelpunt 0.26.2

Vastgelegd: 2026-11-08.

## Bekende, door de gebruiker goedgekeurde werkende versie
- Versie: **0.26.2**
- Bronrepo: `alex2026-cmd/smart-keyboard-profiles`
- Exacte broncodecommit: `20f353432e610be245c9595f940eb0813211ad3c`
- Herstelbranch 1: `archive/windows-v0.26.2-known-good-2026-11-08`
- Herstelbranch 2: `archive/windows-v0.26.2-fallback-copy`
- Windows-installatie: https://github.com/alex2026-cmd/smart-keyboard-downloads/releases/download/v0.26.2/SmartKeyboardProfiles-Setup-0.26.2.exe
- Vastgelegde installatie-SHA-256: `4a0def7682c4fdaa61930bbc83a1d521376e311fc73adf749832fff96cd55e86`

## Herstellen
1. Schakel automatische updates tijdelijk uit of onderbreek de updater zodat een nieuwere versie de herstelde installatie niet direct opnieuw vervangt.
2. Maak een veilige kopie van de lokale profielen en instellingen.
3. Gebruik het bovenstaande installatiebestand van release v0.26.2 (controleer bij voorkeur de SHA-256-checksum).
4. Indien een nieuwe versie niet over een oudere geïnstalleerd kan worden, verwijder dan eerst uitsluitend de nieuwe app-versie; bewaar gebruikersgegevens.
5. Installeer versie 0.26.2 en controleer Office-herkenning, virtueel toetsenbord, Smart Context, sneltoetsassistent en typetrainer.
6. Voor codeherstel: maak een nieuwe herstelbranch vanaf exact de broncodecommit hierboven; verplaats niet automatisch `main` of andere ontwikkelbranches.

## Beveiligingsafspraken
- Niet wijzigen, hergebruiken, resetten of verwijderen: beide `archive/windows-v0.26.2-*`-branches.
- Laat Windows WPF intact tijdens de macOS-ontwikkeling.
- Nieuwe functies eerst in een aparte ontwikkelbranch, met geslaagde Windows-tests vóór publicatie.
- Vervang nooit de `v0.26.2`-release of het bestand daarin.
- Bewaar ook een offline kopie van de installer, omdat GitHub-assets en branches door beheerders verwijderd kunnen worden.

**Opmerking:** GitHub-branches en releases zijn zonder repositoryregels niet technisch onveranderlijk. Dit document beschrijft een gecontroleerd herstelpad, geen absolute garantie.
