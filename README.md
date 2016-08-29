# Grupo-de-Estudos-de-Haskell
Grupo de estudos sobre Haskell da Webschool


# Ementa
* Introdução
  * [O que é Programação Funcional?](#o-que-é-programação-funcional)
  * [Entonces, (WTF is Haskell), o que é Haskell?](#entonces-wtf-is-haskell-o-que-é-haskell)
  * [A Preguiça do Haskell!](#a-preguiça-do-haskell)
  * [Haskell...Estati “O que” ?...Estaticamente Tipado.](#haskell-estati-o-que-estaticamente-tipado)
  * [Inferência de Tipo.](#inferência-de-tipo)
  * [Elegante e Conciso.](#elegante-e-conciso)
  * [Feito por Caras Realmente Inteligente (Cabuloso).](#feito-por-caras-realmente-inteligente-cabuloso)
  * [Bora nessa?!... É Claro Que Sim Jovem Guerreiro!](#bora-nessa-é-claro-que-sim-jovem-guerreiro)
  * [Instalando Haskell.](#instalando-haskell)


# O que é Programação Funcional?

Não é somente uma Programação que _FUNCIONA_...

A programação funcional baseia-se no conceito matemático de função, na qual para cada elemento de seu conjunto domínio (entrada) há apenas UM elemento no seu conjunto contra-domínio (saída), evitando estados/variáveis ou dados mutáveis.

# Entonces, (WTF is Haskell), o que é Haskell?

Haskell é uma linguagem de programação puramente funcional. Em CONTRASTE com a Programação Imperativa, em que segue uma sequência computacional de tarefas sendo executadas e durante o processo possam mudar de ESTADO.

Em linguagens funcionais como Haskell, não se diz para o computador o que fazer, e em vez disso, é dizer em qual coisa está. A soma de uma lista de números é o primeiro mais a soma de todos os outros números, expressando em forma de funções, por exemplo, soma n = soma(n-1) + n .

Não se pode definir uma variável sendo como algo e logo depois defini-lá como outra, ou seja, se for dito que algo é 7, esse algo É 7 e ponto final(.)!

<p> Então, em linguagens puramente funcionais <i>(Devs chamando: -Haskell, Haskell, Haskell...)</i>, uma função não tem efeitos colaterais, e a ÚNICA coisa a ser feita com uma função é calcular um TREM e devolvê-lo como um RESULTADO. Com isso temos a seguinte vantagem, se a função é chamada 2 vezes com os mesmos parâmetros, vai garantir o retorno de um mesmo RESULTADO. <br/>
Isso se chama <i>(tambores...drum...drum...drum…)</i> TRANSPARÊNCIA REFERENCIAL, isso não somente permite que o compilador (no caso do Haskell é o GHC) raciocine sobre o comportamento do programa, permitindo a fácil dedução <i>(esfregando na cara)</i> que uma função está correta, e em seguida, construir funções mais complexas ‘colando’ diversas funções simples em conjunto. </p>

# A Preguiça do Haskell!

<p> Isso significa que a menos que seja especificamente dito de outra forma, Haskell não irá <i>(mover um dedo)</i> executar funções e calcular as coisas antes que ele seja REALMENTE OBRIGADO a mostrar um RESULTADO. <br/>
Isto casa muy bien <i>(como beck e ceva)</i> com a transparência referencial permitindo pensar em programas como uma série de TRANSFORMAÇÕES NOS DADOS. Permitindo <i>umas parada massa</i> como ESTRUTURAS DE DADOS INFINITAS. <br/>
Em uma linguagem preguiçosa, podemos ter alguns dados iniciais e eficimentemente transformá-los, assim assemelhando com aquilo que queremos no final. </p>

# Haskell...Estati “O que” ?...Estaticamente Tipado.

<p> Ao compilar o programa, o compilador saberá o que é um número, o que é uma string, e a vida que segue. <br/>
Isso permite que possíveis erros possam ser capturados em tempo de compilação <i>(ao adicionar um número a uma string, o compilador vai reclamar)</i>. </p>

# Inferência de Tipo.

Não é necessário identificar cada pedaço de código, pois o sistema de tipos inteligentemente descobrirá bastante sobre ele _(não é necessário dizer que a é um número, pois ele irá descobir por si só)_.

Inferência de tipo também permite que o código possa ser mais genérico, ou seja, se uma função de soma passa dois parâmetros e retorna o resultado da soma, não é necessário explicitamente declarar os tipos, ele irá _funfar_ com quaisquer valores que sejam números.

# Elegante e Conciso.

Quer dizer que, Haskell utiliza muito conceitos de alto nível, programas Haskell geralmente são mais curtos que seus equivalentes imperativas. _E cá entre nós_, programas mais curtos são mais fáceis de se manter e possui menos bugs.


# Feito por Caras Realmente Inteligente (Cabuloso).

<p> Haskell foi feito por caras com doutorado. O trabalho sobre Haskell começou em 1987 quando uma comissão de pesquisadores se reuniu para projetar uma linguagem matadora (Killer). <br/>
Em 2003, o Relatório Haskell foi publicado já com uma versão estável <i>(Filé)</i> da linguagem. </p>

# Bora nessa?!... É Claro Que Sim Jovem Guerreiro!

<p> É necessário um editor de texto e o compilador Haskell. O Compilador Haskell utilizado é o GHC (Glasgow Haskell Compiler), o compilador Haskell mais utilizado no mundo. <br/>
A melhor maneira para iniciarmos os trabalhos é baixar a plataforma haskell <i>(acompanhando baterias)</i>. </p>


# Instalando Haskell.

Selecione a [Plataforma Haskell](https://www.haskell.org/platform/)

Por exemplo, em <i>Linux Mint</i>: <br/>
sudo apt-get install haskell-platform <br/>

Para ver a versão atual no seu S.O, abre o terminal e digite: <br/>
ghci <br/>

Para sair, digite: <br/>
:quit OU :q <br/> <br/>

Referências: <br/>
[Learn You A Haskell En-US](http://learnyouahaskell.com) <br/>
[Learn You A Haskell PT-BR](http://haskell.tailorfontela.com.br/)
