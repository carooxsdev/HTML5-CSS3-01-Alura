# HTML5-CSS3-01-Alura
Curso HTML5 e CSS3 parte 1- A primeira pÃ¡gina da Web da plataforma Alura online


##### Seletores Avançados CSS

-  Seletor ">" Para acessar os filhos de determinado elemento.  
	- Ex: Acessar todos os "p" dentro da "main"
	main > p {
}

- Seletor "+", para acessar o primeiro irmão de determinado elemento
	- Ex:  Acessar o primeito "p" após uma "img"

img + p {
}

- Seletor "~", para acessar todos os irmãos de determinado elemento.
	- EX: Acessar todos os "p" após um "img"
img ~ p {
}

- Seletor "not", Para acessar os elementos, exceto algum. Por Exemplo, para acessar todos os "p" dentro de "main", exceto "p" que tem "id" "missão":

main p:not(#missao) {
}

## Contas com "calc" no CSS