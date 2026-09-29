# VSIX Repository

This repository stores and distributes VS Code extensions (`.vsix`).

Due to GitHub repository file size limits and optimal bandwidth, extension binaries are hosted under [GitHub Releases](https://github.com/how0531/vsix/releases).

## Included Extensions

### 1. Anthropic Claude Code
- **Publisher**: Anthropic
- **Extension Name**: Claude Code for VS Code
- **Version**: 2.1.284
- **Platform**: Windows x64 (`win32-x64`)
- **Direct Download**: [Download anthropic.claude-code-2.1.284-win32-x64.vsix](https://github.com/how0531/vsix/releases/download/v2.1.284/anthropic.claude-code-2.1.284-win32-x64.vsix)
- **Release Page**: [Release v2.1.284](https://github.com/how0531/vsix/releases/tag/v2.1.284)

### 2. OpenAI ChatGPT (Codex)
- **Publisher**: OpenAI
- **Extension Name**: Codex – OpenAI’s coding agent
- **Version**: 26.721.30844
- **Platform**: Windows x64 (`win32-x64`)
- **Direct Download**: [Download openai.chatgpt-26.721.30844-win32-x64.vsix](https://github.com/how0531/vsix/releases/download/chatgpt-v26.721.30844/openai.chatgpt-26.721.30844-win32-x64.vsix)
- **Release Page**: [Release chatgpt-v26.721.30844](https://github.com/how0531/vsix/releases/tag/chatgpt-v26.721.30844)

### 3. Microsoft Python
- **Publisher**: ms-python
- **Extension Name**: Python
- **Version**: 2026.4.0
- **Platform**: Universal
- **Direct Download**: [Download ms-python.python-2026.4.0.vsix](https://github.com/how0531/vsix/releases/download/python-v2026.4.0/ms-python.python-2026.4.0.vsix)
- **Release Page**: [Release python-v2026.4.0](https://github.com/how0531/vsix/releases/tag/python-v2026.4.0)

---

## How to Install

### Method 1: VS Code UI
1. Download the desired `.vsix` file from the links above.
2. Open VS Code.
3. Go to the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`).
4. Click the **...** (Views and More Actions) menu in the top-right corner of the Extensions pane.
5. Select **Install from VSIX...** and choose the downloaded `.vsix` file.

### Method 2: Command Line
```bash
# Install Claude Code
code --install-extension anthropic.claude-code-2.1.284-win32-x64.vsix

# Install ChatGPT (Codex)
code --install-extension openai.chatgpt-26.721.30844-win32-x64.vsix

# Install Python
code --install-extension ms-python.python-2026.4.0.vsix
```
