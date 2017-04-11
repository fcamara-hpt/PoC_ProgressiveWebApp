# PoC_ProgressiveWebApp

## Introdução
Progressive Web Application é uma nova forma de desenvolvimento de software, ele é visto como a passagem dos aplicativos nativos de smarthphones para o sistema hibrido e até usando o browser como uma nova opção de plataforma, isso é possivel pelas novas funcionalidades que os browsers veem conseguindo, como por exemplo o service worker e o web app manifest.

Segundo a documentação de developers do google(uma das empresas que apoia o pwa) o basico para uma aplicação ser considerada um pwa é:

* O site deve estar em um servido HTTPS, importando dizer que uma pwa só funciona no HTTP em testes locais, fora isso ela não funciona.

* A pagina deve ser responsiva, principalmente para tablets e smarthphones.

* A URL inical deve responder offline, isso é possivel graças ao service worker.

* Ter metadata suficiente para fazer que a sua pagina peça para ser adicionada como um atalho no smarthphone, isso é possivel por conta de um bom Web app manifest.

* Desde a primeira navegação ele ser rapido, até mesmo no 3G.

* Deve funcionar em todos os browser, obivamente seguindo a disponibilidade de tecnologia que cada um deles atende.

* Ter uma boa navegação mesmo com uma internet com sinal baixo.

* Cada pagina deve ter sua propria URL.

O google tambem oferece o Lighthouse Tool para testar a osua aplicação e ver o quanto elas está atendendo aos requisitos de uma pwa.

Você pode ver um pouco mais sobre no [Google Developers PWA](https://developers.google.com/web/progressive-web-apps/)


## Progressive Web Application vs. Aplicativo Nativo

Mais algumas informaçes sobre pwa pode ser vista aqui:
[Guia básico sobre Progressive Web Apps](https://medium.com/fcamara-hpt/guia-b%C3%A1sico-sobre-progressive-web-apps-4eaa42f17f63)

### Vantagens
* É uma aplicação feita de HTML, CSS e JavaScript, essas são tecnologias que ja tem anos no mercado e que qualquer browser tem o poder de ler elas, a diferença é que se o browser é mais antigo, alguma das funções do pwa pode não funcionar, porem a aplicação ainda sim pode ser vista e utilizada, diferente de uma aplicação nativa que conforme a aplicação e sistemas operacionais do smarthphone vo ganhando atualizaçes, eles ficam obsoletos e precisam ser refeitos para voltar a rodar, gerando retrabalho.

* Eles são rapidos na hora de carregar e nunca vão mostrar que está sem internet, ams sim os dados salvos no service worker, fazendo assim ainda ser possivel interagir com a aplicação.

* São rapidos, até mesmo em internets 3G, pela forma como devem ser estruturados, tem a tendencia de carregar rapido e sempre usar o service worker com os caches a seu favor para sempre melhorar a performance de load da pagina.

* Tem uma experiencia de engajamento muito boa para o usuario, que não precisou procurar o aplicativo dentro de uma store com varios outros aplicativos, ele simplesmente entrou naquele site por meio da sua URL, sendo muito mais facil de interagir e engajar o usuario.

### Desvantagens
* A performance de uma aplicação nativa ainda sim é considerada melhor que a de uma pwa, por mais que a diferença não seja grande, ainda existe.

* A facilidade de acessar o hardware e ter mais funçes nativas é outra vantagem dos nativos, mas que veem sendo quebrada, já que as principais funcionalidades "nativas" ja veem sendo trazidas para os browser, mas ainda sim os aplicativos nativos tem mais facilidades quanto a isso.

## Pré-requisitos para criar um Progressive Web App com Ionic(2.x ou 3.x)

### 1-Node.js
Instalar Node: [Node.js](https://nodejs.org/en/download)
Após a instalação, abra o terminal e execute o seguinte comando para obter a versão mais recente do npm:
```js
npm install npm -g
```
### 2- Ionic2.x e Cordova
Installar Ionic e Cordova: [Ionic e Cordova](http://ionicframework.com/docs/intro/installation/)

```sudo npm install -g ionic cordova```

Para adicionar globalmente é recomentado usar "sudo", caso contrario, só excluir o "sudo" antes do npm.

### 3 - Instalando as dependencias
Faça a instalação das dependendias do Package.json com o 
```npm install```

Depois é necessario a criação de um diretorio 
```www```

### 4 - Subindo a aplicação local
Para subir a aplicação de forma local basta usar o comando 
``` ionic serve```

### 5 - Firebase
Essa aplicação foi online por meio do [firebase](https://firebase.google.com/), uma boa forma de subir a aplicação, já que ele é gratuito, tem a integração com banco de dados e não precisa de um server node, como é o caso do heroku(que tambem não deixa de ser uma boa opção, apenas diferente da usada nesse projeto).

#### Em caso de dúvidas, entre em contato nos e-mails abaixo, tambem presentes no package.json:

Caio Henrique Cristóvão <caio.cristovao@fcamara.com.br> ou <caiohcris@gmail.com> 

Flavio Brognara <flavio.brognara@fcamara.com.br>
