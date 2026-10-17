# Movva CLI Scoop Bucket

Official Scoop bucket for installing the [Movva CLI](https://github.com/movva-tech/movva-cli) on Windows.

## Install

Add this bucket to Scoop:

```powershell
scoop bucket add movva-cli https://github.com/movva-tech/movva-cli-scoop-bucket
```

Install the CLI:

```powershell
scoop install movva
```

Verify the installation:

```powershell
movva --help
```

## Update

Scoop checks for updates when you run:

```powershell
scoop update
scoop update movva
```

## Package manifests

Package manifests are maintained automatically from Movva CLI releases. If a
new release is not yet available through Scoop, use the installer or download
the archive from the [Movva CLI releases page](https://github.com/movva-tech/movva-cli/releases).

## Support

For CLI usage, installation alternatives, and release downloads, see the
[Movva CLI distribution repository](https://github.com/movva-tech/movva-cli).
