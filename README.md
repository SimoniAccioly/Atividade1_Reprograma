# **Como a Internet funciona?** :globe_with_meridians: :globe_with_meridians:

+ Resumo :page_facing_up:
+ TCP/IP :satellite:
+ HTTP e HTTPS :closed_lock_with_key:
+ Roteador :signal_strength:
+ Página/Servidor de e-mail :mailbox_with_mail:
+ Nuvem :cloud:


![internet](https://user-images.githubusercontent.com/67556668/90066030-88330580-dcc3-11ea-8730-9cf1f19ef560.gif)">


# RESUMO
A Internet é a espinha dorsal da Web, a infraestrutura técnica que faz a Web possível. Mas basicamente, a Internet é uma gigantesca rede de computadores que se comunicam juntos.

A história da internet é um pouco obscura. Ela começou nos anos 60 como um projeto de pesquisa consolidado pelo exército norte americano, e tornou-se uma infraestrutura pública nos anos 80 com o suporte dado por diversas universidades públicas e companias privadas. As várias tecnologias que suportam a internet se acoplaram através do tempo, mas a forma de funcionamento não mudou muito: Internet é uma forma de conectar computadores e garantir, em qualquer situação, que eles encontrem uma forma de se manter conectados.

![google-origem](https://user-images.githubusercontent.com/67556668/90075010-c683f100-dcd2-11ea-98f7-cbb88ec8f215.jpg)


Muitas pessoas usam a Internet todos os dias, mesmo sem saber como ela funciona. Quando conversamos com nossas famílias pelo WhatsApp, enviamos e-mails para amigos e amigas e jogamos online, a Internet parece uma coisa mágica. E de fato é. Tecnologia é magia, e magia é tecnologia. Mas entender como essa mágica funciona é muito importante, e é uma questão política.

![não é mágica](https://user-images.githubusercontent.com/67556668/90067348-5a4ec080-dcc5-11ea-8aa6-e7ca2448da62.png)

A Internet é uma rede de redes interconectadas. Daí o nome, inter, de interconectadas, e network, que significa rede em inglês. Internetwork! Ou simplesmente, Internet! Mas uma rede de quê? A Internet é uma rede de computadores (e pessoas!), que funciona de forma parecida a um serviço postal. Assim como o correio, que permite que você envie envelopes contendo mensagens e pacotes, a Internet permite que computadores se conectem entre si para enviar pequenos pacotes de dados contendo informações.

![internet2](https://user-images.githubusercontent.com/67556668/90069035-0c878780-dcc8-11ea-8ad4-e8aa7ff154ac.gif)

Quando pensamos na Internet, a primeira coisa que vem em mente é uma nuvem, certo? Ou uma imagem muito abstrata. Mas na verdade, a Internet é uma coisa bem física. Ela é feita, essencialmente, de cabos que passam por debaixo da terra (e do mar!), e conectam casas, países e continentes. Ao se conectar à Internet, você está se conectando a um cabo. É através dessa infraestrutura de cabos que nossos pequenos pacotes de dados vão trafegar, indo de um computador a outro. Para se conectar a uma página hospedada em um servidor nos Estados Unidos, por exemplo, os dados viajam pelos cabos, por debaixo do mar, até o outro continente e, em apenas alguns segundos, a página aparece na tela do computador.

![cabos submarinos](https://user-images.githubusercontent.com/67556668/90069227-65572000-dcc8-11ea-85fa-ef786da65d28.jpg)

Para se ter uma ideia, há, no mundo, hoje, mais de 360 cabos submarinos em funcionamento, que perfazem mais de 800 mil quilômetros — se juntássemos todos os cabos num só, eles dariam 20 voltas em torno da Terra. A história dos cabos submarinos é a história do capitalismo moderno. Desde as Grandes Navegações, europeus lançavam-se ao mar para fazer a roda do comércio girar e encurtar distâncias. Mas é em 1858, com o desenvolvimento industrial a pleno vapor, que começa a funcionar o primeiro cabo de comunicação transatlântico, construído pelos ingleses. Ele servia à tecnologia em voga à época: o telégrafo. Nos anos 1940, com o impulso da Segunda Guerra Mundial, os cabos submarinos foram convertidos para serem usados para telefonia. O domínio já não era dos britânicos, mas das empresas americanas. Nos anos 1980, por fim, surge a tecnologia da fibra ótica, que passa a ser usada nos cabos submarinos — muitas vezes seguindo as mesmas rotas traçadas no final do século 19.
Para que esse emaranhado de redes, cabos e dados funcione, a Internet é estruturada a partir de vários protocolos, como veremos a seguir:

# TCP/IP 

![tcp-ip](https://user-images.githubusercontent.com/67556668/90069978-7fddc900-dcc9-11ea-91a9-eb941cc6804d.jpg)

Para que os computadores consigam se comunicar, eles utilizam uma “língua” comum chamada TCP/IP (Transmission Control Protocol / Internet Protocol). Todo dispositivo (computador, celular, tablet) conectado à rede recebe um número de IP, para que os dispositivos possam identificar uns aos outros. Para enviarmos uma carta para alguém através do correio, precisamos saber o endereço da pessoa. A mesma coisa acontece na Internet, então o IP é tipo um CEP, um identificador ou um endereço.
Cada página na Internet também possui um IP, para que possamos nos conectar a elas. Como números são muito difíceis de memorizar, foi criado um mecanismo para que possamos identificá-las e acessá-las através de endereços memorizáveis, ou seja, nomes. Se, por um lado, precisamos saber o endereço de uma página para nos conectarmos a ela, as páginas que acessamos também conseguem ver o endereço de IP que estamos usando. Passeamos de página em página deixando alguns rastros, e um deles é o endereço de IP dos nossos dispositivos.
 
# HTTP e HTTPS 
![http](https://user-images.githubusercontent.com/67556668/90070152-c8958200-dcc9-11ea-8a72-e4a4d6744024.jpg)

Para acessar uma página, utilizamos também um protocolo de comunicação chamado HTTP (HyperText Transfer Protocol, que em português significa “Protocolo de Transferência de Hipertexto”), que é um conjunto de regras que permitem ao seu computador trocar informações com um servidor que abriga uma página. Isso significa que, uma vez conectados sob esse protocolo, os dispositivos podem receber e enviar qualquer conteúdo textual — os códigos que resultam na página acessada pelo navegador (chrome, firefox…).
O protocolo HTTP define, entre outras formalidades, como são requisitadas as páginas da Web, como são enviados os dados que uma pessoa insere em formulários de login e como o servidor envia mensagens de erro para o navegador de quem está acessando. No entanto, como o HTTP é um protocolo baseado em texto, ou seja, toda a informação transmitida está em texto, os dados de uma pessoa que usa a internet e do servidor podem ser interceptados ou alterados no meio do caminho.
Isso porque o HTTP foi desenvolvido para permitir a comunicação, e não a privacidade. Como hoje usamos a Internet para tudo, compartilhar informações, conversar com amigos e amigas, fazer compras e acessar nossa conta no banco, a privacidade se tornou uma das questões mais importantes.
Nesse sentido, um novo protocolo foi pensado e desenvolvido, o HTTPS. Ele insere uma camada de proteção na transmissão de dados entre seu computador e o servidor. Em páginas com endereço HTTPS, a comunicação é criptografada, aumentando significativamente a segurança dos dados.
É como se computador e servidor conversassem uma língua que só eles entendessem, dificultando a interceptação das informações.
Ao enviarmos um e-mail para uma pessoa, uma série de coisas acontecem: primeiro, conectamos nosso computador a um roteador através de uma conexão sem fio (wi-fi). O roteador, por sua vez, está conectado, através de um cabo, a um provedor de Internet (Oi, Net, GVT…), que nos concede a conexão à rede. Com o nosso computador conectado à Internet, o próximo passo é abrir um navegador (chrome, firefox) e acessar a página do nosso servidor de e-mail (Riseup, Gmail, Hotmail…). Lá, escrevemos o e-mail e enviamos ao servidor de e-mail da destinatária.
Se nosso computador estabelecer uma conexão com o servidor de e-mail através do protocolo HTTP, nossas informações irão trafegar pela rede sem nenhuma proteção. Seria como se estivéssemos enviando um cartão postal, e todas as pessoas que tivessem acesso a ele poderiam ler a mensagem. Por outro lado, se nosso computador estabelecer uma conexão HTTPS com o servidor de e-mail, nossa mensagem trafegaria com criptografia entre o computador e o servidor. Quem determina, em último caso, que protocolo será usado é o servidor, daí a importância de sempre prestar atenção se as páginas que visitamos usam HTTPS. Para isso, basta conferir, na barra de endereços do navegador, que protocolo está sendo usado.
O HTTPS também é importante para autenticar a página acessada. Ele contém um certificado que nos permite saber se a página que queremos acessar, por exemplo www.riseup.net, é realmente do coletivo Riseup. Isso dificulta que alguém crie uma página e tente se passar pelo Riseup.

# Roteador

![roteador](https://user-images.githubusercontent.com/67556668/90075162-27132e00-dcd3-11ea-86b3-8b2021005cd8.gif)

Imagine duas pessoas com computadores conectados à internet na mesma casa. Uma delas atualizando seu perfil em uma rede social, outra trabalhando. O que impediria o tráfego de informações mobilizado por uma delas de serem enviados para outra? Duas coisas: os endereços de IP dos dispositivos, e o roteador. Roteadores direcionam o tráfego da Internet, ajudando os pacotes de dados a chegar no seu destino. Isso significa que toda a nossa navegação passa por ele.
Assim, quem possuir acesso ao roteador, pode ter acesso a informações de navegação de todos os dispositivos conectados a ele. É por isso que precisamos configurar os roteadores que usamos com senhas fortes e protocolos de segurança. É por isso também que acessar wi-fis públicos pode ser problemático: não é possível saber se há alguém farejando nossa navegação.
Uma forma de se precaver é prestar sempre atenção ao tipo de protocolo estabelecido para acessar as páginas. HTTPS é sempre mais recomendável que HTTP, e dificulta que terceiros conectados ao roteador tenham acesso a nossa navegação. Outra possibilidade é usar serviços e ferramentas como VPN (Virtual Private Network) e Tor.
Provedor de Internet:
Provedores de Internet são empresas que fornecem endereços de IP para acesso à Internet, como Oi, Net, GVT. De acordo com o Marco Civil da Internet, elas não podem bloquear, monitorar, filtrar ou analisar o conteúdo dos pacotes de dados. No entanto, o Marco Civil obriga os provedores a coletar e armazenar logs de acesso à Internet, contendo o IP e a data e hora da conexão. Quer dizer, cada vez que acessamos a Internet, o provedor que contratamos registra a data e hora que conectamos e desconectamos, e o IP que utilizamos.

# Página/Servidor de e-mail

![email](https://user-images.githubusercontent.com/67556668/90080463-11a50080-dce1-11ea-92dc-e66f9d3efed0.png)

Visitar uma página é como visitar a casa de alguém: tudo que você faz por lá, a dona da casa pode ver. Além disso, todas as páginas que visitamos na Internet coletam e armazenam dados sobre nossa navegação e dispositivos. As pessoas que administram a página de um jornal, por exemplo, conseguem saber a que horas o IP do seu dispositivo visitou o site, em que links clicou, qual o sistema operacional do computador, que navegador está sendo usado, qual é o tamanho da tela, e muito mais, dependendo da política de privacidade da página.
Com essas informações, conseguem até traçar um perfil para as pessoas que visitam a página, mostrar publicidades direcionadas etc.
Já um servidor de e-mail comercial, como Gmail, Hotmail e Yahoo, além de coletar todas essas informações, também lê tudo que você escreve. Apesar de não cobrarem pelo uso, eles ganham dinheiro com os nossos dados, então vasculham e armazenam todos os e-mails, as fotos, os contatos. Sabem tudo sobre as pessoas que usam seus serviços, e podem vender esses dados para outras empresas, como as de publicidade, ou entregar esses dados para a polícia e agências de espionagem e Inteligência.
Para mitigar essa vulnerabilidade, não adianta utilizar HTTPS, já que o protocolo criptografa apenas a conexão entre nosso computador e a página. Isso significa que, para uma pessoa de fora, interceptar nossos e-mails pode ser uma tarefa difícil. No entanto, o conteúdo das nossas comunicações não está restrito aos remetentes e destinatários, mas também é acessado por quem provê o serviço. É como se o carteiro pudesse abrir e ler todas as cartas que enviamos.
Daí a importância de utilizar serviços de e-mail confiáveis e que se preocupam com a privacidade das pessoas. Serviços que não possuem como modelo de negócios os dados das pessoas usuárias, e que portanto não coletam informações sobre nossos dispositivos e não leem nossos e-mails, são bastante recomendáveis.

# Nuvem

![nuvem](https://user-images.githubusercontent.com/67556668/90080546-487b1680-dce1-11ea-9a7a-8c038d813edf.png)

Quando você acessa uma página, você está na verdade conectando seu computador a outro computador, através de cabos e protocolos de comunicação.
Uma página é composta de arquivos, que “moram” em um servidor conectado à rede. Servidores não são nuvens que pairam no ar, mas computadores, ligados à energia, e localizados em algum lugar do mundo. Então quando alguém fala de nuvem, tá falando, na verdade, de um computador. A nuvem é sempre o computador de outra pessoa.

### Fonte:
[Medium](https://medium.com/cuidados-integrais/como-a-internet-funciona-2936e6c7053e)
<br>
[mozilla](https://developer.mozilla.org/pt-BR/docs/Learn/Common_questions/Como_a_internet_funciona/)








