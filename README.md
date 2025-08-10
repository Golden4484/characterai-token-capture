# Character.AI Token Capture & Integration Tools

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

## How to Use

### Mobile (Recommended Browser: Kiwi Browser)

1. Install [**Kiwi Browser**](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser) or any mobile browser that supports user scripts and extensions like ViolentMonkey or Tampermonkey.  
2. Install [**ViolentMonkey**](https://violentmonkey.github.io/) or [**Tampermonkey**](https://www.tampermonkey.net/) extension in the browser.  
3. Open [Character.AI](https://character.ai) and log in.  
4. Start a chat with any AI character.  
5. Tap the **"Activate Voice Enabled Mode"** button next to the chat's "..." settings menu.  
6. A modal will pop up displaying your token — copy it.  
7. To capture again, reload the page and repeat.

---

### Desktop

1. Install [**ViolentMonkey** extension for Chrome or Edge](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag).  
2. Install the userscript from [GreasyFork](https://greasyfork.org/en/scripts/545327-character-token).  
3. Open [Character.AI](https://character.ai) and log in.  
4. Start a chat with any AI character.  
5. Click the **"Activate Voice Enabled Mode"** button next to the chat's "..." settings.  
6. The token modal will appear — copy your token.  
7. Reload the page to capture again if needed.

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
- Installing ViolentMonkey/Tampermonkey  
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
