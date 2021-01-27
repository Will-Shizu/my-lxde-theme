# Meu tema LXDE

![Print](https://github.com/Will-Shizu/my-lxde-theme/blob/main/print.png)

## Main Theme
Como tema principal eu utilizei o Dracula blue, uma versão mdificada do tema drácula.

### Download:

`git clone https://github.com/Michedev/Ant-Dracula-Blue.git`

[Acessar GitHub](https://github.com/Michedev/Ant-Dracula-Blue)


## Open box theme
Eu usei o tema dracula open box sem borda no geranciador de janelas Open Box.

### Download:

`git clone https://github.com/the-zero885/dracula-Openbox`

[Acessar GitHub](https://github.com/the-zero885/dracula-Openbox)


## Icons
Como pacote de icones eu utilizei o Papirus Dark que funcionou melhor o tema principal.

### Instalar:
```
sudo add-apt-repository ppa:papirus/papirus
sudo apt-get update
sudo apt-get install papirus-icon-theme
```

[Acessar GitHub](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)


## Cursor
Para o cursor eu utilizei o tema Beeze.

### Instalar:

`sudo apt-get install -y breeze-cursor-theme`


## Dockbar
Utilizei plank com o tema do Deepin, especificamente o Large Black. O compositor utilizado foi o xcompmgr.

### Instalar plank:

`sudo apt install plank`


### Instalar compositor:

`sudo apt install xcompmgr`

[Acessar página de download do tema](https://www.gnome-look.org/p/1333368/)


## Font
A fonte utilizada foi a DejaVu Sans, com 10pt de tamanho, mas somente por motivos de compatibilidade, isso pode ser mudado depois.

[Ver fonte](https://www.fontsquirrel.com/fonts/dejavu-sans)


## Menu Icon e Wallpaper
O ícone do menu eu mesmo personalizei, etão a imagem usada vai estar disponível nos arquivos do repositório, bem como os wallpapers utilizados.


## Sublime theme
O tema que eu utilizei no meu editor de código foi o Ayu darker, muito lindo. Para habilitar ele é só pressionar `CTRL`+`SHIFT`+`p` e digitar "Install packages", lá é só pesquisar e instalar o Ayu Theme.

Para ativar o tema, novamente pressione `CTRL`+`SHIFT`+`p` e pesquise por "ayu", selecione "activate theme" e está feito.

[Acessar GitHub](https://github.com/dempfi/ayu)


## Terminal
Para o terminal eu utilizei LXTerminal o zsh com o tema bira.

### Intalar ZSH:

`sudo apt install zsh`

Para habilitar o zsh veja [esse artigo](https://diolinux.com.br/linux/alterar-o-terminal-padrao-bash-zsh.html);

### Instalar temas ZSH:

`sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

[Mais infomações](https://github.com/ohmyzsh/ohmyzsh)

Para trocar de tema é só editar o arquivo `.zshrc` na linha onde ele declara o tema, no caso, substitua por "bira". Em todo caso vou deixar o arquivo `.zshrc` e `.bashrc` no repositório.