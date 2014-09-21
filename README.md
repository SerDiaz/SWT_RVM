**Sergio Díaz González**

He instalado git, curl para posteriormente instalar RVM, actualizar el bundler, instalando las gemas de Twitter y Sinatra. También he creado un tutorial en formato Markdown y generamos un HTML de Markdown con kramdown.

##· Instalación de Git

Para instalar git: 

`sudo apt-get install git`

![Alt text](hmagenes/git)


###· Instalar de RVM

Para instalar RVM necesito tener instalado 'curl'y como no lo tengo ejecuto:

`sudo apt-get install curl` 

![Alt text](magenes/curl)

Y una vez que ya disponemos de esta herramienta ya podemos instalar RVM: 

`\curl -#L https://get.rvm.io | bash -s stable --autolibs=3 --ruby`

![Alt text](magenes/rvm)


###· Comprobación que tengo Ruby

Ejecuto el comando siguiente comprobando si tengo ruby y la versión que tengo instalada.

`ruby -v`

![Alt text](magenes/ruby)
								
##Instalación de Bundler

Instalo Bundler:

`sudo gem install bundler`

![Alt text](magenes/bundler)

###· Instalación de Sinatra

Uso el siguiente comando:

`sudo gem install sinatra`

![Alt text](magenes/sinatra)

###· Instalación de Twitter

Y con Twitter es igual que en el caso anterior pero cambiando dicho nombre: 

`sudo gem install twitter`

![Alt text](imagenes/twitter)

