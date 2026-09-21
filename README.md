# Awesome VSCode Extensions & IntelliJ Plugins

A curated list of the best extensions for **Visual Studio Code** and plugins for **IntelliJ IDEA** (and other JetBrains IDEs), hand-picked from 2026 community rankings, marketplace install counts, and developer setups.

All entries are categorized so you can grab only what you need. Keep your editor lightweight — install in small batches, not everything at once.

---

## Table of Contents

- [Visual Studio Code](#visual-studio-code)
  - [AI & Code Assistants](#vscode-ai--code-assistants)
  - [Code Quality & Formatting](#vscode-code-quality--formatting)
  - [Git & Version Control](#vscode-git--version-control)
  - [API Testing & HTTP](#vscode-api-testing--http)
  - [Debugging](#vscode-debugging)
  - [Containers & Remote Development](#vscode-containers--remote-development)
  - [Frontend & Web Development](#vscode-frontend--web-development)
  - [Language Packs](#vscode-language-packs)
  - [Productivity](#vscode-productivity)
  - [Collaboration](#vscode-collaboration)
  - [UI, Themes & Icons](#vscode-ui-themes--icons)
  - [Markdown & Docs](#vscode-markdown--docs)
  - [Database Clients](#vscode-database-clients)
- [IntelliJ IDEA Plugins](#intellij-idea-plugins)
  - [AI & Code Assistants](#intellij-ai--code-assistants)
  - [Code Quality & Static Analysis](#intellij-code-quality--static-analysis)
  - [Navigation & Editing Productivity](#intellij-navigation--editing-productivity)
  - [Git & Version Control](#intellij-git--version-control)
  - [Java & Spring Ecosystem](#intellij-java--spring-ecosystem)
  - [Frontend & Web](#intellij-frontend--web)
  - [Testing & API Tools](#intellij-testing--api-tools)
  - [Remote & Collaboration](#intellij-remote--collaboration)
  - [Documentation & Translation](#intellij-documentation--translation)
  - [UI, Themes & Fun](#intellij-ui-themes--fun)
- [Installation](#installation)
- [Troubleshooting & Tips](#troubleshooting--tips)

---

## Visual Studio Code

> Extension IDs are shown so you can install via `code --install-extension <publisher.name>` or the Marketplace search bar.

### VS Code — AI & Code Assistants

| Extension | ID | Why you want it |
| --- | --- | --- |
| [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) | `GitHub.copilot` | The default AI pair programmer — inline completions, chat, test generation. ~78M installs. |
| [Claude Code for VS Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code) | `anthropic.claude-code` | Full-file edits, refactors and agentic workflows from Anthropic. Fastest-growing AI extension of 2026. |
| [Codex (OpenAI)](https://marketplace.visualstudio.com/items?itemName=openai.chatgpt) | `openai.chatgpt` | OpenAI's coding agent, included in ChatGPT plans. |
| [Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) | `TabNine.tabnine-vscode` | Privacy-focused AI completions with a generous free tier. |
| [Continue](https://marketplace.visualstudio.com/items?itemName=Continue.continue) | `Continue.continue` | Open-source AI assistant; bring your own model (Ollama, OpenAI, etc.). |
| [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) | `saoudrizwan.claude-dev` | Autonomous coding agent that plans and edits files in the editor. |
| [Roo Code](https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline) | `RooVeterinaryInc.roo-cline` | A whole "dev team" of AI agents inside your editor. |

### VS Code — Code Quality & Formatting

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | `esbenp.prettier-vscode` | Opinionated formatter for JS/TS/HTML/CSS/JSON/Markdown. Format-on-save kills formatting debates. **The #1 install.** |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | `dbaeumer.vscode-eslint` | Lint JS/TS in real time, catch bugs before you run anything. |
| [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) | `usernamehw.errorlens` | Prints errors/warnings inline at the end of the line — the highest-leverage debugging extension. |
| [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome) | `biomejs.biome` | Fast all-in-one linter + formatter that replaces ESLint + Prettier for JS/TS projects. |
| [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff) | `charliermarsh.ruff` | Fast Python linter + formatter. |
| [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) | `streetsidesoftware.code-spell-checker` | Catches typos in comments, strings, and identifiers. |
| [SonarQube / SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode) | `SonarSource.sonarlint-vscode` | Squiggles code-smells and security issues before you commit. |
| [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) | `EditorConfig.EditorConfig` | Enforces consistent editor settings across a team via `.editorconfig`. |

### VS Code — Git & Version Control

| Extension | ID | Why you want it |
| --- | --- | --- |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | `eamodio.gitlens` | Blame annotations, file history, branch compare, commit graph — Git superpowers in-editor. |
| [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) | `mhutchie.git-graph` | Beautiful interactive commit graph in a view. |
| [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) | `donjayamanne.githistory` | View file/branch/line history and compare commits. |
| [Conventional Commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits) | `vivaxy.vscode-conventional-commits` | Enforces conventional commit message format. |

### VS Code — API Testing & HTTP

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client) | `rangav.vscode-thunder-client` | Lightweight Postman alternative — REST/GraphQL testing, collections, environments. |
| [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) | `humao.rest-client` | Send HTTP requests straight from `.http` files you can commit and share. |

### VS Code — Debugging

| Extension | ID | Why you want it |
| --- | --- | --- |
| [JavaScript Debugger](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug) | `ms-vscode.js-debug` | Built-in Node + Chrome debugger (usually bundled, but verify it's enabled). |
| [Chrome DevTools](https://marketplace.visualstudio.com/items?itemName=ms-edgedevtools.vscode-edge-devtools) | `ms-edgedevtools.vscode-edge-devtools` | Inspect DOM, network and console for frontend debugging. |
| [Playwright Test](https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright) | `ms-playwright.playwright` | Run/debug E2E tests, record tests, and pick locators in-editor. |

### VS Code — Containers & Remote Development

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) | `ms-azuretools.vscode-docker` | Build, run, and manage containers/images/volumes from the sidebar. |
| [Remote Development Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) | `ms-vscode-remote.vscode-remote-extensionpack` | One-click install for Remote - SSH, Containers (Dev Containers), and WSL. Turns VS Code into a full remote IDE. |
| [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) | `ms-vscode-remote.remote-containers` | Develop inside a Docker container with full IntelliSense. |
| [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) | `ms-vscode-remote.remote-ssh` | Edit code on any SSH server as if it were local. |

### VS Code — Frontend & Web Development

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) | `ritwickdey.LiveServer` | Instant local server with live reload for static HTML/CSS/JS. |
| [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) | `bradlc.vscode-tailwindcss` | Autocomplete, hover previews, and linting for Tailwind classes. |
| [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) | `formulahendry.auto-rename-tag` | Renames paired opening/closing HTML tags together. |
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | `christian-kohler.path-intellisense` | Autocomplete file paths in imports and strings. |
| [ES7+ React/Redux Snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | `dsznajder.es7-react-js-snippets` | Fast React snippets (rafce, rfc, etc.). |
| [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) | `glenn2223.live-sass` | Compiles SCSS/Sass to CSS on save (for projects without a build tool). |

### VS Code — Language Packs

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) | `ms-python.python` | IntelliSense, debugging, linting, and Jupyter for Python. |
| [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) | `vscjava.vscode-java-pack` | Full Java support: debugger, test runner, Maven/Gradle, project manager. |
| [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go) | `golang.Go` | Official Go language support. |
| [Rust](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) | `rust-lang.rust-analyzer` | Official Rust language server with great IntelliSense. |
| [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) | `ms-dotnettools.csdevkit` | Project-level .NET tooling: debugging, testing, and solution management. |
| [ESLint/Prettier for TS bundling] | — | Pair the quality tools above with any TypeScript workload. |

### VS Code — Productivity

| Extension | ID | Why you want it |
| --- | --- | --- |
| [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) | `oderwat.indent-rainbow` | Colorizes indentation levels — spot misaligned code instantly. |
| [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) | `wayou.vscode-todo-highlight` | Surfaces TODO/FIXME comments so they can't be forgotten. |
| [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | `alefragnani.project-manager` | Save, switch, and search projects fast. |
| [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) | `mikestead.dotenv` | Syntax highlighting for `.env` files. |
| [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) | `adpyke.codesnap` | Beautiful syntax-highlighted screenshots for docs, articles, blog posts. |
| [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) | `johnpapa.vscode-peacock` | Color-code your VS Code window per project — never edit the wrong project again. |
| [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | `alefragnani.Bookmarks` | Jump between marked lines across files. |

### VS Code — Collaboration

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) | `MS-vsliveshare.vsliveshare` | Real-time pair programming: shared code, terminal, and debugging sessions. |
| [GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) | `vsls-contrib.gistfs` | Tame Gists/notes right in the editor. |

### VS Code — UI, Themes & Icons

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | `PKief.material-icon-theme` | The de-facto file icon pack (~18M installs). |
| [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) | `zhuangtongfa.Material-theme` | Most popular color theme, easy on the eyes. |
| [Catppuccin](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc) | `Catppuccin.catppuccin-vsc` | Trendy pastel theme family (Latte/Mocha/Frappe/Macchiato). |
| [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night) | `enkia.tokyo-night` | Clean, high-contrast dark theme. |

### VS Code — Markdown & Docs

| Extension | ID | Why you want it |
| --- | --- | --- |
| [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) | `yzhang.markdown-all-in-one` | Live preview, TOC, list editing, keyboard shortcuts, and more. |
| [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) | `DavidAnson.vscode-markdownlint` | Lints Markdown for consistent style and broken structure. |

### VS Code — Database Clients

| Extension | ID | Why you want it |
| --- | --- | --- |
| [PostgreSQL](https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-postgresql) | `ms-ossdata.vscode-postgresql` | Microsoft's Postgres explorer with IntelliSense and query tools. |
| [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) | `mtxr.sqltools` | Universal SQL client for multiple dialects + a driver marketplace. |
| [MongoDB](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode) | `mongodb.mongodb-vscode` | Query and visualize MongoDB directly from VS Code. |

---

## IntelliJ IDEA Plugins

> Most plugins work across all JetBrains IDEs (PyCharm, WebStorm, GoLand, Android Studio, CLion, etc.). Install via *Settings → Plugins → Marketplace* or the [JetBrains Marketplace](https://plugins.jetbrains.com).

### IntelliJ — AI & Code Assistants

| Plugin | Why you want it |
| --- | --- |
| [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot) | AI completions and chat with GitHub account sign-in. |
| [JetBrains AI Assistant](https://plugins.jetbrains.com/plugin/22282-jetbrains-ai-assistant) | JetBrains-native AI, tightly integrated with refactorings and chat. |
| [Junie](https://plugins.jetbrains.com/plugin/25331-junie) | JetBrains' agentic AI coding agent. |
| [Continue](https://plugins.jetbrains.com/plugin/22707-continue) | Open-source copilot; any model, any provider. |
| [AI Commits (Blarc)](https://plugins.jetbrains.com/plugin/22176-ai-commits) | Generates conventional commit messages from your diff. |
| [ProxyAI](https://github.com/carlrobertoh/ProxyAI) | Leading open-source AI copilot for JetBrains supporting many models. |

### IntelliJ — Code Quality & Static Analysis

| Plugin | Why you want it |
| --- | --- |
| [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint) | Squiggles quality and security issues before you commit. |
| [Qodana](https://plugins.jetbrains.com/plugin/20575-qodana) | JetBrains' quality gate with cloud/CI integration. |
| [CheckStyle-IDEA](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea) | Checkstyle support with live inspection. |
| [Error Prone Compiler](https://plugins.jetbrains.com/plugin/7343-error-prone-compiler) | Helps the compiler catch more Java bugs via Error Prone. |
| [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore) | Enhanced `.gitignore` editing with per-VCS templates (Git, SVN, Mercurial...). |
| [detekt](https://plugins.jetbrains.com/plugin/10761-detekt) | Static analysis for Kotlin. |

### IntelliJ — Navigation & Editing Productivity

| Plugin | Why you want it |
| --- | --- |
| [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump) | Jump anywhere in a file with a single character search (Vim-EasyMotion style). |
| [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x) | Teaches you keyboard shortcuts every time you click a button. |
| [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) | Colors nested brackets to make code structure obvious. |
| [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation) | Case conversion, escaping, sorting, regex replace — a text Swiss army knife. |
| [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro) | VS Code-style minimap on the right side of the editor. |
| [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim) | Full Vim emulation (add IdeaVim-EasyMotion and IdeaVim-Quickscope for extras). |
| [Presentation Assistant](https://plugins.jetbrains.com/plugin/7345-presentation-assistant) | Shows popups of shortcuts for the actions you trigger — perfect for demos. |
| [Edit Tabs Location](https://plugins.jetbrains.com/plugin/19373-edit-tabs-location) | One-click tab layout presets (top row, vertical tabs, sorted, cleanup). |

### IntelliJ — Git & Version Control

| Plugin | Why you want it |
| --- | --- |
| [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox) | Status bar branch info, blame, auto-fetch, commit notifications. |
| [.gitignore generator] | Use **.ignore** above, or the bundled **.gitignore** plugin. |
| [Git Flow Integration](https://plugins.jetbrains.com/plugin/7315-git-flow-integration) | Git Flow branch model operations from the IDE. |
| [OpenAI commit message] | See **[AI Commits (Blarc)](#intellij--ai--code-assistants)** for automated commit messages. |

### IntelliJ — Java & Spring Ecosystem

| Plugin | Why you want it |
| --- | --- |
| [Spring Assistant](https://plugins.jetbrains.com/plugin/10229-spring-assistant) | Enhanced Spring configuration metadata, properties, and YAML assistance. |
| [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy) | Entity generation, migrations, and JPA/Hibernate productivity suite. |
| [GenerateAllSetter](https://plugins.jetbrains.com/plugin/9360-generateallsetter) | One-shot generation of all setters / getters / builders for an object. |
| [Lombok](https://plugins.jetbrains.com/plugin/6317-lombok) | Bundled in recent IDEA but keep it enabled for older versions. |
| [MyBatisX](https://plugins.jetbrains.com/plugin/10119-mybatisx) | Jump from Mapper interface to XML; **MyBatis Log Plugin** prints colored SQL with bound parameters. |
| [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration) | Render UML diagrams directly in the IDE. |

### IntelliJ — Frontend & Web

| Plugin | Why you want it |
| --- | --- |
| [Prettier](https://plugins.jetbrains.com/plugin/10456-prettier) | Format on save for JS/TS/HTML/CSS/JSON/Markdown. |
| [ESLint](https://plugins.jetbrains.com/plugin/7494-eslint) | Real-time linting for JS/TS projects. |
| [LiveEdit](https://plugins.jetbrains.com/plugin/946-liveedit) | Live reload for HTML/CSS/JS during debugging. |
| [Emmet Everywhere](https://plugins.jetbrains.com/plugin/16190-emmet-everywhere) | Emmet completion for non-HTML languages. |

### IntelliJ — Testing & API Tools

| Plugin | Why you want it |
| --- | --- |
| [RestfulTool](https://plugins.jetbrains.com/plugin/14218-restfultool) | Browse and invoke RESTful endpoints from the sidebar. |
| [HTTP Client (bundled)](https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html) | Built-in `.http` files — send requests without leaving the IDE. |
| [Gherkin](https://plugins.jetbrains.com/plugin/9164-gherkin) | Cucumber/Gherkin support with step navigation. |
| [LeetCode Editor](https://github.com/shuzijun/leetcode-editor) | Solve LeetCode problems in the IDE and sync to LeetCode. |

### IntelliJ — Remote & Collaboration

| Plugin | Why you want it |
| --- | --- |
| [Code With Me](https://plugins.jetbrains.com/plugin/14896-code-with-me) | Real-time collaborative editing, voice/video, and remote pairing. |
| [Remote Development Gateway](https://plugins.jetbrains.com/plugin/22373-remote-development-gateway) | Official JetBrains Remote Development — run the IDE backend on a server. |
| [Docker](https://plugins.jetbrains.com/plugin/7724-docker) | Build/run/manage containers from the IDE (bundled on Ultimate). |

### IntelliJ — Documentation & Translation

| Plugin | Why you want it |
| --- | --- |
| [Translation (YiiGuxing)](https://plugins.jetbrains.com/plugin/8579-translation) | In-editor translation of identifiers, docs, and selections (~12K GitHub stars). |
| [Mintlify Doc Writer](https://plugins.jetbrains.com/plugin/18638-mintlify-doc-writer) | AI-generated docstrings for the selected function. |

### IntelliJ — UI, Themes & Fun

| Plugin | Why you want it |
| --- | --- |
| [Material Theme UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) | Material Design icons, color schemes, and UI polish. |
| [Catppuccin Theme](https://plugins.jetbrains.com/plugin/25656-catppuccin-theme) | Pastel theme family with matching UI. |
| [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar) | Replaces the Progress bar with a Nyan cat animation. |
| [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii) | Particles and sparks while you type (use low intensity to avoid distraction). |

---

## Installation

**VS Code** — from the terminal:
```bash
code --install-extension esbenp.prettier-vscode
code --install-extension eamodio.gitlens
code --install-extension usernamehw.errorlens
```

**IntelliJ IDEA** — `Settings → Plugins → Marketplace`, search the plugin name, and click **Install**. For bulk installs, use the **Settings Sync** feature or JetBrains Toolbox profiles.

---

## Troubleshooting & Tips

- **Don't install everything.** Five great extensions beat twenty okay ones — an overloaded editor slows startup and indexing.
- **Avoid conflicting duplicates.** Run only one of: Biome vs ESLint+Prettier; one icon theme; one AI completion engine at a time.
- **Enable format-on-save once:** in VS Code set `"editor.formatOnSave": true` and set Prettier as the default formatter per language.
- **Monitor resource usage:** JetBrains users can check `Help → Diagnostic Tools → Profile IDE`; disable anything you don't reach for.
- **Rebuild after big upgrades:** occasionally disable everything, then re-enable only what you actually use (the "yearly cleanup" method).
- **Local-first requests:** `.http` files (REST Client / HTTP Client) are versionable and reviewable alongside your code — a nice alternative to separate API apps.

---

## Contributing

PRs and issues are welcome. The list is intentionally curated — new entries should be genuinely notable (high installs, unique value, or strong community traction).