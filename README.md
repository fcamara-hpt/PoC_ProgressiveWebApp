# PoC_ProgressiveWebApp

## Introdução
Progressive Web Application é uma nova forma de desenvolvimento de software, ele é visto como a passagem dos aplicativos nativos de smarthphones para o sistema hibrido e até usando o browser como uma nova opção de plataforma, isso é possivel pelas novas funcionalidades que os browsers veem conseguindo, como por exemplo o service worker e o web app manifest.

Segundo a documentação de developers do google(uma das empresas que apoia o pwa) o basico para uma aplicação ser considerada um pwa é:

*O site ser servido em um servido HTTPS, importando dizer que uma pwa só funciona no HTTP em testes locais, fora isso ela não funciona.

*A pagina deve ser responsiva, principalmente para tablets e smarthphones.

*A URL inical deve responder offline, isso é possivel graças ao service worker.

*Ter metadata suficiente para fazer que a sua pagina peça para ser adicionada como um atalho no smarthphone, isso é possivel por conta de um bom Web app manifest.

*Desde a primeira navegação ele ser rapido, até mesmo no 3G.

*Deve funcionar em todos os browser, obivamente seguindo a disponibilidade de tecnologia que cada um deles atende.

*Ter uma boa navegação mesmo com uma internet com sinal baixo.

*Cada pagina deve ter sua propria URL.

O google tambem oferece o Lighthouse Tool para testar a osua aplicação e ver o quanto elas está atendendo aos requisitos de uma pwa.

Você pode ver um pouco mais sobre no [Google Developers PWA](https://developers.google.com/web/progressive-web-apps/)

## Como usar o pwa no server
* É necessario instalar ionic v2 junto do cordova e uma versão do Node.js superior a 6.x, de preferencia para usar uma versão LTS.
```npm install -g ionic cordova```
  [Node.js](https://nodejs.org/en/download)
  
* Depois de instalar o ionic é necessario fazer dois passos para ai sim poder ver a aplicação no servidor


* FBaixar e instalar as dependências:


```npm install```


* Depois é necessario criar uma pasta www no diretorio principal.


* Acesse a aplicação usando ``` ionic serve``` ele vai subir um localhost para fazer o teste da aplicação.
