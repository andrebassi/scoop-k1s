# Scoop Bucket for k1s

This is the official [Scoop](https://scoop.sh/) bucket for [k1s](https://github.com/andrebassi/k1s) - Kubernetes TUI Debugger.

## Installation

```powershell
# Add the bucket
scoop bucket add k1s https://github.com/andrebassi/scoop-k1s

# Install k1s
scoop install k1s
```

Or install directly:

```powershell
scoop install https://raw.githubusercontent.com/andrebassi/scoop-k1s/main/bucket/k1s.json
```

## Update

```powershell
scoop update k1s
```

## Uninstall

```powershell
scoop uninstall k1s
scoop bucket rm k1s
```

## About k1s

k1s is a terminal-based user interface for debugging Kubernetes workloads.

**One screen to see why your pod is broken.**

Features:
- Real-time container logs with filtering
- Pod events with Warning filtering
- Resource metrics (CPU/Memory)
- HPA monitoring with KEDA support
- ConfigMaps/Secrets viewing
- Cross-namespace resource copy

For more information, visit: https://github.com/andrebassi/k1s
