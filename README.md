# Stategraph Releases
This repository hosts release binaries for [Stategraph](https://stategraph.com).

## Downloads
See the [Releases](https://github.com/stategraph/releases/releases) page for available versions.

## Docker Images
Docker images are available on [GitHub Container Registry](https://github.com/orgs/stategraph/packages):

```bash
# Client CLI
docker pull ghcr.io/stategraph/stategraph:VERSION

# Server (API + Web Console)
docker pull ghcr.io/stategraph/stategraph-server:VERSION
```

## Why a separate repository?
The main Stategraph repository is private. GitHub Release assets inherit the repository's visibility, so we publish releases here to allow unauthenticated downloads.
