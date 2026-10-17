# Agenda de Tarefas Pessoal

## 1. Nome e tema do projeto

O projeto se chama **Agenda de Tarefas Pessoal** e tem como objetivo representar uma agenda simples para organizar as tarefas do dia e acompanhar o desempenho das atividades concluídas.

O projeto foi desenvolvido como parte de uma atividade acadêmica sobre JavaScript ES6 e Bootstrap.

## 2. Explicação da interface

A interface foi planejada para apresentar informações relacionadas às tarefas diárias, como a quantidade total de tarefas, as tarefas concluídas e as tarefas pendentes.

O objetivo é criar uma página simples, organizada e responsiva, utilizando os componentes do Bootstrap.

## 3. Componentes do Bootstrap utilizados

Os componentes e classes utilizados na interface são:

- **Navbar:** apresenta o nome do projeto.
- **Container:** organiza o conteúdo da página.
- **Row e Col:** organizam os elementos em linhas e colunas responsivas.
- **Card:** apresenta informações sobre as tarefas.
- **Badge:** identifica o status de uma tarefa.
- **Button:** representa uma ação disponível na interface.
- **Alert:** exibe uma mensagem informativa.
- **Footer:** apresenta informações no final da página.

O Bootstrap foi incluído por meio de CDN, sem a necessidade de criar um arquivo CSS próprio.

## 4. Diferença entre let, const e var

Durante a atividade, foram utilizadas diferentes formas de declarar variáveis em JavaScript.

- **const:** utilizada quando o valor da variável não for ser alterado.
- **let:** utilizada quando o valor da variável precisa ser alterado.
- **var:** uma forma mais antiga de declarar variáveis, que possui diferenças de escopo em relação a `let` e `const`.

No projeto, utilizei principalmente `const` e `let`, pois permitem escrever um código mais organizado e com escopo mais previsível.
Mas também utilizei `var` no exercicio solicitado.

## 5. Tipos de dados utilizados

Foram praticados os seguintes tipos de dados:

- **String:** representa textos, como o nome do projeto.
- **Number:** representa números, como a quantidade de tarefas.
- **Boolean:** representa um valor verdadeiro ou falso.
- **Null:** representa a ausência intencional de um valor.

Esses tipos foram utilizados para armazenar informações relacionadas à agenda e exibir os resultados no Console do navegador.

## 6. Operadores utilizados

Foram utilizados operadores matemáticos e de comparação para realizar cálculos relacionados às tarefas.

- **Adição (+):** soma valores.
- **Subtração (-):** calcula a quantidade de tarefas restantes.
- **Multiplicação (*):** calcula valores derivados da quantidade de tarefas.
- **Divisão (/):** auxilia no cálculo da porcentagem de tarefas concluídas.
- **Comparação (>= e <):** compara a porcentagem concluída com a meta estabelecida.

Essas operações ajudam a praticar a lógica de programação utilizando situações relacionadas ao projeto.

## 7. Condição com if e else

Foi criada uma condição para avaliar a porcentagem de tarefas concluídas no dia.

Quando a porcentagem é menor que 50%, o programa exibe uma mensagem de baixo desempenho. Quando a porcentagem é igual ou superior a 50%, o programa exibe uma mensagem de ótimo desempenho.

Essa condição permite praticar decisões em JavaScript com base nos valores armazenados nas variáveis.

## 8. Template literals

Foram utilizados template literals para montar mensagens dinâmicas no Console.

Com essa funcionalidade, é possível inserir valores de variáveis diretamente em uma string utilizando `${}`.

## 9. Console do navegador

O Console foi utilizado para exibir mensagens, verificar valores das variáveis, visualizar os resultados dos cálculos e testar as condições criadas com `if` e `else`.

A função `console.log()` ajudou a acompanhar a execução do código durante o desenvolvimento.

## 10. Maior dificuldade encontrada

Minha maior dificuldade foi compreender a lógica do cálculo da porcentagem de tarefas concluídas e utilizar esse resultado corretamente na condição `if` e `else`.

Inicialmente, a ordem das variáveis na divisão estava incorreta, o que gerava um resultado diferente do esperado.

## 11. Como a dificuldade foi resolvida

A dificuldade foi resolvida revisando a fórmula da porcentagem, dividindo a quantidade de tarefas concluídas pelo total de tarefas e multiplicando o resultado por 100.

Depois, utilizei esse valor para comparar o desempenho com a meta de 50%, verificando se a condição apresentava o resultado esperado.

## 12. Tecnologias utilizadas

- HTML5
- JavaScript ES6
- Bootstrap via CDN

## 13. Estrutura do projeto

```text
atividade-js-bootstrap/
├── index.html
├── app.js
└── README.md
```

## 14. Conclusão

A atividade permitiu praticar os conceitos iniciais de JavaScript, incluindo variáveis, tipos de dados, operadores, template literals e estruturas condicionais.

Também possibilitou conhecer os componentes do Bootstrap e compreender como organizar uma interface web de maneira simples e responsiva.
