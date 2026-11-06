# yaw-mode-mirror

Public mirror of the yaw-mode bundle manifest + tarball (CDN-outage fallback for the Yaw app).

This repository holds ONE rolling GitHub release (`v0.0.0`) whose assets are
clobbered by `release.sh` on every Yaw release: `manifest.json` and
`yaw-mode-v<version>.tar.gz`, uploaded together so a manifest never names an
un-uploaded tarball. The Yaw client falls back to
`releases/latest/download/...` here when cdn.yaw.sh is unreachable.
