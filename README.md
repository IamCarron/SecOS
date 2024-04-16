<p align="center">A fork of AtlasOS focused on security, without leaving behind usability and performance.</p>

<p align="center">
  <a href="https://atlasos.net" target="_blank">🌐 AtlasOS Website</a>
  •
  <a href="https://docs.atlasos.net" target="_blank">📚 AtlasOS Documentation</a>
  •
  <a href="https://discord.atlasos.net" target="_blank">☎️ AtlasOS Discord</a>
  •
  <a href="https://forum.atlasos.net" target="_blank">💬 AtlasOS Forum</a>
</p>

## 📚 **Important Documentation**
- [Installation](https://docs.atlasos.net/getting-started/installation/)
- [FAQ & Common Issues](https://docs.atlasos.net/faq-and-troubleshooting/removed-features/)
- [Contribution Guidelines](https://docs.atlasos.net/contributions/)
- [Branding](https://docs.atlasos.net/branding/)

## 🤔 What is SecOS?
SecOS is an open source fork of AtlasOS that enhances Windows by eliminating factors that negatively affect performance. 
SecOS focuses on security as it focuses on the daily use of Windows to ensure end-user safety.

## 👀 Why SecOS?

As computer geeks, we all have family members who don't use their computers primarily for gaming. SecOS aims to provide these types of users with a fast user experience, similar to AtlasOS, but with a stronger focus on security and privacy.

Trying to follow Microsoft's official methods.

### 🔍 Open Source and Transparent

Unlike custom Windows ISOs, Atlas is more straightforward to audit due to the use of [AME Wizard](https://ameliorated.io). AME Wizard is controlled by Playbooks, a customizable script-esque system that can perform various tasks.

Playbooks are renamed **.zip** archives, with the password [`malte`](https://docs.ameliorated.io/developers/getting-started/creation.html). As they primarily consist of plain text, Playbooks enable transparency, unlike custom Windows ISOs, which have many entry points for malicious activity. The few binaries in the Playbook are open source in our [`utilities` repository](https://github.com/Atlas-OS/utilities), with the [hashes listed here](https://github.com/Atlas-OS/Atlas/blob/main/src/playbook/Executables/AtlasModules/README.md).

Although the GUI is not open source for AME Wizard, AME Wizard's entire backend (called [TrustedUninstaller](https://github.com/Ameliorated-LLC/trusted-uninstaller-cli)) is open source under MIT, which contains each action used to run SecOS. The Atlas Playbook is open source under the [GPLv3 license](https://github.com/iamcarron/SecOS/blob/main/LICENSE).

### 🔒 Legal Compliance
As Atlas doesn't redistribute a modified Windows ISO, it complies with [Windows's Usage Terms](https://www.microsoft.com/en-us/Useterms/Retail/Windows/10/UseTerms_Retail_Windows_10_English.htm). In addition, Atlas does not alter activation in Windows.
