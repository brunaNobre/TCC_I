# Above
**Web App de Astrologia e Organização Pessoal**

## Projeto para o TCC-I da FATEC Pelotas Senac RS 

**Autora**: Bruna Nobre Almeida<br>
**Orientador:** 

### Proposta


Desenvolver uma web app de entretenimento e organização pessoal tendo como tema central uma das culturas místicas mais populares do mundo: Astrologia, que é a crença de que as posições relativas dos corpos celestes poderiam prover informação sobre a personalidade, as relações humanas, e outros assuntos relacionados à vida do ser humano.

O app será utilizado para centralizar informações relativas a humor, como se faz no aplicativo [Maia](https://itunes.apple.com/br/app/maia-controlador-do-per%C3%ADodo/id492534636?mt=8), por exemplo, mas com enfoque em Astrologia. Com espaço para alimentação do app com informações pessoais que serão comparadas com informações de “trânsitos astrológicos”, fornecidas pelo próprio app, e essa correlação será apresentada em algum formato visual.

O app apresentará informações que a Astrologia diz afetar as pessoas em geral, como o trânsito aparente da Lua, Vênus, a ocorrência dos chamados “planetas retrógrados”, etc.

Notificará o usuário, com _push notifications_, avisando sobre mudanças desses trânsitos e mostrará, em área específica,  informações sobre os seus significados segundo a Astrologia.

Haverá uma área de anotações para organização pessoal, com calendário (que conterá informações astrológicas) que o usuário poderá utilizar para decidir o melhor momento para a realização de tarefas do cotidiano e iniciar projetos, por exemplo.

Acreditando ou não em Astrologia, o usuário terá uma ferramenta para traçar seu estado de espírito ao longo do tempo e para organizar-se de forma lúdica.

### Motivação

A Astrologia é um tema que possui grande interesse por parte das pessoas, e, mesmo que essas não acreditem, necessariamente, na veracidade de suas afirmações, a maioria delas a mantém presente em suas vidas, pois como diz o sociólogo Michel Maffesoli, “A Astrologia não é uma ciência, é um fato social.” 

Também sobre a Astrologia na sociedade o astrônomo e professor de história da ciência do Instituto de Astronomia e Geofísica e Ciências Atmosféricas da USP (IAG), Amâncio Friaça, diz que trata-se de “um fenômeno psicossocial e simbólico. É tremendamente importante, por isso que a Astrologia continua bem forte hoje em dia. Se ela não tivesse um apelo simbólico e racional profundo, não seria tão forte.”

Fazendo-se uma pesquisa sobre o assunto pode-se constatar que nos últimos anos, houve um crescimento na demanda de produtos, principalmente digitais, com enfoque em astrologia. Observa-se o aumento das pesquisas no Google, nos últimos 5 anos, de termos como “mapa astral” e “signo” no Brasil e “mercury retrograde” no mundo:


![Pesquisa do termo "mapa astral" no Google](https://raw.githubusercontent.com/brunaNobre/TCC_I/master/googleTrendsMapaAstral.PNG)
_Pesquisa do termo "mapa astral" no Google nos últimos 5 anos, no Brasil._

<br>
<br>

![Pesquisa do termo "signo" no Google](https://raw.githubusercontent.com/brunaNobre/TCC_I/master/googleTrendsSigno.PNG)
_Pesquisa do termo "signo" no Google nos últimos 5 anos, no Brasil._

<br>
<br>

![Pesquisa do termo "mercury retrograde" no Google](https://raw.githubusercontent.com/brunaNobre/TCC_I/master/googleTrendsMercuryRetrograde.PNG)
_Pesquisa do termo "mercury retrograde" no Google desde 2004, no mundo._


Vê-se cada vez mais sites, perfis no Instagram e Facebook relacionados à Astrologia.

Exemplos de sites:

https://energiasdomes.com.br<br>
https://www.desvendandoosastros.com/consulta<br>
https://www.personare.com.br/<br>
https://www.viastral.com.br/<br>
https://www.girlboss.com/girlboss/2018/2/28/horoscopes-march-2018<br>
https://www.bustle.com/profile/mecca-woods-1906818<br>
https://www.thedailyhunch.com/<br>
https://twitter.com/poetastrologers?lang=en<br>
https://medium.com/@rosalyster<br>
http://astroinvest.com.br/<br>

Exemplos de perfis no **Instagram**:

https://www.instagram.com/isabellamezzadri/<br>
_287mil seguidores_

https://www.instagram.com/desvendandoosastros/<br>
_57,2mil seguidores_

https://www.instagram.com/astrodica/<br>
_47,2mil seguidores_

https://www.instagram.com/cafecomastrologia/<br>
_17,7mil seguidores_

Exemplos de canais no **Youtube**:

[Claudia Lisboa](https://www.youtube.com/channel/UCdSmm6Wp1vexPuoZh_yRDIw)<br>
_47.888 inscritos_

[Paula Pires - Astrologia e Terapias](https://www.youtube.com/user/safhica)<br>
_245.082 inscritos_

[Caroll Crown](https://www.youtube.com/user/papoastral)<br>
_367.974 inscritos_

A demanda e aceitação por parte do público é suficiente para que alguns desses sites cobrem preços relativamente altos por serviços como realização de mapa astral e _coaching_ tendo a Astrologia como base. Um deles, o [Astroinvest](http://astroinvest.com.br/), foi além do aconselhamento na esfera da vida pessoal e oferece serviços de consultoria financeira baseando-se no movimento dos astros. Um outro exemplo, mais extremo, é essa oferta de vaga de emprego na qual é solicitado que se envie o mapa astral do candidato junto ao currículo:

![vaga de emprego](https://raw.githubusercontent.com/brunaNobre/TCC_I/master/vaga%20de%20emprego.png)
_Fonte: <https://www.facebook.com/vagasVTNC/photos/a.484277248573331.1073741828.484254228575633/589999451334443/?type=3&theater>._

Uma [reportagem](https://oglobo.globo.com/sociedade/pesquisa-revela-que-44-dos-brasileiros-seguem-mais-de-uma-religiao-21444431) do jornal O Globo apresenta dados de uma pesquisa que demonstra que, no Brasil,  “a astrologia é defendida por 42% das pessoas”.


Esse [artigo](https://www.nytimes.com/2018/01/01/arts/how-astrology-took-over-the-internet.html) do jornal americano The New York Times fala sobre como a Astrologia “tomou conta” da Internet, tendo cada vez mais _memes_ de signos, o surgimento de novos “gurus” famosos na internet e todo um grupo de produtos que fazem um _rebranding_ do zodíaco para as mídias digitais. O artigo argumenta, também, que a Astrologia preenche vários requisitos para ser viral, como o fato de oferecer um _framework_ para a criação de um infindável material personalizado e acessa a nostalgia dos anos 90. É o [Quizz do Buzzfeed](https://www.buzzfeed.com/quizzes?utm_term=.onVgq6DdE#.jjpXNebvn) cósmico.
[Outro artigo](https://www.marketwatch.com/story/why-millennials-are-ditching-religion-for-witchcraft-and-astrology-2017-10-20) diz que a geração Y está menos propensa a ter uma religião e está preenchendo esta lacuna com o esoterismo.

O app americano [Co-Star](https://www.costarastrology.com/), que oferece serviços de confecção de mapa astral, entre outras coisas, teve tanta demanda que na primeira semana de seu lançamento o app caiu três vezes.

A Astrologia como uma tendência foi identificada também pelo publicitário e pesquisador André Alves, o psicanalista e pesquisador Lucas Liedke (ambos trabalharam na Box1824, empresa especializada em pesquisa de mercado e tendências de consumo) e os designers gráficos Gabriela Namie e Jun Ioneda que montaram o projeto [Peoplestrology](https://www.peoplestrology.com/peoplestrology/#cap1) que se propõe a pesquisar "o que a Astrologia pode revelar sobre valores da atualidade – a forma como enxergamos o mundo, os outros e nós mesmos".

Tendo em vista as considerações acima, a criação de um app com enfoque em Astrologia mostra-se pertinente e passível de interesse por uma quantidade razoável de usuários.

### Objetivos

**Geral**

Criar aplicação [PWA](https://developers.google.com/web/progressive-web-apps/) (Progressive Web App) para usuários com interesse em Astrologia, e que normalmente buscam informações diárias sobre trânsitos astrológicos, e outros temas relacionados à Astrologia, em diversas fontes esparsas, para que eles possam ter essas informações centralizadas e rapidamente acessíveis. O app também deverá conter módulos de organização pessoal que os usuários poderão utilizar para alinhar suas tarefas e projetos com as chamadas “energias dos planetas”.

**Específicos**

A seguir, são apresentados os objetivos específicos:

* Aprofundar conhecimentos de Laravel.
* Criar back-end da aplicação;
* Identificar os perfis de usuários;
* Criar personas e mapas de empatia;
* Definir a UX (User Experience) mais adequada para o app;
* Aprofundar conhecimentos sobre PWA para a criação da web app como um todo;
* Estudar as tecnologias _service workers_ e _push notifications_;
* Desenvolver as notificações na tela do usuário mostrando os trânsitos astrológicos diários;
* Consolidar conhecimentos em Vanilla Javascript, React e Redux;
* Desenvolver telas e componentes da aplicação.



### Levantamento de Requisitos

O levantamento dos requisitos do sistema se deu através de observação, benchmarking e entrevistas.

**Requisitos Funcionais**

- **Cadastrar usuário**:<br>
  O usuário fará um cadastro que depois será utilizado para mostrar sua área de perfil personalizada (levando em consideração seu signo solar);

- **Fornecer formulário para informar dados do nascimento do usuário para o cálculo do mapa natal**:<br>
  Após ter cadastrado seu nome e dados de nascimento, o usuário poderá consultar, em área específica, os dados do seu mapa astral;
- **Mostrar cálculo de mapa natal**;

- **Mostrar perfil do usuário com informações dos principais signos do mapa**:<br>
  O perfil do usuário mostrará seu nome e, abaixo dele, os símbolos do seu signo solar, ascendente e lunar;

- **Fornecer campo com um calendário com o qual o usuário poderá interagir para registrar tarefas e anotações diversas**:<br>
  O usuário poderá escolher um dia no calendário, pressionando no mesmo, e assim o app abrirá um campo para o registro de atividades ou anotações;

- **Apresentar, nos campos do calendário que mostram os dias específicos, o trânsito atual da lua**:<br>
  Cada bloco do calendário, que representa o dia da semana, terá dois símbolos específicos para informar a fase da Lua e em que signo ela está transitando;

- **Mostrar dicas astrológicas com relação ao trânsito da lua**:<br>
  Quando o usuário pressionar em um dia específico no calendário, mostrar botão que, quando pressionado, mostrará informações sobre o que é recomendado fazer e o que não é, segundo a astrologia, naquele dia segundo a lua;

- **Fornecer informações sobre a posição diária dos astros e interpretações sobre ela**:<br>
  Em área específica, o usuário terá acesso a pequenos textos com a interpretação do trânsito astrológico atual;

- **Mostrar notificações sobre trânsitos astrológicos através de _push notifications_**;

- **Fornecer área para _checklist_ de atividades**:<br>
  O usuário poderá acessar o checklist de suas atividades pelo calendário ou em um caminho que leve diretamente para ele;

- **Ter área para registro das _vibes_ do dia**:<br>
  Um ícone levará o usuário para uma lista de ícones, representando, cada um, uma vibe diferente que o usuário poderá escolher (poderá ser mais de uma) para representar as _vibes_ daquele dia;

- **Cruzar informações do trânsito do dia com as _vibes_ do dia**:<br>
  Mostrar o percentual de acerto entre a vibe prevista pela interpretação do trânsito astrológico e a _vibe_ informada pelo usuário em um infográfico;

- **Mostrar uma frase motivacional ou de humor com imagem (a exemplo dos memes) ao fundo diferente a cada dia**.


**Requisitos não-funcionais**

- Ser uma [PWA](https://developers.google.com/web/progressive-web-apps/) - Progressive Web App;
- Front-end com [React](https://reactjs.org/);
- Back-end utilizará o framework [Laravel](https://laravel.com/)
- Utilizar API para a realização dos mapas natais do usuário;
- Utilizar API para as informações dos trânsitos astrológicos diários;
- Utilizar API para as explicações astrológicas desses trânsitos;

