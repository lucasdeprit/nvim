# Nvim for Windows

My personal nvim configuration for windows:

![nvim Image](https://github.com/lucasdeprit/nvim/blob/windows/Images/Front.png)

Instrucciones Vim:

- Instalar chocolately y git en el pc
- Instalar nvim con chocolately
- Entrar a usuario/tuusuario/AppData/local
- Clonar el repositorio en esta localizacion

Instalar vim-Plug

iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force

- ejecutar :PlugInstall para instalar todos los plugins de vim

- instalar node.js

- ejecutar :checkhealth e ir solucionando todos los warnings que nos aparezcan (el de python no lo he sabido solucionar)

- ejecutar :cocInstall para instalar todos los plugins de coc
