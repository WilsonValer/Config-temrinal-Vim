# Config-temrinal-Vim
### primer paso
+ crear un editor: vim .vimrc
### segundo paso
+ dentro de tu editor copiar todo el texto del file configVim.
### tercer paso
+ revisa que los textos esten completos, y que no tengas espacios en blanco.
+ guarda los cambios y vuelve a abrir un editor y empieza a codear.

## instalacion de plugin para vim
### instalando colorscheme
+ ingresamos a este link para escoger el tema para vim
https://vimcolorschemes.com/

les enseñare como lo realize a mi manera, existen muchas formas de hacerlo
claro esta algunos lo hacen con plugins y otros configurando el .vimrc

+ clonamos el repositorio del tema que elejimos, todos las repos tienen entre
sus archivos algo que dice colores, esto es lo que importa.

+ Si está utilizando Vim, clone el repositorio en formato ~/.vim/colors. Si usa Neovim,
clone el repositorio en formato ~/.config/nvim/colors.
+ Ingrese al repositorio clonado y encontrará un directorio llamado 'colores'.
+ Ejecutar mv colors/*.vim ../(esto moverá todos los color-scheme-name.vimarchivos
a ~ /.vim/colors/o a ~/.config/nvim/colors/, dependiendo de si es Vim o Neovim.
+ Agregue la línea colorscheme <color-scheme-name>a su 'vimrc'.
