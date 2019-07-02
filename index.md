# Get latest Assets

An API to always get the latest assets from a github release.

## Usage

```bash
curl -LO https://api.getlatestassets.com/github/:owner/:repo/:asset-name[?version=version-constraint]
```

version-constraint can be any version-contraint that you know from composer. So f.e. "^2.4" will fetch the latest version with major version 2 as long as it is higher than 2.4. So f.e. 2.4.1 or 2.5 or 2.6.7 but no 3.0.0.

## Roadmap

* Include latest assets from GitLab
* Include latest assets from BitBucket
* Include latest releases from Atlassian-Products… (That would be scratching my own itch…)
