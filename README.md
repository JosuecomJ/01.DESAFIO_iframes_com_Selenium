### 02. Coletando dados de tabelas em Iframe via Selenium
 
O projeto tem o intuito de coletar dados dentro de sites que possuem multimplos iframes, e existe a necessidade de ultilizar o scroll no iframe

#### _Para encontrar a div onde o scroll sera aplicado use o seguinte codigo Javascritp no console do navegador:_
```]
var elements = document.getElementsByTagName("div");

for (var i = 0; i < elements.length; i++) { if (elements[i].scrollHeight > document.getElementsByTagName("body")[0].scrollHeight) {
console.log(elements[i]);
console.log(elements[i].scrollHeight);
}}
```

ao passar o mouse sobre as divs no console você consiguirar encontrar a div onde deseja ultilizar o scroll. 
