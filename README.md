# Antwerpen - a color theme for VS Code

![Bike license plates from Antwerpen](https://i.imgur.com/QO8384T.jpg)

Antwerpen is a lukewarm *dark theme* for VS Code. So far I've used it with
Python, JS(X), HTML and CSS/LESS, so other syntaxes might be a bit wonky.

## Installation

The documentation suggest the theme files should be placed under
`.vscode/extensions`. At least for me on Ubuntu WSL this was actually
`~/.vscode-server/extensions`. YMMV.

When the files are in place, the theme can be selected normally via VS Code
(`ctrl-k, ctrl-t`).

## Samples

### Python

![Python syntax highlighting (courtesy of Django project)](https://i.imgur.com/BvuOwCQ.png)  

*Python syntax highlighting (courtesy of Django project)*

### JSX

![JSX syntax highlighting (courtesy of Mattermost project)](https://i.imgur.com/Idvlbxr.png)  

*JSX syntax highlighting (courtesy of Mattermost project)*

### HTML/Django template

![HTML/Django template (courtesy of Django project)](https://i.imgur.com/uN9RAHW.png)  

*HTML/Django template (courtesy of Django project)*

### CSS

![CSS (courtesy of VS Code project by Microsoft)](https://i.imgur.com/yY5b95w.png)  

*CSS (courtesy of VS Code project by Microsoft)*

## Known issues

These issues can't currently be fixed, at least without inadversely affecting
highlighting in some other part or syntax.

* Some CSS properties such and `font` and `cursor` get incorrectly highlighted
  as selectors
* Inner and outer curly brackets around Django template variables are
  incorrectly rendered with different colors
