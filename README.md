<h1 align="center">
VS Code Extension Samples
</h1>

This repository contains sample code illustrating the VS Code extension API. Each sample is a self-contained extension that explains one topic in [VS Code API](https://code.visualstudio.com/docs/extensionAPI/vscode-api) or VS Code's [Contribution Points](https://code.visualstudio.com/docs/extensionAPI/extension-points). You can read, play with or adapt from these samples to create your own extensions.

You can expect from each sample:
- An explanation of its functionality
- A gif or screenshot demonstrating its usage
- Link to a guide on VS Code website, if it has one
- Listing of used VS Code API and Contribution Points
- Code of the same style, enforced using TSLint and Prettier

## Samples

<!-- SAMPLES_BEGIN -->
| Sample | Guide on VS Code Website | API & Contribution |
| ------ | ----- | --- |
| [Multi Root Sample](basic-multi-root-sample) | N/A | [workspace.getWorkspaceFolder](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#workspace.getWorkspaceFolder)<br>[workspace.onDidChangeWorkspaceFolders](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#workspace.onDidChangeWorkspaceFolders) |
| [Webview Sample](webview-sample) | [/api/extension-guides/webview](https://vscode-ext-docs.azurewebsites.net/api/extension-guides/webview) | [window.createWebviewPanel](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#window.createWebviewPanel)<br>[window.registerWebviewPanelSerializer](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#window.registerWebviewPanelSerializer) |
| [Status Bar](statusbar-sample) | [/api/extension-guides/status-bar](https://vscode-ext-docs.azurewebsites.net/api/extension-guides/status-bar) | [StatusBarItem](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#StatusBarItem) |
| [File System Provider Sample](fsprovider-sample) | N/A | [workspace.registerFileSystemProvider](https://vscode-ext-docs.azurewebsites.net/api/references/vscode-api#workspace.registerFileSystemProvider) |
| [LSP Sample](lsp-sample) | [/api/language-extensions/smart-editing-lsp-guide](https://vscode-ext-docs.azurewebsites.net/api/language-extensions/smart-editing-lsp-guide) |  |
| [LSP Log Streaming Sample](lsp-log-streaming-sample) | N/A |  |
| [LSP Multi Root Server Sample](lsp-multi-server-sample) | https://github.com/Microsoft/vscode/wiki/Extension-Authoring:-Adopting-Multi-Root-Workspace-APIs#language-client--language-server |  |
<!-- SAMPLES_END -->

## :warning: Legacy Samples :warning:

Legacy samples are at [`/legacy-samples`](/legacy-samples). They are unlikely to receive any updates and might not work with the latest version of VS Code.

| Sample | Deprecated Reason |
| ------ | ----------------- |
| [Preview HTML](/legacy-samples/previewhtml-sample/README.md) | [Webview API](/webview-sample/README.md) supersedes the old HTML Preview functionality |

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](https://github.com/Microsoft/vscode-extension-samples/blob/ext-docs/LICENSE) License.