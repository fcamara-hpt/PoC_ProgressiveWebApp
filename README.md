# PoC_ProgressiveWebApp


* Um Progressive Web Aplication é um aplicativo dentro de um browser, isso se da por conta do service worker e web app manifest,
que permitem fazer o cache de dos dados para eles serem utilizados offline e pelo fato da pagina web se oferecer para ser salva
na tela do telefone e poder ser acessada pelo usuario igual um aplicativo, inclusive modificando a barra de URL para um nav, assim
passando para o usuario uma experiencia de app e não de uma web page.


## Como usar o pwa no server


* É necessario instalar ionic v2 junto do cordova e uma versão do Node.js superior a 6.x, de preferencia para usar uma versão LTS.
```npm install -g ionic cordova```
  [Node.js](https://nodejs.org/en/download)
  
* Depois de instalar o ionic é necessario fazer dois passos para ai sim poder ver a aplicação no servidor


* FBaixar e instalar as dependências:


```npm install```


* Depois é necessario criar uma pasta www no diretorio principal.


* Acesse a aplicação usando ``` ionic serve``` ele vai subir um localhost para fazer o teste da aplicação.
