## BEM - Block Element Modifier

- blocos são containers,elementos pais algo que envolva outros elementos
- Elementos são filhos de blocos
- Modificadores são classes que permitem que sejam feitas novas estilizações
 
 #### Na imagem abaixo o elemento pai header que tem o nome da classe "topo" é pai do elemento "a" que tem o nome da classe do seu pai, mais o underline (__) seguido do nome do elemento no caso "topo__link"

<image src="./imagem/bem.png">


### Classe modificadora

- a classe modificadora é uma classe adicionada ao elemento que permite que sejam feitas alterações no CSS sem que a estilização ja feita seja alterada
- No exemplo abaixo foram adicionadas as classes modificadoras "grande" e "pequeno"

<image src="./imagem/classe-modificadora.png">

- O jeito correto de escrever o nome da classe modificadora é "topo__link--grande"

<image src="./imagem/jeito-certo-de-escrever-nome-classe.png">