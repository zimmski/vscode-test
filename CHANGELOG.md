# Changelog

### 0.3.0 | 2019-04-13

- 🙌 Add TypeScript as dev dependency. [#9](https://github.com/Microsoft/vscode-test/pull/9)
- 🙌 Adding a simpler way of running tests with only `vscodeExecutablePath` and `launchArgs`. [#8](https://github.com/Microsoft/vscode-test/pull/8).

### 0.2.0 | 2019-04-12

- 🙌 Set `ExecutionPolicy` for Windows unzip command. [#6](https://github.com/Microsoft/vscode-test/pull/6).
- 🙌 Fix NPM http/https proxy handling. [#5](https://github.com/Microsoft/vscode-test/pull/5).
- Fix the option `vscodeLaunchArgs` so it's being used for launching VS Code. [#7](https://github.com/Microsoft/vscode-test/issues/7).

### 0.1.5 | 2019-03-21

- Log folder to download VS Code into.

### 0.1.4 | 2019-03-21

- Add `-NoProfile`, `-NonInteractive` and `-NoLogo` for using PowerShell to extract VS Code. [#2](https://github.com/Microsoft/vscode-test/issues/2).
- Use `Microsoft.PowerShell.Archive\Expand-Archive` to ensure using built-in `Expand-Archive`. [#2](https://github.com/Microsoft/vscode-test/issues/2).

### 0.1.3 | 2019-03-21

- Support specifying testing locale. [#1](https://github.com/Microsoft/vscode-test/pull/1).
- Fix zip extraction failure where `.vscode-test/vscode-<VERSION>` dir doesn't exist on Linux. [#3](https://github.com/Microsoft/vscode-test/issues/3).