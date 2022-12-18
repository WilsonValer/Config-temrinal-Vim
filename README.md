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

+ Si está utilizando Vim, clone el repositorio en formato `~/.vim/colors`. Si usa Neovim,
clone el repositorio en formato `~/.config/nvim/colors.`
+ Ingrese al repositorio clonado y encontrará un directorio llamado 'colores'.
+ Ejecutar `mv colors/*.vim ../` (esto moverá todos los color-scheme-name.vimarchivos
a `~ /.vim/colors/o a ~/.config/nvim/colors/` dependiendo de si es Vim o Neovim.
+ Agregue la línea colorscheme <**color-scheme-name**> a su 'vimrc'.

### instalando colorscheme utilizando plugins

+ Un requisito previo de este método es que tenga instalado vim-plug y sepa cómo usarlo.
  aquie les dejo el link para instalar: https://github.com/junegunn/vim-plug

+ La mayoría de las veces, todo lo que necesita es llamar a vim-plug
  desde su 'vimrc' como se muestra a continuación:

  ```c
  " begin plugin section
  call plug#begin()

  Plug '<GITHUB-USERNAME>/<REPOSITORY-NAME>'

   " end plugin section
  call plug#end()
  ```
+  Entonces, si quiero instalar el tema spaceduck que está disponible
   para Vim, a continuación se muestra cómo se vería mi 'vimrc'.

   ```c
   " begin plugin section
	call plug#begin()

	Plug 'sheerun/vim-polyglot'

	" end plugin section
	call plug#end()
   ```
+ Y finalmente, habilite ese esquema de colores agregando la siguiente
  línea a su 'vimrc' (si aún no lo ha hecho).
  `colorscheme <color-scheme-name>`
 
## Tips

+ Cuando se realize algun Cambio en **.vimrc**
  para que surja efecto el cambio sin tener que  cerrar el terminal 
  realizar la actualizacion desde dentro de .vimrc, asi `:source ~/.vimrc`
+ `:colorscheme [space] [press 'Ctrl + d']` esta opcion te permite ingresar
  a toda la paleta de colores, tambien esta otra opcion `:colorscheme [space] + tab`

 
contributor : Daisy

