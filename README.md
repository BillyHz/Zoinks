# Zoinks

Repo de actividad diaria automatizada vía GitHub Actions.

Cada día a las 00:00 UTC hace entre 1 y 35 commits a `diary.md` con timestamp.

## Trigger manual

Pestaña Actions → Daily Activity → Run workflow.

## Cambiar el rango de commits

Por defecto random entre 1 y 35. Para forzar un número fijo:

Settings → Secrets and variables → Actions → Variables → New variable:
- Name: `PULSE_COMMITS`
- Value: ej `10`
