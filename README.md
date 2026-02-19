# Road-to-First-Job: Minha Jornada Fullstack 2026

Retornei aos estudos de programação em 2026 com um objetivo claro: conquistar minha primeira vaga como desenvolvedor até o fim do ano. Criei este repositório para documentar minha jornada, consolidar meu aprendizado e servir como portfólio técnico.

Atualmente, meu foco total está nos fundamentos do JavaScript. Acredito que dominar a base da linguagem me permitirá criar um framework mental sólido para aprender qualquer tecnologia no futuro. Utilizo este espaço para mapear meu progresso, identificar lacunas de conhecimento (gaps) com auxílio de IA e manter uma rotina de atualização semanal.

Atualizado: 15/02/2026

⚙️ [Utilitários](utilitarios.md)
📅 [Log de Estudos](logs.md)

## Javascript
### Variáveis
✅ O que são variáveis 
✅ Como criar uma variável e atribuir valores  (`var`, `let` e `const`)
✅ Como nomear as variáveis e usar a convenção do camelCase e snake_case
✅ Hosting e TDZ em variáveis  `var`, `let` e `const`
	✅ Como o código javascript é executado duas vezes
✅ O fato do javascript não ser uma linguagem tipada 
✅ Como usar o `typeof` para verificar o seu tipo 
	✅ `typeof null` retorna `'object'` que é um erro da linguagem
✅ Quais os três tipos de variáveis (`var`, `let` e `const` )
	✅ Diferença entre elas
	✅ E as regras de escopo de cada 
✅ Quais os 6 tipos primitivos em javascript (Number, string, boolean, null, undefined)
✅ Diferença entre `null` e `undefined` 
✅ Usar o `Bigint()` e suas particularidades 
✅ Os erros de não usar o ponto e virgulas explicitamente causado pelo ASI do JS

### Operações matemáticas 
✅ Os 6 operadores básico de matemática 
✅ Como funciona a ordem de procedência com os operadores matemáticos 
✅ Como elevar a prioridade de operações matemáticas usando `()`
✅ O fato que o javascript não tem um boa precisão matemática para casas decimais grandes
	✅ Não tem precisão em cálculo para números inteiros maior que o tamanho máximo ideal 
✅ O que é o `NaN` e quando ele ocorre 
	✅ Diferença entre o função `isNaN()` e o método `Number.isNaN()`
✅ Usar os operadores de atribuição composta
	✅  `x += 3;` ,  `x -= 3;`, `x *= 3;` e `x /= 3;`
✅ Usar os operadores unários de incremento e decremento
	✅ `x++;` e `x--;`
	✅ Diferença entre Pós-incremento e pré-incremento
✅ Alguns funcionalidades do modulo `Math`
✅ Criar números de forma "aleatória" usando o `Math.random()`
✅ Usar o Numeric separators para melhor a visualização de números grandes

### String
✅ O que são strings
✅ Criar strings usando aspas simples e dupla 
✅ Como concatenar string usando `+` 
✅ Usar *template string* para usar junto com variáveis 
✅ Acessar os caracteres individualmente usando a notação de colchete `[x]`
	✅ Descobrir o tamanho da string usando `.length`
	✅ Acessar index invalido vamos receber `undefined`
✅ O fato que as strings são imutáveis 
✅ Usar os principais métodos para manipular string 
✅ Encadear vários métodos de manipulação 
✅ Fazer o parse de `string` numéricas para tipo numérico usando `parseInt` e `parseFloat`

### Operadores Lógicos e condicionais 
✅ O que são os operadores lógicos 
✅ Diferença entre o `==` e `===` e também o `!=` e `!==`  
	✅ Quando acontece a coerção 
	✅ Como o valor e o tipo são avaliados na comparação 
✅ Usar os operadores de magnitude `>`, `<`, `<=`, `>=` 
✅ Usar os operadores lógicos `!` (not),  `&&` (AND) e `||` (OR) e ordem de precedência 
✅ Todos os valores considerados *falsy* (`false`, `0`, `""`, `null`, `undefined` e `NaN`) em condições 
✅ Usar condicionais `if`, `else if`, `else` e `switch` 
	✅ Usar condicionais aninhadas 
