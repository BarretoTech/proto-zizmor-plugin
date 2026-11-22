# Proto plugin for zizmor

Install [zizmor](https://github.com/zizmorcore/zizmor) with [Proto](https://moonrepo.dev/proto).

## Install

```sh
proto plugin add zizmor https://github.com/BarretoTech/proto-zizmor-plugin/releases/download/v0.1.0/plugin.toml
proto install zizmor 1.32.0
proto run zizmor 1.32.0 -- --version
```

Add the locator and tool version to `.prototools` to pin them for a project.

```toml
zizmor = "1.32.0"

[plugins.tools]
zizmor = "https://github.com/BarretoTech/proto-zizmor-plugin/releases/download/v0.1.0/plugin.toml"
```

Install tests cover Linux x64 and ARM64, macOS Intel and Apple Silicon, and Windows x64 with Proto 0.63.2.

The plugin configuration is available under the [MIT License](LICENSE).
