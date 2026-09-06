# scoop-bucket

```powershell
scoop bucket add hashiiiii https://github.com/hashiiiii/scoop-bucket
scoop install prefablens
```

After [PrefabLens PR #326](https://github.com/hashiiiii/PrefabLens/pull/326) merges, the Release workflow will publish manifest updates to this bucket.
This bucket has no separate update workflow or `checkver` / `autoupdate` configuration.

After the Release workflow updates this bucket, install the new version:

```powershell
scoop update prefablens
```

For manifest changes, edit `cli/pkg/prefablens.json` in PrefabLens.
