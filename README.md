# setup-maui Action

 [![Action test on MacOs](https://github.com/weslleymurdock/setup-maui-action/actions/workflows/macos.yml/badge.svg)](https://github.com/weslleymurdock/setup-maui-action/actions/workflows/macos.yml)
 [![Action test on Windows](https://github.com/weslleymurdock/setup-maui-action/actions/workflows/windows.yml/badge.svg)](https://github.com/weslleymurdock/setup-maui-action/actions/workflows/windows.yml)

Github Action to setup [.NET MAUI](https://dot.net/maui) on osx and windows OS runner's ⚙️🖥
Needs an existent .NET Setup

## Usage

### Build MAUI Classlib

***OSX***

```yaml
    steps: 
      - uses: weslleymurdock/setup-maui-action@v1.1
        with:
          dotnet-version: 8.0.x
```

***Windows***

```yaml
    steps:
      - uses: weslleymurdock/setup-maui-action@v1.1
        with:
          dotnet-version: 8.0.x
```

## Contributing

☞ [Guidelines](https://github.com/weslleymurdock/setup-maui-action/blob/main/CONTRIBUTING.md)

## Licensed

☞ This repository uses the [Apache License 2.0](https://github.com/weslleymurdock/setup-maui-action/blob/main/LICENSE)