✅ Usar o operador ternário `condição ? _true : _false`
✅ Usar o Nullish Coalescing Operator (`??`) 
✅ Usar o OR Assignment (`||=`),  And Assignment (`&&=`) e Nullish Assignment (`??=`)

### Estruturas de Dados 
#### Arrays 
✅ O que são os Arrays e casos de uso
✅ Mutabilidade dos arrays
✅ Criar e atribuir valores a estrutura de dados Array
✅ Usar os seus principais métodos de manipulação 
✅ Acessar os elementos individualmente e alterar os valores
✅ Descobrir o tamanho do array 
✅ Calcular a relação entre os índices e o tamanho do array `length -1`
✅ Não obter `undefined` ao tentar acessar um elemento que não existe 
✅ Como é armazenado na memória usando referencia  
	✅ Copiar array usando a sua referencia 
	✅ Criar um cópia superficial do array
✅ Lidar com arrays multidimensionais 
✅ Percorrer os elementos do array usando o `for of`, `for` tradicional e `while`
	✅ Loops aninhados usando arrays multidimensionais
	✅ Usar as palavras chave `break` e `continue` em condicionais 
✅ Usar os métodos `forEach`, `map`,  `find`, `filter`, `every`, `some`, `sort` e `reduce`
✅ Usar os operador `rest` e `spread` 
	✅ Criar uma cópia superficial de um array 
	✅ Espalhar elementos do arrays
	✅ Agrupar dados elementos 
✅ Usar o Destructuring 
	✅ Separar os elementos individualmente em variáveis
	✅ Pular elementos quando necessário
	✅ Usar integrado com o operador `rest`
✅ Usar o `Array.at()` para acessar elementos do array 
✅ Usar o `Array.from()` para criar novos arrays ou manipula-los

#### Objetos
✅ O que são objetos e casos de uso 
✅ Criar objetos literais 
✅ Como os objetos são salvos na memória 
✅ Acessar as propriedade usando notação de `.` e `[key]`
	✅ Tudo colocado entre colchete é convertido para string 
	✅ Podemos usar variáveis e string (fora do padrão de nomeação das variáveis) no colchete
✅ *Shorthand Properties* e *Computed Properties* em objetos literais 
✅ Não obter `undefined` ao tentar acessar uma propriedade que não existe 
✅ Criar métodos em objetos literais
✅ Percorrer as propriedades usando o `for in`
✅ Percorrer as propriedades usado o `for of` junto com o `Object.keys` ou `Object.values`
✅ Usar os operador `rest` e `spread` 
	✅ Criar uma cópia superficial de um objeto
	✅ Atualizar as propriedades de um objeto
✅ Usar o Destructuring 
	✅ Criar variáveis com o mesmo nome das chaves para separas as propriedades 
	✅ Criar variáveis com nome diferente das chaves 
	✅ Usar integrado com o operador `rest`
✅ Diferença ao usar funções anonimas e arrow function como métodos em objeto literais 
✅ Usar o `this` corretamente em objetos literais dentro nos método
	✅ `this` dentro de funções anonima e arrow function 
✅ Como criar objetos a partir de classes
✅ Como instanciar uma classe 
✅ Como acessar os atributos de uma classe
✅ Como criar um método dentro de uma classes
	✅ A diferença entre usar função anonima e arrow function e como isso impacta no `this`
✅ Como executa um método de uma classe 
✅ Como usar um atributo de uma classe em um método
✅ Como usar o `this` dentro de uma classe 
✅ Como funciona a classe construtora
✅ Como estender as propriedades e métodos de uma classe modelo usando o `extends`
✅ Como usar o método `super()` no construtor 
✅ Sobre o que faz o `new` por trás dos panos 
✅ Verificar se um objeto e uma instancia de um classe específica usando o `instanceof`
✅ Fato que as classes são uma sintax simplificada das funções construtoras e `prototype`
✅ Criar propriedade e métodos estáticos usando o `static`
	✅ Alguns contextos de uso
	✅ O valor do `this` em um método `static`
	✅ E como não devemos tentar acessa-los após instanciar a classe 
