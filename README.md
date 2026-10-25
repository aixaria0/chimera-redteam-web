# CHIMERA Red Team — Public Web Surface

This repository contains only the static public interface for CHIMERA Red Team.

The analysis engine, test runner, evidence logic, provider integrations and development history are maintained separately in a private repository. No private source, credentials, repository history or runtime evidence is published here.

## Deployment

GitHub Pages serves the root of the `main` branch. Deployment is updated manually. There are no push or pull-request workflows.

## Security boundary

This site does not execute repository code, access private repositories or accept uploaded evidence. It builds local CLI commands and documents the public operating boundaries. Actual analysis and test execution happen explicitly on the operator's machine.

## Local preview

```bash
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080`.
