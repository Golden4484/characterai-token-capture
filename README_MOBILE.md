# Character.AI Token Capture & Integration Tools (Mobile)

[Readme Desktop](./README.md)

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

Character.AI doesn’t provide an official API, so grabbing your authentication token for unofficial tools is tricky — especially on mobile. This userscript and guide simplify token capture when you activate Voice Enabled Mode inside chats.

---

## How to Use (Mobile)

### 1. Install Kiwi Browser

- Download [**Kiwi Browser**](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser), a Chromium-based mobile browser that supports user scripts and extensions.

### 2. Install Userscript Manager Extension

- In Kiwi Browser, install [**ViolentMonkey**](https://violentmonkey.github.io/) or [**Tampermonkey**](https://www.tampermonkey.net/).

### 3. Install the Token Capture Userscript

- Install the userscript from [GreasyFork](https://greasyfork.org/en/scripts/545327-character-token) via ViolentMonkey or Tampermonkey in Kiwi.

### 4. Capture Your Token

1. Open [Character.AI](https://character.ai) and log in on your mobile browser.  
2. Start a chat with any AI character.  
3. Tap the **"Activate Voice Enabled Mode"** button next to the chat's "..." settings menu.  
4. The token modal will appear — copy your token.  
5. Reload the page to capture again if needed.

---

## Usage & Related Projects

You can use the captured token with popular unofficial Character.AI libraries such as:

- [node_characterai by realcoloride](https://github.com/realcoloride/node_characterai)  
- [PyCharacterAI by Xtr4F](https://github.com/Xtr4F/PyCharacterAI)

Check these repos for integration and bot-building examples.

---

## Screenshots & Examples

<!--  
Add mobile screenshots or GIFs demonstrating:  
- Installing Kiwi Browser and ViolentMonkey/Tampermonkey  
- Activating Voice Enabled Mode  
- Token modal popup

Example markdown image syntax:  
![Mobile Example](./images/mobile-example.png)  
-->

---

## Contributing

Open to improvements, bug reports, feature requests, and external contributions.  
Feel free to open issues or pull requests — let’s improve this tool together.

---

## License

For educational and research purposes only. No warranties provided.

---

*Created by Golden4484 — Use responsibly and don’t be that guy.*
