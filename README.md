# Character.AI Token Capture & Integration Tools (Desktop)

[Mobile Page](./README_MOBILE.md)

---

> **Disclaimer:**  
> This is an unofficial userscript developed by an independent enthusiast and is not affiliated with the Character.AI team.  
> Use this software at your own risk. The author is not responsible for any consequences, including token leaks or account issues.  
>  
> The method used to capture tokens relies on intercepting network requests and may break if Character.AI updates their system.  
> This project is in active development to adapt to such changes.  
>  
> By using this tool, you accept these terms.

---

## Overview

Character.AI currently does not provide a public API, which complicates obtaining authentication tokens required for unofficial integrations and tools. This repository offers a userscript solution that simplifies token capture by intercepting network requests triggered when activating the Voice Enabled Mode in chats.

---

## Installation and Usage (Desktop)

### Step 1: Install ViolentMonkey Extension

Install the ViolentMonkey browser extension for Chrome or Edge:

- [ViolentMonkey on Chrome Web Store](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)

### Step 2: Install the Token Capture Userscript

Install the userscript via ViolentMonkey by visiting:

- [Character Token Capture Script on GreasyFork](https://greasyfork.org/en/scripts/545327-character-token)

### Step 3: Capture Your Authentication Token

1. Open [Character.AI](https://character.ai) and log in to your account.  
2. Start a chat with any AI character.  
3. Click the **"Activate Voice Enabled Mode"** button located beside the chat’s settings ("...") menu.  
4. A modal window will appear displaying your authentication token. Copy this token for use in integrations or tools.  
5. To capture the token again, refresh the page and repeat the process.

---

## Related Projects

Use the captured token with the following popular unofficial Character.AI integration libraries:

- [node_characterai](https://github.com/realcoloride/node_characterai) by realcoloride  
- [PyCharacterAI](https://github.com/Xtr4F/PyCharacterAI) by Xtr4F

Refer to these repositories for guidance on how to integrate and build applications using your token.

---

## Contribution

Contributions, bug reports, and feature requests are welcome. Please submit issues or pull requests to help improve this project.

---

## License

This project is provided for educational and research purposes only. No warranties or guarantees are implied.

---

Created by Golden4484
