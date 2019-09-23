# O que é

Um tuto de comandos garimpados da internet para deixar o workspace do Gnome horizontal.

# Motivação

Workspace vertical e dinâmico é doença.

# Passos de instalação

* Instalando o shell extension

```
$ sudo apt-get install chrome-gnome-shell
```

https://chrome.google.com/webstore/detail/gnome-shell-integration/gphhapmejobijbbhgpjhcjognlahblep?hl=pt-BR

* Instalando a Workspace Matrix

https://extensions.gnome.org/extension/1485/workspace-matrix/

Ir em configurações e trocar o número de colunas para X.

* Trocando os shortcuts (no meu caso eu gosto do `Elementary` então)

```
$ gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-right  "['<Super>Right']"
```

```
$ gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-left  "['<Super>Left']"
```

```
$ gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-left  "['<Super><Alt>Left']"
```

```
$ gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-right   "['<Super><Alt>Right']"
```

*  Trocar os shortcuts do sistema no sistema mesmo para algo escroto, tipo `Ctrl+Alt+W` onde há tem o `Super+Right`
