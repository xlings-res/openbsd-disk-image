# openbsd-disk-image

OpenBSD 8.0 (amd64) installed from the release's own media, with a serial console, as a qcow2 disk for emulator runners

Installed by the release's installer (autoinstall(8)) from cd80.iso and the official sets, verified against the release's signed SHA256.sig.

Packaged for xlings by the recipe `pkgs/*/openbsd-disk-image.lua` of
[openxlings/xim-pkgindex](https://github.com/openxlings/xim-pkgindex), whose
`.agents/tools/` holds the script that assembled it. Each release's
`PROVENANCE.md` (inside the archive) states the upstream files, their digests and every change.
