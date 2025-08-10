# Character.AI Token Capture & Integration Tools (Desktop)

[Mobile Page](./README_MOBILE.md)

---

> **Warning / Disclaimer:**  
> This is an **unofficial** userscript created by an enthusiast with **no affiliation** to Character.AI or its development team.  
> Use this tool **at your own risk**. The author is **not responsible** for any token leaks, account issues, or other problems resulting from misuse.  
>  
> The token capture method currently works by intercepting network requests, but Character.AI may change their system at any time, breaking this script.  
> This project is still in early stages and will be updated as needed to keep pace with website changes.  
>  
> By using this, you accept all risks involved.

---

## About

Character.AI doesn't offer an official API, making it a pain to get your authentication token for integrations and unofficial tools. This repository and the userscript here aim to make that process way easier by capturing the token automatically when you activate Voice Enabled Mode in chats.

---

## How to Use (Desktop)

### 1. Install ViolentMonkey Extension

- Install [**ViolentMonkey**](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) extension for Chrome or Edge.

### 2. Install the Token Capture Userscript

- Get the latest version from [GreasyFork](https://greasyfork.org/en/scripts/545327-character-token) and install it via ViolentMonkey.

### 3. Capture Your Token

1. Open [Character.AI](https://character.ai) and log in.  
2. Start a chat with any AI character.  
3. Click the **"Activate Voice Enabled Mode"** button next to the chat's "..." settings menu.  
4. A modal will pop up displaying your token — copy it.  
5. To capture again, reload the page and repeat.

---

## Usage & Related Projects

Use your captured token with popular unofficial Character.AI libraries like:

- [node_characterai by realcoloride](https://github.com/realcoloride/node_characterai)  
- [PyCharacterAI by Xtr4F](https://github.com/Xtr4F/PyCharacterAI)

Explore those repos for integration examples and bot development.

---

## Screenshots & Examples

<!--  
Add screenshots or GIFs here demonstrating:  
- Installing ViolentMonkey  
- Activating Voice Enabled Mode  
- Token modal popup

Markdown image syntax example:  
![Example](./images/example.png)  
-->

---

## Contributing

This project is open to improvements, bug reports, feature requests, and external contributions.  
Feel free to open issues or pull requests — let’s make this better together.

---

## License

For educational and research purposes only. No warranties provided.

---

*Created by Golden4484 — Use responsibly and don’t be that guy.*
