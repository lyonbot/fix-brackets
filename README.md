# Fix Brackets

<div align="center">

<img src="./images/icon.png" width="96" height="96">

⚔️ The VS Code extension that helps you fight against brackets!

[💾 Install on VSCode](https://marketplace.visualstudio.com/items?itemName=lyonbot.fix-brackets) - [💬 Feedback](https://github.com/lyonbot/fix-brackets/issues)

</div>

## Features

- **💫 Magical Brackets 💫**

  - typing `]` `)` `}` and auto activate this mode - can be disabled in settings
  - **move** them with `Cmd+↓` `Cmd+↑` or `Cmd+←` `Cmd+→`
  - _tips:_ use `Cmd+G` to switch any open / closing bracket into magical mode

  ![](./images/magical-bracket.gif)

- **🔥 Complete Brackets 🔥**

  - **at end of line**, use `Cmd+Right` to complete brackets
  - works on new lines too

  ![](./images/complete-bracket.gif)

## Extension Settings

## Known Issues

- The bracket matching algorithm is not perfect, so it might not work in some cases (eg. some JSX and HTML case)

- The completing algorithm is based on **indent**, I hope you have a decent code formatting.

- The parser is language-irrelative, so it doesn't complete `,` or `;` for you.

## Release Notes

### 0.1.0

Initial release of fix-brackets

- **💫 Magical Closing Brackets 💫**

  - auto enter that mode when typing `]` `)` `}` - can be disabled in settings
  - move them with `Cmd+Arrow`
  - use `Cmd+G` to toggle that mode on any closing bracket

- **🔥 Complete Brackets 🔥**

  - **at end of line**, use `Cmd+Right` to complete brackets
  - different behavior on empty / non-empty lines
