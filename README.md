# Zoorikcloud/scoop-bucket

The Scoop bucket for `zoorikctl`.

```powershell
scoop bucket add zoorikcloud https://github.com/Zoorikcloud/scoop-bucket
scoop install zoorikctl
```

`bucket/zoorikctl.json` is written by the release workflow in `Zoorikcloud/k8spilot`. Do not hand-edit it —
its `hash` values come from the release's signed `checksums.txt`.

Scoop is the Windows path because a bucket needs nobody's approval: publishing is a push, with no
account, no review queue and no publisher identity. winget and Chocolatey both add a moderation
queue per version.
