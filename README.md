# scoop-pile

I will submit a PR to the official Scoop bucket for any `manifest` that meets its criteria. It will be removed from this bucket after the PR is merged.

## Usage

```pwsh
scoop bucket add pile https://github.com/scillidan/scoop-pile
scoop install pile/<app>
```

```pwsh
# Optional
scoop config virustotal_api_key <key>
scoop virustotal <app>
```
