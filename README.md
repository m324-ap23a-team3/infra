# infra – Betrieb (Ops)

Teil von **M324 Projekt 4: Ticketsystem**. Team-Repo: [m324-ap23a-team3/team](https://github.com/m324-ap23a-team3/team)

Code Owner: Team `ops` (Maintain); Team `dev` hat Write (Branch + Pull Request).

Gehört hierher (gemäss Praxis/Readme.md):

- Deployment-Konfiguration (z.B. `docker-compose.yml` für ms1, ms2 und je eine MariaDB)
- Deploy-Pipeline
- Secrets **nur** als GitHub Actions Secrets/Variables, nie im Code
- Smoke Tests aus den Akzeptanzkriterien
- Monitoring und Runbook

Images aus den Build-Pipelines:

- `ghcr.io/m324-ap23a-team3/ms1:<commit-sha>`
- `ghcr.io/m324-ap23a-team3/ms2:<commit-sha>`
