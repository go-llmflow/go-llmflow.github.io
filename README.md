# go-llmflow.github.io

Landing page of the [go-llmflow](https://github.com/go-llmflow) organisation,
published at <https://go-llmflow.github.io/>. Built with Hugo and the shared design
of [go-fleettools/landingkit](https://github.com/go-fleettools/landingkit), a Hugo
module pinned in `go.mod`.

The brand colours are read from `static/img/logo.svg`
(`go run github.com/go-fleettools/landingkit/cmd/landingkit brand static/img/logo.svg`).
The repositories on the page are listed in `hugo.toml`; the `ci` workflow fails if
one is missing. The gateway is shown as **v0.21.0, current release**: change that line, the
tags in `hugo.toml` and the documentation together at the next release.

```sh
hugo server
```
