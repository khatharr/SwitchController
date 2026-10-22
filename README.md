# 🕹️ SwitchController  
> Remotely control a Nintendo Switch from your computer, just as you would with a physical controller, and view the Switch screen in real time.  
<img width="882" height="412" alt="image" src="https://github.com/user-attachments/assets/1c936579-d829-46fc-af9f-02c5400e2b2a" />

<img width="880" height="411" alt="image" src="https://github.com/user-attachments/assets/b9695559-3e4b-46b9-b3c9-5a22fcff1713" />

<img width="883" height="413" alt="image" src="https://github.com/user-attachments/assets/3740edcb-d065-4623-b77d-6d1298e1894b" />

---

## 📖 Project Overview
**SwitchController** is a remote-control and automation tool based on Sys-BotBase.  
With this application, you can:
- Control your Switch directly from a computer by emulating Joy-Con inputs;
- View the Switch screen in real time;
- Automate tasks (such as macros);
- Combine controls and screen viewing in one interface, making remote Switch management convenient for players and developers.

---

## ⚙️ Main Features
- 🎮 Emulate Joy-Con inputs (A/B/X/Y, analog sticks, touch input, etc.) ✅
- 📺 View the Switch screen in real time ✅
- 🔁 Task scripting (automation) ❌
- 🧩 Control the console over a network without a physical controller ✅

---

## 🧱 How It Works
This project relies on **Sys-BotBase**, a background service that runs on a modded Nintendo Switch
and accepts commands over a network connection (such as button inputs and memory operations).

> ⚠️ Note: The Switch must be running `Sys-BotBase`, and the Switch and computer must be on the same local network.

---

## 🖥️ How to Use
### 1️⃣ Prepare Your Setup
- A Nintendo Switch with **Sys-BotBase** installed;
- A computer on the same network as the Switch;
- Install [.NET 9.0+](https://dotnet.microsoft.com/download/dotnet);
- Download or build this project's executable.

### 2️⃣ Start Sys-BotBase
For detailed instructions, see [sys-botbase](https://github.com/olliz0r/sys-botbase).

### 3️⃣ Connect and Control
1. Open SwitchController;
2. Enter the Switch's IP address. The default port is 6000;
3. Click "Connect";
4. The Switch screen can then be viewed in real time within the application;
5. Use your mouse to interact with the controls.

---

## ⚠️ Notes / Disclaimer
- This project is intended for **personal research, learning, and homebrew software development**;
- Do not use it in ways that violate Nintendo's terms of use or online service rules;
- Users accept responsibility for any risk of device damage or account bans resulting from use of this project;
- This project is not affiliated with Nintendo.

---

## ⭐ Support the Project
If you find this project useful, you're welcome to:
- Star ⭐ the repository;
- Submit issues or pull requests to help improve it;
- Share it with other developers who want to control a Switch remotely.

---

> "Bringing control and freedom together, just like using a real controller."


## 🪪 License / Licensing Notice

**SwitchController** is released as open-source software under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

You may:
- ✅ Use, modify, and redistribute this project freely;
- ✅ Use it for research, teaching, and other noncommercial or commercial purposes, subject to GPLv3;
- ⚠️ When distributing derivative works, **retain the GPLv3 license** and preserve copyright and attribution notices.

---

### 🔗 Included Upstream Projects
This project builds on the following open-source projects:

| Dependency | Author | License |
|-----------|------|------|
| [Sys-BotBase](https://github.com/olliz0r/sys-botbase) | olliz0r | GPL-3.0 |
| [SysBot.Base](https://github.com/kwsch/SysBot.NET) | kwsch | MIT |
| SwitchController | ZiYuKing | GPL-3.0 |

Because this project directly depends on and links against Sys-BotBase (GPLv3),  
the project as a whole is distributed under GPLv3.

📄 **See [LICENSE](LICENSE) for the full license text.**
