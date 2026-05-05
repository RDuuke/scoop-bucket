# RDuuke Scoop Bucket

Scoop bucket for [RDuuke](https://github.com/RDuuke) Go CLIs on Windows.

## Setup

```powershell
scoop bucket add rduuke https://github.com/RDuuke/scoop-bucket
```

## Available Manifests

### nea-ai

Local-first control plane for AI dev agents. Repo: <https://github.com/RDuuke/nea-ai>.

```powershell
scoop install nea-ai
nea-ai --help
```

### neabrain

Local-first persistent memory and MCP server for AI dev agents. Repo: <https://github.com/RDuuke/nea-brain>.

```powershell
scoop install neabrain
neabrain --help
```

## Updates

```powershell
scoop update nea-ai
scoop update neabrain
```

This bucket is updated automatically by [GoReleaser](https://goreleaser.com) when
a new `v*` tag is pushed to each upstream repo. Do not edit `bucket/*.json` by
hand — open issues in the upstream repos instead.

## Uninstall

```powershell
scoop uninstall nea-ai
scoop uninstall neabrain
scoop bucket rm rduuke
```
