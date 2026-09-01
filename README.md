# storagetax/scoop-bucket

The Scoop bucket for `stxctl`.

```powershell
scoop bucket add storagetax https://github.com/storagetax/scoop-bucket
scoop install stxctl
```

`bucket/stxctl.json` is written by the release workflow in the private monorepo. Do not hand-edit it —
its `hash` values come from the release's signed `checksums.txt`.

Scoop is the Windows path because a bucket needs nobody's approval: publishing is a push, with no
account, no review queue and no publisher identity. winget and Chocolatey both add a moderation
queue per version.
