# Unfold Neo — NEO-app op GitHub Pages

Dit is de **losse NEO-app** (frontend) die volledig statisch op GitHub Pages draait,
inclusief alle sport-/talentvarianten (de `assets/neo/`-map wordt via https geladen).

## Online zetten (2 minuten)

1. Maak een GitHub-repo en zet deze map erin (`index.html`, `assets/`,
   `.github/workflows/deploy-pages.yml`).
2. `git add . && git commit -m "NEO-app" && git push`.
3. GitHub → repo → **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. De workflow deployt automatisch; je krijgt een URL als
   `https://<jij>.github.io/<repo>/`.

## Belangrijk — wat dit WEL en NIET is

✅ De NEO-app zelf: challenges, NEO met animerend gezicht, alle varianten.
❌ **Geen** login, geen rollen, geen voortgang-opslag, geen betalingen.
❌ **Geen** veilige scheiding leerling/mentor — een statische site kan dat niet
   afdwingen (clientcode is aanpasbaar).

Voor inloggen met Microsoft 365 + harde rolscheiding + voortgang per klas heb je
een backend nodig; zie de projectopties (Azure Static Web Apps of Vercel+database).