✅ Como usar os métodos `get` e `set` e contexto de uso 
✅ Como criar atributos e métodos declarados como públicos e privados 
	✅ Como usar a sintaxe antiga usando `_` para definir como privado 
✅ Como usar o Optional Chaining (`?.`) para lidar com dados incompletos 


### Funções 
✅ O que são funções e casos de uso 
✅ Criar funções nomeadas, anônimas e arrow functions 
✅ A importância de obedecer a sequência da ordem dos parâmetros
	✅ Quando os parâmetros recebem valor `undefined` quando não são atribuídos
✅ Executar funções 
✅ Retornar valores usado uma função 
	✅ Função sem retorno retorna `undefined` implicitamente 
✅ Diferença entre declaração de função e expressão de função
✅ Definir funções com parâmetros e usar parâmetros com valor padrão 
✅ Chamar uma função e passar argumentos
✅ Passar uma função para uma: 
	✅ Variável, 
	✅ No parâmetro para outra função
	✅ Retorna função dentro de outra função 
✅ O que são High Order function (callback e factory)
✅ Usar o `return` da função para implementar uma *guard clauses*
✅ Escopo de função e escopo léxico com funções aninhadas 
✅ O que são Closure em uma função aninhadas 
✅ Hosting e TDZ em declaração de função e expressão de função 
✅ Usar os operador `rest` e `spread` 
	✅ Criar funções com número indefinido de parâmetros
	✅ Espalhar elementos de um array no argumentos 
	✅ Coletar argumentos não previstos 
✅ Usar o Destructuring 
	✅ Separar os elementos individualmente de um objeto no parâmetro
	✅ Separar os elementos individualmente de um array no parâmetro
	✅ Usar integrado com o operador `rest`
✅ O que são e como usar Funções Geradoras (Generators) e suas particularidades

### Prototype
✅ O que é o protoype 
✅ O que é o prototype chain 
✅ String, Arrays e Objeto tem a propriedade `__proto__`
	✅ Referencia da class de prototype de onde herdam atributos e métodos 
✅ `Array.prototype` é a classe de prototype em si 
✅ Criar métodos personalizados e colocar no `prototype`
✅ Como o `prototype` traz um componente de eficiente para o Javascript
✅ Fato que quando usamos o `extends` estamos adicionando mais um nível a *prototype chain*

### Navegador
✅ O que é o DOM e `document` o seu ponto de entrada 
✅ Como selecionar um `node` do DOM e quais são as formas
✅ Descobrir os descendentes de um `node` e seleciona-lo 
✅ Verificar se um elemento é descendente de outro 
✅ A diferença entres os *Array-like* `HTMLCollection` e `NodeList`
	✅ Como percorrer os items e quais métodos podemos usar
	✅ Como converter para um Array 
✅ Acessar e modificar as propriedades de um elemento 
✅ Acessar e modificar as propriedades que não são nativas dos elementos
✅ Modificar o estilos visual dos elementos 
✅ Como criar elementos com javascript e adicionar ao DOM
✅ Remover elementos do DOM 
✅ Aplicar e remover classes em um elemento 
✅ Adicionar vários tipos de eventos a um elemento
✅ Funcionamento dos eventos por trás dos panos 
✅ Manipular o objeto de `Event` de um evento e acessar as propriedades 
✅ Lidar corretamente com eventos de tags de formulário 
✅ Acessar as propriedades de `dataset` dos elementos
✅ Manipular e obter as informações da barra de endereço 
	✅ As três formar de mudar de paginas usado o javascript
	✅ Acessar todas as partes individualmente da URL

### Assincronismo 
✅ O que é o assincronismo e porque ele existe no javascript
✅ Como as funções assíncronas são executadas por baixo dos panos
✅ O que é uma `Promise` 
✅ Como é o objeto que a `Promise` retorna
✅ Como criar e manipular uma `Promise`
✅ Os três estados da `Promise` 
✅ Como usar os métodos `.then()` e `.catch()` 
✅ A evolução da sintaxe das promises com `async/await` 
✅ Como usar o `async/await` 
✅ Como o `async/await` funciona por baixo dos panos 
✅ Qual o retorno de uma função `async` 
✅ As formas de lidar com errors com `async/await`
✅ Diferença em resolver uma `Promise` em sequencia e em paralelo usando o `Promise.all()`
✅ Como usar o `fetch` API e as suas particularidades 
✅ Como usar o `axios` para fazer requests 
✅ Como usar o `Promise.any([...])` 

