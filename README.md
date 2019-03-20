# a git of thrones
> in the git of thrones you either win or die. But you always git commit and git push before it.

Este repositório foi criado para a apresentação sobre git. Usaremos as threads da Família Stark, de A Song of Ice and Fire, para explicar alguns conceitos básicos desta ferramenta.

## Sobre o exercício proposto
A proposta é que se faça um review dos principais acontecimentos com os integrantes da Família na história contada até agora. Os acontecimentos serão organizados assim:

* Cada integrante da casa possui um arquivo `.txt`, onde sua história vai sendo incrementada nas diversas versões;
* Cada novo plot será apresentado em um branch diferente, para demonstrar o fluxo de criação, navegação e merge de branches;
* Todo plot finalizado será redirecionado para o branch `master`, que funciona como o repositório da história contada pelos meistres da cidadela;
* Os eventos foram organizados de forma simplista. Não espera-se que todos os eventos sejam anotados perfeitamente aqui. A ordem cronológica também pode ter se alterada em alguns pontos, novamente, para simplificar a estrutura dos branches;
* Todos os eventos alheios à cena principal da Familia Stark foram desconsiderado neste exemplo: o foco é o exercício proposto, não a história a ser contada.

## Roteiro
> Obs.: O roteiro possui algumas frases com concordância verbal incorreta, escrita entre aspas. Os textos servirão para ser colocados nos arquivos exclusivos dos personagens, por isso foram anotados assim.

Segue abaixo o roteiro a ser seguido durante a apresentação:

> Inicia-se o repositório (através de um pull no remoto).

> Criar os arquivos
  * ned.txt
  * caitlyn.txt
  * jon.txt
  * robb.txt
  * sansa.txt
  * arya.txt
  * bran.txt
  * rickon.txt

> Ainda em master

* Toda a Família se inicia a história em Winterfell, recebendo a visita da comitiva do Rei Robert Baratheon
* Ned é convidado ao Porto Real para servir de Mão do Rei
* Bran "sofre acidente" e fica tetraplégico
* Ned, Sansa e Arya "vai para Porto Real"
* Jon vai para a Muralha para se juntar à Patrulha da Noite

> Trocar de branch para `jon-na-muralha`

* Jon viaja para além da Muralha;
* Jon encontra os selvagens;
* Jon knows nothing;
* Jon volta para Castelo Negro;
* Jon batalha contra os selvagens pelo Castelo Negro;
* Jon se torna lord comandante da Patrulha da Noite;

> Trocar de branch para `starks-em-porto-real`

* Ned morre decaptado em porto real
* Sansa fica presa em porto real como refém
* Arya foge tentando chegar ao Norte

> Fazer o merge dos dois branches criados

> Trocar de branch para `robb-em-riverlands`

* Rob é proclamado King in the Nooorth!!!
* Rob e Caitlyn "luta contra os Lannisters em riverlands"
* Rob se casa (não com uma frey)
* Rob e Caitlyn "morre no casamento vermelho"
* Bran e Rickon "é capturado por theon greyjoy em Winterfell"
* Bran e Rickon "é queimado em praça pública por Theon Greyjoy"

> Merge com master

> Trocar de branch para `winterfell-atacada`

* Rob é proclamado King in the Nooorth!!!
* Rob e Caitlyn "luta contra os Lannisters em riverlands"
* Bran e Rickon "é capturado por theon greyjoy em Winterfell"
* Bran e Rickon "foge com osha e holdor"

> Merge com master; apresenta-se conflito; resolve-se conflitos

> Aqui passou-se por todo o conteúdo. Agora já pode-se terminar, ser quisermos

> Trocar de branch para `starks-pelo-mundo`

* Sansa foge de porto real
* Sansa "se casa" com ramsay bolton
* Sansa foge de Winterfel para o vale
* Arya anda por todos os lados em westeros
* Arya conhece Jaqen H'ghar
* Arya vai treinar em bravos
* Arya forma-se uma "faceless man" (🤘)
* Arya volta a westeros e se vinga do casamento vermelho (🤘🤘🤘)
* Bran vai para norte com holdor
* Bran treina corvo de três olhos
* Bran torna-se o corvo de três "olhos" (🤘)
* Bran presencia a batalha da tower of joy

> Trocar de branch para `batalha-dos-bastardos`

* Jon é traído e morto pela Patrulha da Noite
* Jon ressussita, executa os traidores "and now my watch has ended"
* Jon parte para Winterfell, para enfrentar por Ramsay Bolton
* Jon luta na Batalha dos Bastardos e quase é derrotado
* Jon vence a batalha, com suporte da cavalaria do Vale
* Jon volta para Winterfell
* Jon prende Ramsay Bolton  (🤘🤘🤘)

* Sansa vai para o vale
* Sansa se encontra com Jon no Castelo Negro
* Sansa parte para Winterfell, para enfrentar por Ramsay Bolton
* Sansa consegue suporte da cavalaria do Vale
* Sansa vence a batalha, com suporte da cavalaria do Vale
* Sansa volta para Winterfell
* Sansa prende Ramsay Bolton
* Sansa executa Ramsay Bolton (🤘🤘🤘🤘🤘)
* Rickon capturado por ramsay bolton
* Rickon morre na batalha dos bastardos

> Merge com master

> Trocar de branch para `the-kids-are-back`

* Jon proclamado King in the Nooorth!!!
* Arya e Bran "volta para Winterfell"
* Sansa, Arya e Bran executa o Mindinho (🤘🤘🤘🤘🤘)