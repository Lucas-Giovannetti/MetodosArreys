# MetodosArreys
POC 2 sobre metosdos de arrey em JS
reduce()
Reduz o array a um único valor aplicando uma função acumulativa. Muito útil quando você quer somar, multiplicar ou combinar de um array em uma única resposta.
 
1.  O .map() transforma o array original em [7, 8, 8.5] (um array apenas com as notas).
 2. O .reduce() percorre esse array:
⦁	Primeira iteração: accumulator é 0 (valor inicial), currentValue é 7. Então, 0 + 7 = 7
⦁	Segunda iteração: accumulator é 7, currentValue é 8. Então, 7 + 8 = 15
⦁	Terceira iteração: accumulator é 15, currentValue é 8.5. Então, 15 + 8.5 = 23.5

.sort()
Quando o método .sort() é chamado sem uma função de comparação, ele converte os elementos do array em strings (se não forem strings) e os ordena com base na sequência de caracteres Unicode.  Isso pode levar a resultados inesperados, especialmente ao ordenar números.
 
.filter()
 
O que o .filter() faz aqui:
⦁	Array original: Você tem um array de idades: [20, 23, 22].
⦁	Função verify: A função verify(age) recebe cada valor do array idades como argumento (age) e compara com o valor que o usuário digitou no campo de entrada. A função retorna true se age for maior que o valor inserido.
⦁	Filtro: O .filter() aplica a função verify a cada elemento do array idades. Se o resultado for true, o elemento será incluído no novo array.
⦁	Exibição: O novo array filtrado (com idades maiores que o valor digitado) é exibido no HTML.
 
