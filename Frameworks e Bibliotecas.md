  ### O que são Bibliotecas?

É uma coleção de códigos voltados para resolver um determinado problema.

<i>Exemplos</i>

 * Moment.js - Biblioteca para converter, validar, manipular e exibir datas e horários<br>
 * Chart.js - Biblioteca para a criação de gráficos<br>
 * Voca - Biblioteca para trabalhar com Strings<br>
 * mo.js - Biblioteca para criar animações incríveis com SVG. Já fizemos um post sobre como começar com o mo.js<br>
 * React - Biblioteca para criar interfaces de usuário. Se quiser conhecer um pouquinho, temos um post aqui no blog para você conhecer o React<br>

  ### O que são Frameworks?

É um conjunto de padrões que permitem a construção de aplicativos e que podem ser aplicados em projetos diferentes. O foco dos frameworks é mais amplo que das bibliotecas.<br>

<i>Exemplos</i>

 * Angular - Framework para criação de aplicações web<br>
 * Vue.js - Framework também para criação de aplicações web<br>
 * Ionic - Framework para criar aplicativos mobile com Angular, React ou Vue<br>
 * Express - Framework para criar aplicações com Node.js<br>
 * LoopBack - Framework para criar APIs e microserviços com Node.js<br>

  ### Mas então, qual a diferença entre Framework e Biblioteca?

Alguns lugares chamam Angular de biblioteca e React de framework, mas na verdade é o contrário. Além das diferenças já mostradas aqui é que normalmente as bibliotecas são usadas pelos nossos códigos, enquanto os frameworks é quem costumam utilizar os nossos códigos.

No <i>React</i> nós temos basicamente funções para a criação de componentes e criação de estados. Estamos no controle o tempo todo, nós chamamos as funções do React, podemos decidir qual será a estrutura da nossa aplicação e o fluxo com o qual ela funciona. Se acaso a gente precisar de funcionalidades de roteamento, animações, internacionalização, etc, precisaremos buscar bibliotecas para isso.

Em contrapartida no <i>Angular</i> todas essas funcionalidades já vêm inclusas. Há uma estrutura que devemos seguir (componentes, serviços, pipes, rotas, módulos), e o Angular é quem vai chamar o nosso código seguindo seu próprio fluxo. Essa característica de já ter uma estrutura é o principal diferencial entre um framework e uma biblioteca. Você pode notar que em nenhum momento nós chamamos alguma função como Angular.nomeFuncao(). Eventualmente, caso queira fazer algo num fluxo ou estrutura diferente, o Angular não vai entender e você terá um erro.

  ### Qual o melhor?
Podemos concluir que enquanto na biblioteca nós mesmos criamos a base e o fluxo, no framework já temos toda a estrutura pronta para utilizarmos e seguirmos. Mas isso não significa necessariamente que um é melhor do que o outro. São ferramentas diferentes para propósitos diferentes.

Ao passo que no Angular nós já temos toda a estrutura pronta, nos poupando desse trabalho, teremos menos liberdade para certas escolhas. Em contrapartida, no React temos que definir coisas comuns como arquitetura e fluxo, mas teremos mais liberdade de escolher cada biblioteca responsável por cada funcionalidade em nossa aplicação.
