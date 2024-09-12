# MetodosArreys
POC 2 sobre metodos de arrey em JS


##.reduce()
Reduz o array a um único valor aplicando uma função acumulativa. Muito útil quando você quer somar, multiplicar ou combinar de um array em uma única resposta.
 ![image](https://github.com/user-attachments/assets/33ceedec-f2fc-463b-8c54-9836c81387f9)

O metodo .map(function) cria uma nova arrey utilizando os dados da arrey base, o metodo não lê dados nulos e não altera a arrey original.
1.  O .map() transforma o array original em [7, 8, 8.5] (um array apenas com as notas).

![image](https://github.com/user-attachments/assets/3b407a04-741c-45c8-bb61-ffdf7b9f4696)

 2. O .reduce() percorre esse array:
*	Primeira iteração: accumulator é 0 (valor inicial), currentValue é 7. Então, 0 + 7 = 7
*	Segunda iteração: accumulator é 7, currentValue é 8. Então, 7 + 8 = 15
*	Terceira iteração: accumulator é 15, currentValue é 8.5. Então, 15 + 8.5 = 23.5

##.sort()
Quando o método .sort() é chamado sem uma função de comparação, ele converte os elementos do array em strings (se não forem strings) e os ordena com base na sequência de caracteres Unicode.  Isso pode levar a resultados inesperados, especialmente ao ordenar números.

 ![image](https://github.com/user-attachments/assets/0a869b74-12b8-439f-8d1f-8a6134a940ff)

##.filter()

 ![image](https://github.com/user-attachments/assets/c18d6622-d1d8-4d4b-b630-0bed383aa658)

O que o .filter() faz aqui:
*	Array original: Você tem um array de idades: [20, 23, 22].

*	Função verify: A função verify(age) recebe cada valor do array idades como argumento (age) e compara com o valor que o usuário digitou no campo de entrada. A função retorna true se age for maior que o valor inserido.

*	Filtro: O .filter() aplica a função verify a cada elemento do array idades. Se o resultado for true, o elemento será [Uploading index.html…]()
incluído no novo array.

*	Exibição: O novo array filtrado (com idades maiores que o valor digitado) é exibido no HTML. (O metodo não executa a funçãocom elementos nulos e não altera o arrey original)

 
![image](https://github.com/user-attachments/assets/435c23f4-f43f-4472-a616-dcb8f104afd7)

O "..." também conhecido como spread serve para concatenar dados de arrays, sejam elas variaveis ou retorno de funções, como visto nas seguintes linhas de código:

![image](https://github.com/user-attachments/assets/0227041a-0de5-40b3-b275-04a102af4778)

Resultando na concatenação dos dados em sequência:

![image](https://github.com/user-attachments/assets/87c53b7d-f698-4ac9-b575-de0ad81f6c63)


