# Pré Requisitos

## Noções Básicas de Informática

O computador é um dispositivo eletrônico que manipula informações ou dados. Ele vê os dados como uns (1) e zeros(0) - código binário - e os combinam em coisas mais complexas (fotos, filmes, sites, jogos etc). Eles usam **Hardware** e **Software**. O primeiro é qualquer parte física do computador, seus componentes internos e externos, já o último é qualquer conjunto de intruções que diz ao hardware o que fazer (navegador web, reprodutor de mídia ou editor de texto)

## Como a Web Funciona
### Como a Internet funciona?
A Web é um sistema de informações interligadas que permitem o acesso de conteúdos através da Internet. A ***World Wide Web***, conhecida mundialmente como ***“www”*** é uma das ferramentas da Internet que é responsável pela conexão através dos navegadores, como o Google Chrome e o Mozila Firefox, onde são publicados os formatos HTML. A internet é a espinha dorsal da web, a infraestrutura técnica que a torna possível. Em sua forma mais básica, a internet é uma grande rede de computadores que se comunicam entre si. Ou seja, a internet é uma forma de conectar computadores e garantir que, aconteça o que acontecer, eles encontrem uma maneira de permanecer conectados. Dessa forma, a Internet é uma infraestrutura técnica que permite conectar bilhões de computadores. Entre estes computadores, alguns computadores (chamados de servidores Web) podem enviar mensagens inteligíveis para navegadores Web. A Internet é a infraestrutura, enquanto a Web é um serviço construído sob esta infraestrutura. Vale a pena notar que existem diversos outros serviços que funcionam na Internet, tais como email e IRC.

Quando dois computadores precisam se comunicar, é preciso conectá-los, seja fisicamente (geralmente com um cabo Ethernet ) ou sem fio (por exemplo, com sistemas Wi-Fi ou Bluetooth ). Mas uma rede não é limitada a dois computadores. Você pode conectar quantos computadores desejar. Mas isto se torna complicado. Se você está tentando conectar, digamos, dez computadores, você irá precisar de 45 cabos, com 9 conexões por computador! Para resolver este problema, cada computador na rede está conectado a um pequeno computador especial chamado de roteador. Este roteador tem um único trabalho: como um sinalizador em uma estação de trem, ter certeza de que a mensagem enviada por um determinado computador chegue ao computador destinatário corretamente. 

Mas para conectrar centenas, milhares, milhões de computadores? Conectando roteadores a roteadores, criando uma rede de computadores. Mas e para conectar a rede da nossa casa com o resto do mundo? Muito bem, já existem cabos ligados a sua casa, como por exemplo, cabos de eletricidade e telefone. A estrutura do telefone já conecta nossa casa com o resto do mundo, então é exatamente o que nós precisamos. Para conectar nossa rede a rede telefônica, precisamos de um equipamento especial chamado modem. Este modem transforma a informação da nossa rede em uma informação gerenciável pela rede telefônica e vice-versa.

Então nós estamos conectados à infraestrutura telefônica. O próximo passo é enviar mensagens da nossa rede para a rede que nós desejamos alcançar. Para fazer isto, vamos precisar conectar nossa rede a um Provedor de Serviço de Internet (ISP, em inglês). Um ISP é uma companhia que gerencia alguns roteadores especiais que são conectados e podem também acessar roteadores de outros ISPs. Então a mensagem da nossa rede é transportada para a rede de redes do ISP e então para a rede de destino. A Internet é composta por toda esta infraestrutura de redes.

Se você quer enviar uma mensagem para um computador, você precisa especificar qual é este computador. Por isso, qualquer computador conectado à uma rede possui um único endereço de identificação, chamado de "Endereço IP" (onde IP, do inglês Internet Protocol, significa Protocolo de Internet). Este é um endereço composto por uma série de 4 números separados por pontos, por exemplo: 192.168.2.10.

Isto é perfeito para computadores, mas nós seres humanos temos dificuldades para lembrar estes endereços. Para tornar as coisas mais fáceis, nós podemos dar apelidos aos endereços IP que nós humanos podemos compreender, chamados nome de domínio. Por exemplo, google.com é um nome de domínio usado para "apelidar" o endereço 142.250.190.78 Então, usando o nome de domínio é uma forma mais simples de encontrar um computador na Internet.

Além da Internet, existem as Intranets e as Extranets: 
* Intranets são redes privadas restritas aos membros de uma organização particular. Elas são geralmente usadas para prover um portal para que tais membros tenham acesso a recursos compartilhados, possam colaborar e comunicarem-se entre si de forma segura.
    * Por exemplo, a intranet de uma organização pode hospedar páginas da web para compartilhar informações de departamentos ou equipes, unidades compartilhadas para gerenciamento de documentos e arquivos importantes, portais para executar tarefas de administração de negócios e ferramentas de colaboração como wikis, quadros de discussão e sistemas de mensagens.
* Extranets são bastante semelhantes às Intranets, exceto pelo fato de que abrem toda ou parte de uma rede privada para permitir o compartilhamento e a colaboração com outras organizações.
    * Elas são normalmente usadas para compartilhar informações de forma segura com clientes e partes interessadas que trabalham em estreita colaboração com uma empresa. Frequentemente, suas funções são semelhantes às fornecidas por uma intranet: informações e compartilhamento de arquivos, ferramentas de colaboração, fóruns de discussão, etc.

Fonte: https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Howto/Web_mechanics/How_does_the_Internet_work

### Qual a diferença entre página web, site, servidor web e mecanismo de busca?
___**Página web**___ é simplesmente um documento que é renderizado ("mostrado") por um navegador. Tais documentos são escritos com uso da linguagem HTML. Todas as páginas web disponíveis na web são alcançáveis através de um único endereço, webpage é uma única página, isolada dentro de um site. Essas páginas apresentam um endereço único que, diferente de um site, não é navegável. Uma página web pode possuir uma variedade de diferentes tipos de recursos incorporados a ela, como:
* informação de estilo — controlando como a página se apresenta e se comporta (look-and-feel)
* scripts — os quais são responsáveis por adicionar interatividade à página
* mídia — imagens, sons e vídeos.

Um ___**site**___ é um conjunto de páginas web vinculadas (mais os recursos associados a elas) que compartilham um único nome de domínio. Cada página web de um dado website provê links explícitos - na maior parte do tempo na forma de texto clicável - que possibilitam a um usuário mover-se de uma página do website à outra.

Um ___**servidor**___ web nada mais é que um computador hospedando um ou mais websites. "Hospedar" significa que todas as páginas web e seus arquivos auxiliares estão disponíveis a partir daquele computador. O servidor web enviará qualquer página web a partir do website que está hospedado nele para o navegador de qualquer usuário que o tenha requisitado

___**Mecanismos de pesquisa**___ são uma fonte comum de confusão na web. Um mecanismo de pesquisa é um tipo especial de website que auxilia usuários a encontrar páginas web de outros websites.Há um número abundante destas ferramentas: Google, Bing, Yandex, DuckDuckGo e diversos outros. 

Fonte: https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Environment_setup/Browsing_the_web

### Como a Web Funciona


### O que é um nome de domínio?