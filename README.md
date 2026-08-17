# Entire Scoop Bucket

Private Scoop bucket for the Entire CLI.

## Installation

First, add the bucket:

```powershell
scoop bucket add entire https://github.com/entireio/scoop-bucket.git
```

Then install:

```powershell
scoop install entire/entire
```

If your existing Scoop package is named `cli`, migrate once:

```powershell
scoop uninstall cli
scoop install entire/entire
```

## Updating

```powershell
scoop update
scoop update entire
```

## Uninstall

```powershell
scoop uninstall entire
scoop bucket rm entire
```