### Node.js
✅ O que é o Node.js 
✅ Como instalar o Node.js e o npm 
✅ O que é o NPM
✅ Executar código javascript usando o Node.js
	✅ Usar o REPL ou executar um arquivo .js
✅ Diferença de escopo de um arquivos .js no navegador e no Node.js
✅ Para que server os modulos
✅ Como criar modulos personalizados 
✅ Como usar os modulos nativos do Node.js
✅ Como importar e exportar os modulos personalizados
✅ O que é o `require.cache` no Node.js quando exportamos um modulo
✅ Diferença entre o Cammon Js e o `import from`
✅ Como o código executado pelo Node.js é encapsulado por uma função invisível 
	✅ A função tem 5 parâmetros por padrão 
	✅ Quais são eles e como usar 
✅ Como usar o objeto global `process`, suas propriedades e métodos
✅ Como usar as funções dos modulos nativos baseado em callback *erro-first*
✅ Como usar as versão em `Promise` das funções dos módulos nativos 

### Express
✅ O que é o `express`
✅ Como criar um servidor `express` e especificar a porta de acesso
✅ Como criar aquivos de rotas em arquivos separados 
✅ O que são middleware, como criar e usa-la 
	✅ Quais os parâmetros são passados para ela
	✅ Como adicionar informação no request 
✅ Criar uma *route handler* para responder request 
✅ A diferença entre  `POST`, `GET`, `DELETE`, `PUT` e `PATCH` 
✅ Quais os parâmetros a *route handler* tem acesso
✅ Como receber e tratar informações dos campos de formula do *front-end*
	✅ Fazer a sanitização e a validação usando `express-validator`
✅ O que é o *body parse* para tratar informações do tipo *url enconded*
	✅ Usar essa middleware para esperar o body request 
✅ Entendi o porquê do header do request chega primeiro que o body 
✅ A diferença entre a propriedade `method` e `enctype` da tag `<form>`
✅ Fazer upload de arquivos 
✅ Diferença entre o`enctype` do `x-www-form-urlencoded` e o `multipart/form-data`
✅ Como extrair as informações do `enctype=multpart/form-data`
✅ Como utilizar cookies de sessão e quais informações podemos adicionar nele
	✅ Como invalidar um cookie 
✅ A maneira correta de salvar senha no banco de dados
	✅ Usar algoritmo de hash com salt 
	✅ Validar a senha usando hash 
✅ Como diferenciar request para rotas com `router handler` e arquivos estáticos
	✅ Porque devemos verificar se uma rota de arquivo estático logo ao receber o request

### package.json
✅ O que é esse arquivo
✅ Como criar esse arquivos 
✅ Como instalar dependências
	✅ Quando ou não usar a flag `--dev`
✅ Como restaurar as dependências do projeto quando excluir a pasta `node_modules`
✅ Como criar scripts personalizados para executar tarefas no `"script"`
✅ Como criar comandos CLI personalizados no  `"bin"`

### Outras informações 
✅ Criar um canvas usando SVG para criar formas e manipular usando o javascript
✅ O que é um debounce e como usar para reduzir a quantidade de requests ao server 
✅ Codificar um string para se tornar um *URL friendly* usando `btoa()` e 
	✅ Retorna para estado original usando `atob()`
✅ O que é o um arquivo XML e JSON
✅ Os 3 canais de comunicação de um processo quando e criado 
✅ O que é um terminal e qual a sua função 
✅ O que é o Shell do terminal 

## Referencias
### Cursos 
✅  [[[The Modern Javascript Bootcamp Course]]](https://www.udemy.com/course/javascript-beginners-complete-tutorial/)
⏳ [JavaScript Pro: Mastering Advanced Concepts and Techniques](https://www.udemy.com/course/pro-javascript/)
⏳ [JavaScript Algorithms and Data Structures Masterclass](https://www.udemy.com/course/js-algorithms-and-data-structures-masterclass/)
