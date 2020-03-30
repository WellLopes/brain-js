# Problemas ao instalar o brain.js? #

  * Primeiro temos que saber como instalar via terminal
  Se você ainda não sabe fazer isso [assista](https://www.youtube.com/watch?v=RfbgCBCWME8)

## Se você está com um erro parecido com esse

 * [Error_Install_brain.js](https://github.com/BrainJS/brain.js/issues/390) - Erro de instalação

## Como eu consegui resolver

 ### Configurações do notebook que eu uso:
 
  * Windows 8.1 Pro 64x
  * Intel(R) Core(TM) i5-3320M CPU @ 2.60 GHz 2.60 GHz
  * Modelo: Thinkpad x230

 ### Linhas de comandos executadas
  
  * Desinstalei todas as versões do python que tinha na máquina
  
   `npm install -g node-gyp`

   `npm install -g windows-build-tools` - Não se preocupe, aqui irá demorar na instalação.

   `npm config set python python2.7`

   `npm config set msvs_version 2017`
  
   #### Depois de todo executado, fui no terminal do Visual Studio Code e digitei

   `npm install brain.js`

## Cosiderações finais

  Essa foi a forma que funcionou para mim, espero que de alguma forma possa ajudar a vocês à instalarem essa biblioteca
  E sim, a versão que roda o brain.js tem que ter o python 2.7, e quando executa o código ```npm install -g windows-build-tools``` ele já instala junto.
