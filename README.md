## O INICIO:

Na minha busca incessante para descobrir como fazer o dito cujo desafio, eu busquei ajuda com um mentor que me deu orientações e eu tive uma ideia um tanto quanto muito boa. Dai, eu peguei a ideia de um rpg simples com mensagens e pequenos comandos de texto sendo eles 1 e 2 para ambos ataque e defesa como um Jogador x Inimigo.

Então, estudando a fundo eu dei uma olhada breve em bibliotecas do Swift e vi que a Foundation é mais adequada para o caso apesar de que não seja necessária colocar o “import” no código, mas há situações em que você precisará dela que pelo que eu vi são:

1. **Manipulação Avançada de Strings:** Operações mais complexas que vão além das capacidades básicas da Standard Library que eu usei no swift
2. **Operações de Arquivo:** Ler e escrever arquivos no sistema de arquivos e Etc
3. **Coleções Avançadas:** Utilizar estruturas de dados mais sofisticadas que não estão disponíveis na Standard Library

Fonte: https://www.swift.org/documentation/core-libraries/

obs: porém, como gosto de organização optei por colocar, vai que da algum erro né 👀.

## ESTRUTURAÇÃO:

Utilizei a “class” pois é uma estrutura que permite criar objetos com propriedades (variáveis) e métodos (funções) com comportamentos específicos para criar entidades.

Já a “var” ou variavel usei para que um valor possa ser alterado após sua inicialização.

O “init” para configurar propriedades iniciais.

‘Self” se referindo à instância atual da classe. Usado para distinguir entre propriedades da classe que tem o mesmo nome.

O “func” usei para declarar uma função ou método.

O “if” para executar o código condicionalmente, dependendo de uma expressão booleana.

Usei o “guard let” tentando descompactar o valor retornado por “read line”. Se for nil, a função retornara uma string vazia. caso nao, continua com o valor descompactado.

O “return” pra encerrar a execução de uma função.

“let” par não mudar um valor apos a inicialização.

“while” para quando a condição booleana for verdadeira.

“switch” pra permitir selecionar entre múltiplas opções.

“case” definir os diferentes casos a serem tratados.

”default” pra definição de um caso padrão quando nenhum dos casos anteriores é correspondido.

e por fim o “break” para sair de um loop principal quando o jogo termina.

Fonte: Aula 2 de Swift do Capacita Brasil.

## CONCLUSÃO

A conclusão que eu tive foi que compreender esses conceitos fundamentais de Swift é essencial para desenvolver programas eficientes e bem estruturados. No contexto do meu RPG esses elementos trabalham juntos para criar uma experiência interativa onde personagens podem atacar, defender e interagir com base nas escolhas do jogador.
