# Brincando com o HTML (André, Sira & Waira)

## Links.
* https://www.deeplearning.ai/ site para aprender machine learning
* https://ai.google/education/ site da google para aprender machine learning
* Coursera tambem tem aulas com o Andrew Ng.
* https://www.udemy.com/ Tem cursos de ciencias da computação. Tem aulas de qualquer um então tem que ter cuidado. Tem um cara chamado Jose Portilla tem cursos bons. 
* https://fonts.google.com/ fontes do google.

## HTML:
* http://getbootstrap.com/ Site para fazer uma página de internet
* w3schools.com da para tirar dúvidas sobre o html
* https://startbootstrap.com/ Aqui tem template de graça
* O html é uma inguagem de marcação!
* atom.io 

### Abre o atom e começar a criar o html
	1. Cria uma pasta clica com o botão direito, escolher new file -> index.html. Aqui nós criamos um documento html.
	2. <> abre um elemento, </> fecha o elemento. Sempre começa com <html> e termina com </html>
	3. <!-- coloque o comentario aqui -->
	4. todo html tem head & body. O body é onde tera todas as informações. O head tem os metadados, ele não aparece na pagina. Pode pegar algo pronto.
	5. h1 a h6 cabeçalhos, o um é o cabeçalho maior. 
	6. p é para escrever paragrafo
	7. salva com ctr+S e da pra abrir o index no chrome
	8. Head: não vai ser renderizado. Ele vai aparecer como o titulo na aba na internet. Nunca vai aparecer no browser. 
	9. Body: tudo que será renderizado. Tudo que colocamos aqui será o texto da página. 
	10. a. Ancora. Serve como link. coloca <a href="Colocar o link que é pra colocar"> Ex. <a href="http://www.unb.br/">Este é um link</a>
	11. Tem dois tipos de elemento. 1) em bloco e 2) linha
	12. Ul unordened list (coloca pontinhos) item e il list item ol ordered list (coloca numeros na lista)
	13. da para colocar listas dentro de listas

### CSS: Estilizar o html (cascade style sheet)
	1. Adicionar o estilo. Criar um arquivo stye.css
	2. Para dizer ao index que queremos colocar um estilo css, abrir um link (não fecha)   <link rel="stylesheet" type="text/css" href="style.css"> com isto linkamos.
	3. trocar o estilo de cada h: abre {, aplica para todo elemento h especificado. ex. color: red; (e fecha). Assim todos os h selecionados ficarão vermelhos. Da pra colocar o rgb (red green blue) e colocar os valores color: rgb(2,3,1)
	4. Se você muda em outra linha embaixo a cor, o ultimo terá preferencia. 
	5. Para mudar a fonte font-famiy: "Arial", se não tiver colocar o nome da fonte depois
	6. Sempre colocar o ; no final.
	7. Se no index colocar a classe depois do h, da para mudar os atributos de cada h mesmo sendo um mesmo tipo de h . Se colocar o numero do h.red assim muda somente do h1, se não vai mudar para todos os que tem essa classe
	8. Um elemento pode ter mais que uma classe, separa por espaço. 
	9. Div: caixinha que organiza conteudo. Da pra colocar classes. 
	10. id para elementos que são únicos. O elemento é demominado de Id, então o nome específico daquele elemento é o id.
