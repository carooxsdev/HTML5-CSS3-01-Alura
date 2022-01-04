# HTML5-CSS3-01-Alura
Curso HTML5 e CSS3 parte 1- A primeira página da Web da plataforma Alura online


##### Seletores Avan�ados CSS

-  Seletor ">" Para acessar os filhos de determinado elemento.  
	- Ex: Acessar todos os "p" dentro da "main"
	main > p {
}

- Seletor "+", para acessar o primeiro irm�o de determinado elemento
	- Ex:  Acessar o primeito "p" ap�s uma "img"

img + p {
}

- Seletor "~", para acessar todos os irm�os de determinado elemento.
	- EX: Acessar todos os "p" ap�s um "img"
img ~ p {
}

- Seletor "not", Para acessar os elementos, exceto algum. Por Exemplo, para acessar todos os "p" dentro de "main", exceto "p" que tem "id" "miss�o":

main p:not(#missao) {
}

## Contas com "calc" no CSS