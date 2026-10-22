# Noordernacht

Statische site: alles staat in `index.html` (plus media en `logo.svg` in de root).

## Live zetten

De site is gekoppeld aan GitHub: alles wat op `main` komt, staat automatisch live.
Een wijziging live zetten = de pull request naar `main` mergen. Er is geen aparte deploystap.

## Conventies

- Bij elke wijziging het versienummer ophogen: regel 1 (`<!-- Versie: ... -->`) en de `version-tag` (`vXX.X`) in `index.html`.
- Mobiel is de basis-CSS; desktop staat in `@media (min-width: 640px)`.
