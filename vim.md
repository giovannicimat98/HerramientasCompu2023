# Comandos basicos

+ vim 
  + abre el editor en la carpeta donde se encuentra la terminal
+ vim (nombre del archivo)
  + abre el archivo con el editor, si no existe, entonces el archivo es "creado"
+ tipos de modos
  + normal
    + d
      + eliminar
    + u
     + undo
    + ctrl + r
     + redo
    + p
     + pegar
    + y 
     + yank (copiar)
    + b
      + palabra anterior
    + B | w
      + palabra siguiente
    + %
      + saltar entre parentesis, brackets, corchetes
    + t
      + salta hacia un caracter atras del que se especifico
    + f
      + salta hacia el caracter que se especifico
    + /
      + buscar en el documento
    + :s/original/remplazo
      + remplazar en el archivo 
  + insert
    + solamente escribir
    + a
      + despues del cursor
    + shift a (A)
     + final de la linea
    + i
     + antes del cursor
    + shift i (I)
      + Inicio de la linea
    + o
     + nueva linea
    + shift o (O)
      + nueva linea en la parte de arriba
  + visual 
  + Para salir de cada modo se utiliza la tecla esc, el modo normal es el modo donde se debe estar la mayoria del tiempo
+ Comandos basicos 
  + :q
    + salir de vim
  + :w
    + guardar archivo
  + q!
    + no guarda los cambios que hemos hecho
  + !
    + comandos de terminal

# Configuracion

+ :set number 
  + añade el numero de lineas
+ :set relativenumber
  + la enumeración se convierte en relativa dependiendo de donde se encuentra el cursor
+ :set mouse=a
  + Hacer acciones con el mouse
+ :colorscheme
  + añadir un tema a vim 

# Plugins 

## Instalacion

+ vim-plug
