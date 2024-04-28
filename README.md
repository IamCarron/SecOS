<p align="center">A fork of AtlasOS that focuses on security without compromising usability or performance.</p>

<p align="center">
  <a href="https://atlasos.net" target="_blank">🌐 AtlasOS Website</a> |
  <a href="https://docs.atlasos.net" target="_blank">📚 AtlasOS Documentation</a> |
  <a href="https://discord.atlasos.net" target="_blank">☎️ AtlasOS Discord</a> |
  <a href="https://forum.atlasos.net" target="_blank">💬 AtlasOS Forum</a>
</p>

## 📚 **Important Documentation**
- [Installation](https://docs.atlasos.net/getting-started/installation/)
- [FAQ & Common Issues](https://docs.atlasos.net/faq-and-troubleshooting/removed-features/)
- [Contribution Guidelines](https://docs.atlasos.net/contributions/)
- [Branding](https://docs.atlasos.net/branding/)

## 🤔 What is SecOS?
SecOS is an open-source fork of AtlasOS that improves Windows by eliminating factors that negatively impact performance. It emphasizes security to ensure user protection during daily use of Windows.

## 👀 Why Choose SecOS?

SecOS is designed for users who want a fast, secure experience similar to AtlasOS but with a greater emphasis on security and privacy. It is ideal for those who don't primarily use their computers for gaming.

SecOS adheres to Microsoft's official methods.

### 🔍 Open Source and Transparent

Unlike custom Windows ISOs, SecOS easier to audit due to the use of [AME Wizard](https://ameliorated.io). AME Wizard is controlled by Playbooks, a customizable script-like system that can perform various tasks.

Playbooks are **.zip** files with the password [`malte`](https://docs.ameliorated.io/developers/getting-started/creation.html). Since they primarily consist of plain text, Playbooks offer transparency, unlike custom Windows ISOs, which have many entry points for malicious activity. The few binaries in the Playbook are open source in our [`utilities` repository](https://github.com/Atlas-OS/utilities), with the [hashes listed here](https://github.com/Atlas-OS/Atlas/blob/main/src/playbook/Executables/AtlasModules/README.md).

Although the GUI of AME Wizard is not open source, the entire backend (called [TrustedUninstaller](https://github.com/Ameliorated-LLC/trusted-uninstaller-cli)) is open source under MIT and contains each action used to run SecOS. The SecOS Playbook is open source under the [GPLv3 license](https://github.com/iamcarron/SecOS/blob/main/LICENSE).

### 🔒 Legal Compliance
SecOS complies with [Windows's Usage Terms](https://www.microsoft.com/en-us/Useterms/Retail/Windows/10/UseTerms_Retail_Windows_10_English.htm) because it doesn't redistribute a modified Windows ISO. Additionally, SecOS does not alter Windows activation.

### 🤝 Contributions
SecOS began as a class project, so frequent updates are not guaranteed. Contributions are welcome and appreciated to help improve the project.