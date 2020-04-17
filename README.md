# Polybar-Simple-Elegance

Dependencies: This customization of Polybar does not contain dependencies, in addition to those that are already customary in most customizations of Polybar, which are in their entirety (Symbolic Fonts), so that the symbols used in the customization are supported.

Dependencias: Essa customizaçao do Polybar nao contem dependencias,alem daquelas que ja sao de costume na maioria de customizaçoes de Polybar, que sao em su todo (Fontes Simbolicas), para que sejam suportados os simbolos usados na customizaçao.

Installation: Assuming you don't have Polybar installed on your system, then use AUR to install Polybar, compiling it from the website, or using yay on your terminal.

Then, create a directory inside your home / .config, and under the name of polybar, enter inside the polybar directory with the compact cd .config / polybar. Clone the Polybar Red_dark theme repository within the polybar directory.

With the text editor of your choice, edit the i3 config file, this file will be inside .config / i3 / config. At the end of the file add the following lines. exec --no-startup-id polybar -r mybar & exec --no-startup-id polybar -r bottom & These commands are responsible for starting the polybar altomatico with your system at boot time.

And last but not least, copy the fonts to your / usr / share / fonts directory, as follows. Within your polybar directory of the cd fonts command, of the ls command and check if they are all contained within the directory, then from the command, sudo cp -r * / usr / share / fonts, this command will copy all the necessary fonts for the correct functioning of the theme.

Restart your system, if everything went smoothly, when starting the theme will already be working.

Instalaçao: Supondo que voce nao tenha o Polybar instalado no seu sistema, entao use o AUR para instalar o Polybar, compilando o mesmo do site,ou usando o yay no seu terminal.

Em seguida, crie um diretorio dentro de sua home/.config, e de o nome de polybar, entre dentro do diretorio polybar com o comado cd .config/polybar. Clone o repositorio do tema Polybar Red_dark dentro do diretorio polybar.

Com o editor de texto de sua preferencia,edite o arquivo config do i3, este arquivo estara dentro de .config/i3/config. No final do arquivo adicione as seguintes linhas. exec --no-startup-id polybar -r mybar & exec --no-startup-id polybar -r bottom & Esses comandos sao responsaveis pelo inicio altomatico do polybar com seu sistema no momento do boot.

E por ultimo porem nao menos importante, copie as fontes para seu diretorio /usr/share/fonts, da seguinte forma. Dentro do seu diretorio polybar de o comando cd fonts, de o comando ls e confira se estao todas contidas dentro do diretorio, entao de o comando, sudo cp -r * /usr/share/fonts, esse comando ira copiar todas as fontes nesessarias para o funcionamento correto do tema.

Reinicie seu sistema, se tudo correu de forma certa, ao iniciar o tema ja estara funcionando.
