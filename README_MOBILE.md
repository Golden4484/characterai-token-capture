# Character.AI Token Capture & Integration Tools (Mobile)

[Readme Desktop](./README.md)

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

Obtaining authentication tokens on mobile devices can be challenging due to browser restrictions and lack of official API support. This repository provides a userscript and detailed instructions for capturing your Character.AI token using mobile browsers that support user scripts and extensions.

---

## Installation and Usage (Mobile)

### Step 1: Install Kiwi Browser

Download and install Kiwi Browser, a Chromium-based browser for Android with support for user scripts and extensions:

- [Kiwi Browser on Google Play Store](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)

### Step 2: Install Userscript Manager Extension

Within Kiwi Browser, install either ViolentMonkey or Tampermonkey:

- [ViolentMonkey](https://violentmonkey.github.io/)  
- [Tampermonkey](https://www.tampermonkey.net/)

### Step 3: Install the Token Capture Userscript

Install the userscript from GreasyFork using your userscript manager:

- [Character Token Capture Script on GreasyFork](https://greasyfork.org/en/scripts/545327-character-token)

### Step 4: Capture Your Authentication Token

1. Open [Character.AI](https://character.ai) and log in on your mobile browser.  
2. Start a chat with any AI character.  
3. Tap the **"Activate Voice Enabled Mode"** button located beside the chat’s settings ("...") menu.  
4. A modal window will display your authentication token. Copy the token for your use.  
5. To capture the token again, reload the page and repeat the process.

---

## Related Projects

Use your captured token with popular unofficial Character.AI integration libraries:

- [node_characterai](https://github.com/realcoloride/node_characterai) by realcoloride  
- [PyCharacterAI](https://github.com/Xtr4F/PyCharacterAI) by Xtr4F

Refer to these repositories for guidance on integration and bot development.

---

## Contribution

Contributions, bug reports, and feature requests are welcome. Please submit issues or pull requests to improve this project.

---

## License

This project is provided for educational and research purposes only. No warranties or guarantees are implied.

---

Created by Golden4484
