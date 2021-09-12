Exercises from the third week - DevInHouse

# Exercícios da semana 3 do DevInHouse

## ex001

Faça uma página HTML contendo um label que exiba a mensagem “Insira sua data de nascimento”, um campo de texto que só permita inserir data (dica: input type date) e um botão rotulado “calcular idade”. Programe uma função a ser executada quando o usuário clicar no botão, que faça o cálculo da idade do usuário, e então exiba a idade em um texto na página HTML.

https://ex001-week3-devinhouse.netlify.app

## ex002 

Faça uma página HTML contendo 2 campos de texto (dica: input type number), para que o usuário possa inserir, em cada um, o valor que deseja calcular. Coloque também na sua página 4 botões, um indicando soma, outro subtração, outro multiplicação, e outro divisão. Adicione um outro campo de texto, apenas leitura (readonly). Quando o usuário clicar no botão de soma (multiplicação, divisão ou subtração), a sua página deve somar (multiplicar, dividir ou subtrair) os 2 valores inseridos pelo usuário e exibir o resultado no campo de texto readonly. Programe essa interatividade utilizando JavaScript.

https://ex002-week3-devinhouse.netlify.app

## ex003

Em uma página HTML, insira um campo de texto para que o usuário insira um número. Programe uma função em JavaScript para verificar se o número inserido pelo usuário é par ou ímpar, e informe o usuário através de um texto na página HTML.

https://ex003-week3-devinhouse.netlify.app

## ex004

Construa uma página HTML contendo um texto que informa o horário no momento de acesso, no formato “23:59” (HH:mm).

https://ex004-week3-devinhouse.netlify.app

## ex005

Construa uma página HTML contendo um texto que informa o horário atual, no formato “23:59”, e que atualize automaticamente o valor, sempre que mudar o horário.

ex005-week3-devinhouse.netlify.app

## ex006

Sua página deve conter um texto e uma imagem, ambos representando a estação. Ao carregar a página, baseado na data atual, seu código deve verificar qual a estação atual do ano no hemisfério sul, e deve alterar o texto e a imagem, para que passem a representar a estação correta. Considere: 22/12 a 21/03 - Verão; 22/03 a 21/06 - Outono; 22/06 a 21/09 - Inverno; 22/09 a 21/12 - Primavera.

ex006-week3-devinhouse.netlify.app (para testar é necessário mudar a data do computador e atualizar a página algumas vezes)

## ex007

Sua página deve possibilitar ao usuário inserir itens em uma lista e exibir a lista atualizada a medida que forem sendo adicionados novos itens. A página deve conter um rótulo (<label>) “Item a adicionar:” seguido de um campo de texto onde o usuário possa digitar o item. Deve conter também um botão “Adicionar”, que no momento do clique do usuário deve inserir o item digitado na lista. Se o texto estiver vazio (length), deve mostrar uma mensagem ao usuário solicitando a inserção de algum texto. A página também deve conter uma lista (<select>), que exibirá os itens adicionados pelo usuário.

## ex008

Utilizando a mesma página do exercício anterior, adicione um novo botão “Salvar lista”. Quando o usuário clicar nesse botão, a lista de itens de mercado deve ser salva no Local Storage do navegador.

## ex009

Utilizando a mesma página dos 2 exercícios anteriores ( [SP03] - Ex 7 e [SP03] - Ex 8 ), crie um novo botão “Carregar lista”, que ao ser clicado deve buscar no Local Storage se existe uma lista de itens de mercado salva, e em caso positivo deve mostrar os itens no elemento da página. Caso não haja nenhuma lista previamente salva, deve informar o usuário “Não há itens salvos”.

ex007-008-009-week3-devinhouse.netlify.app

## ex010

Na página HTML devem existir 2 campos de texto (dica: input type number): um rotulado (label) “valor inicial”, e outro rotulado “raíz”. Também deve ter 2 botões: um rotulado “Calcular P.A.” e outro rotulado “Calcular P.G.”. O evento click de cada botão deve chamar uma função que: verifica se os campos estão preenchidos (dica: length) e, se estiverem vazios, deve mostrar uma mensagem ao usuário pedindo para inserir os valores; caso os campos estejam preenchidos, deve calcular os 10 primeiros valores da sequência e exibir na tela. Relembrando: P.A. (Progressão Aritmética) é uma sequência numérica em que cada termo, a partir do segundo, é igual à soma do termo anterior com a raiz. Exemplo: Valor inicial = 1; raiz = 3; P.A. = 1, 4, 7, 10, 13, 16, 19, 22, 25, 28. P.G. (Progressão Geométrica) é como uma P.A., mas em vez de somar, multiplica-se a raiz. Exemplo: Valor inicial = 1; raiz = 3; P.G. = 1, 3, 9, 27, 81...

ex010-week3-devinhouse.netlify.app
