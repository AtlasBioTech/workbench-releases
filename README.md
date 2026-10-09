# Atlas Workbench — releases

Binary releases of the **Atlas Workbench**: an AI assistant for bio/pharma
scientists. Chat on the left, a notebook on the right; the assistant queries
public databases (UniProt, AlphaFold DB, ClinVar, Europe PMC…), writes a
reproducible analysis, and shows its sources.

This repository holds **releases only**. The source code is private.

## Installer / Install

**Linux, macOS**

```bash
curl -fsSL https://github.com/AtlasBioTech/workbench-releases/releases/latest/download/install.sh | sh
```

puis / then:

```bash
atlas-workbench --demo     # essayer sans clé d'API / try it without an API key
atlas-workbench setup      # choisir son modèle / choose your model (OpenRouter, Scaleway, …)
atlas-workbench update     # mettre à jour / update
```

**Windows**: téléchargez / download `atlas-workbench_<version>_windows_amd64.zip`
from the [latest release](https://github.com/AtlasBioTech/workbench-releases/releases/latest),
unzip it, and run `atlas-workbench.exe`.

Chaque archive est vérifiée par `SHA256SUMS`. Les binaires ne sont pas encore
signés : macOS et Windows demandent une confirmation au premier lancement.
Each archive is checked against `SHA256SUMS`. Binaries are not signed yet:
macOS and Windows ask for confirmation on first launch.

## Licence

[PolyForm Strict 1.0.0](LICENSE).

Usage gratuit à des fins non commerciales, y compris pour les organismes de
recherche, de santé et d'enseignement publics, quel que soit leur
financement. Pas de redistribution, de modification ni d'œuvre dérivée, ce
qui inclut les skills de l'agent. L'usage commercial nécessite une licence
d'AtlasBioTech.

Free for noncommercial use, including by public research, health and
educational organisations whatever their funding. No redistribution,
modification or derived works, the agent's skills included. Commercial use
needs a licence from AtlasBioTech.

Each archive carries `LICENSE` and `THIRD_PARTY_NOTICES.txt` (the open
source components inside and their licences).

## Contact

AtlasBioTech — https://demoatlas.online

© 2026 AtlasBioTech.
