# 🗂️ Multi Tab Opener

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21,9,2&height=210&section=header&text=Multi%20Tab%20Opener&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Open%20Dozens%20of%20Tabs%20in%20One%20Click&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.5.0-F77F00?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Chrome](https://img.shields.io/badge/Chrome%20%7C%20Firefox%20%7C%20Edge-FCBF49?style=for-the-badge&logo=googlechrome&logoColor=black)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-D62828?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

<br/>

### ⚡ A browser extension that opens multiple URLs at once — with a single click

*📋 Paste List • 🎯 Filter & Sort • ⏱️ Smart Delays • 💾 Save Presets*

<br/>

<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/📥_ADD_TO_BROWSER-F77F00?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=C46500" alt="Add to Browser" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/🚀_TRY_IT- FCBF49?style=for-the-badge&logo=rocket&logoColor=black&labelColor=CC9A3A" alt="Try It" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/📚_DOCS-D62828?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=A81F1F" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="800" alt="unnamed (5)" src="https://github.com/user-attachments/assets/8b6e78c4-2d82-4eed-b51b-1e208e889969" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Multi Tab Opener** is a simple but incredibly useful browser extension that lets you open **dozens — or hundreds — of URLs at once**. Just paste a list, hit "Open", and watch your tabs appear in the right order, with the right timing, every time.

Whether you're researching a topic, comparing products, or launching your daily work set — stop clicking links one by one.

> 💡 **Perfect for:** Researchers, developers, SEO specialists, online shoppers, and anyone who works with link lists daily.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 📋 **Paste List** | 🚀 **One-Click Open** | ⏱️ **Smart Delays** |
|:---:|:---:|:---:|
| Paste any list of<br/>URLs instantly | Launch all tabs<br/>with one button | Avoid tab-overload<br/>with configurable delays |

| 💾 **Save Presets** | 🎯 **Filter & Sort** | 🔒 **Fully Local** |
|:---:|:---:|:---:|
| Store frequently<br/>used link sets | Remove duplicates,<br/>sort by domain | No servers, no<br/>tracking, no accounts |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Extension

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Blazing Fast** | Opens 100 tabs in under 3 seconds with smart batching |
| 🧠 **Smart Deduplication** | Automatically skips duplicate URLs so you never open the same page twice |
| 🎨 **Beautiful UI** | Clean, intuitive interface — no clutter, no confusion |
| 💾 **Presets & History** | Save your favorite sets of links and re-launch them anytime |
| 🛡️ **Privacy First** | Runs entirely in your browser — no data ever leaves your device |
| 🌐 **Universal** | Works in Chrome, Firefox, and Edge with native performance |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Extension Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🗂️  Multi Tab Opener  v2.5.0                    ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  📋 Paste URLs (one per line):                   ║
║  ┌────────────────────────────────────────────┐  ║
║  │ https://github.com/trending                │  ║
║  │ https://news.ycombinator.com               │  ║
║  │ https://developer.mozilla.org              │  ║
║  │ https://stackoverflow.com                  │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  ⚙️ Delay between tabs:  [ 200ms ▾ ]             ║
║  🔀 Shuffle order:       [ OFF ]                 ║
║                                                  ║
║  [ 🚀 OPEN 4 TABS ]   [ 💾 Save as Preset ]      ║
║                                                  ║
║  ✅ 4 tabs opened in 0.8s                        ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🗂️ multi-tab-opener/
├── 🎨 popup/                  # Extension popup UI
│   ├── popup.html
│   ├── popup.css
│   └── popup.js
├── ⚙️  background/            # Tab-opening engine
│   ├── tab-manager.js
│   └── delay-queue.js
├── 💾 storage/                # Presets & history
├── 🎯 utils/                  # URL parsing & dedup
├── 🧪 tests/                  # Unit & e2e tests
└── 📖 docs/                   # Usage & tips
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chrome APIs](https://img.shields.io/badge/Chrome_APIs-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![WebExtensions](https://img.shields.io/badge/WebExtensions-000000?style=for-the-badge&logo=firefoxbrowser&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Have a feature idea? Want a new preset?

<div align="center">

<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-F77F00?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/o81mP4Tq28SyIlEWw">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-D62828?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🗂️ Made with ⚡ by the Multi Tab Opener Team

*If this extension saved you clicks — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21,9,2&height=120&section=footer" width="100%"/>

</div>
