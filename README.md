# setup-maui Action

[![Action test on Ubuntu](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/ubuntu.yml) [![Action test on MacOs](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/macos.yml/badge.svg)](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/macos.yml) [![Action test on Windows](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/windows.yml/badge.svg)](https://github.com/GuillaumeFalourd/ritchie-cli-action/actions/workflows/windows.yml)

<img width="1000" alt="title" src="https://user-images.githubusercontent.com/22433243/123156441-aa4af780-d43f-11eb-8f1c-b7a8d4d536be.png">

Github Action to setup [.NET MAUI](https://dot.net/maui) on any OS runner ⚙️🖥
Needs an existent .NET Setup

* * *
 
### Requirements

⚠️ [`Actions to setup environments`](https://github.com/marketplace?type=actions&query=setup+env+) are necessary to use this action:

- [setup-dotnet](https://github.com/marketplace/actions/setup-dotnet) for action install workload 

 * * *

## ♻️ Scenarios

### 1️⃣ Run formula from `PUBLIC` Github repository

**Unix**

```yaml
    steps: 
      - uses: weslleymurdock/setup-maui-action@v1
```

**Windows**

```yaml
    steps:
      - uses: weslleymurdock/setup-maui-action@v1
```

## 🤝 Contributing

☞ [Guidelines](https://github.com/weslleymurdock/setup-maui-action/blob/main/CONTRIBUTING.md)

## 🏅 Licensed

☞ This repository uses the [Apache License 2.0](https://github.com/weslleymurdock/setup-maui-action/blob/main/LICENSE)
