# Sibil Monitor — legacy release archive

This repository is retained only as a historical archive of early Sibil
Monitor CLI binaries. It is no longer maintained and must not be used for new
installations.

The canonical open-source agent, documentation and provenance-attested
releases now live at:

- source: <https://github.com/sibil-monitor/sibil-agent>
- latest release: <https://github.com/sibil-monitor/sibil-agent/releases/latest>
- public product identity: <https://sibil.sh/>

## Supported install path

Inspect the canonical installer before running it:

```bash
curl -fsSL https://github.com/sibil-monitor/sibil-agent/releases/latest/download/install.sh -o sibil-install.sh
less sibil-install.sh
sudo sh sibil-install.sh
```

The current supported agent release is `v1.4.2`. Its release contains Linux
`amd64`/`arm64` binaries, checksums, an install script and GitHub artifact
attestations.

Historical releases in this repository remain available for audit and
reproducibility only. Their presence does not imply current support or
security maintenance.
