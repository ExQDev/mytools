# Мій Minimal-TOP-2022 інструментів для зручної роботи з Node у VS Code:

## 1. VSCode:

  Themes:

  ```json
  "workbench.colorTheme": "Community Material Theme Palenight High Contrast"
  ```

  Plugins(ids):

  + Equinusocio.vsc-community-material-theme
  + ms-azuretools.vscode-docker - для докеру
  + dbaeumer.vscode-eslint - для дотримання codestyle
  + esbenp.prettier-vscode - для того що й вище (працює разом з ним)
  + waderyan.gitblame - дозволяє підглядати хто який рядок написав через git прямо у редакторі
  + huizhou.githd - для перегляду історії змін git
  + eamodio.gitlens - потужний інструмент для управління git
  + zyrong.node-modules - для зручної навігації по модулям
  + TabNine.tabnine-vscode - дуже потужний ассистент, який навчається на проекті та може пропонувати в автодоповненні саме те, що тобі потрібно
  + Gruntfuggly.todo-tree - щоб не губити свої "// TODO:" в проекті - підсвічує і систематизує

  
## 2. Native tools:

  - [volta](https://volta.sh/) - це як nvm, тільки краще. Дозволяє прикріпити на кожен проект власну версію node та yarn.
  - [thefuck](https://github.com/nvbn/thefuck) - з ним не прийдеться переписувати весь рядок якщо помилився буквою коли писав git commit... А також це швидке рішення коли не встановлено origin при push. Доречі, працює не тільки з гітом.
  - [zsh](https://www.zsh.org/) - дуже потужна оболонка для тірміналу, рекомендую замість `bash`
  - [powerlevel10k](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k) - дуже потужна тема для zsh, інформативна, налаштовувана
  - [OhMyZSH](https://ohmyz.sh) - інструмент для зручного налаштування zsh
  - [Neutralino.js](https://neutralino.js.org/) - фреймворк для перетворення веб-додатків у стацінарні
  - [Turbo](https://turbo.build/) - інструмент інкрементальної компіляції, набагато пришвидшує білд
  - [Cross-env](https://www.npmjs.com/package/cross-env) - інструмент для кроссплатформенного використання аргументів середовища
  

## 3. Підказки:

  - Якщо можливо, не використовуйте деструктуризацію у імпортах. Це збільшує розмір збірки і сповільнює роботу додатку.
