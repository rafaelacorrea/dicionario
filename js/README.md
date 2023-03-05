# JavaScript

## Variáveis: 
são os locais onde vamos armazenar as informações na memória e quando precisamos conseguimos acessá-las para obter ou alterar alguma informação contida dentro dela. Veja abaixo sua estrutura:

```javascript
var nomeDaVariavel = "valor"
```

## Array: 
É quando precisamos armazenar muitos valores numa única variável. Para isso, utilizamos os colchetes.

```javascript
var guardaRoupa = ["camisa","camiseta","roupa de cama","calça","peça íntima","toalha"];
```

## Objetos: 
O objeto permite que a gente adicione e agrupe informações de forma mais categórica, facilitando a organização dessas informações.

```javascript
var guardaRoupa = {
    "camiseta01":{manga: "curta", estampa:"lisa", tamanho: "grande"},
    "camiseta02":{manga: "longa", estampa: "listrada", tamanho: "pequeno"}
    };
```

## Estrutura de repetição:

### for
Nos permite criar repetições de um determinado ciclo, seja percorrendo uma array ou objeto. É indicado para criarmos iteração em objetos. Dentro do for() atribuímos uma variável que irá receber as informações referentes aos objetos que iremos percorrer.

```javascript
for(item in camiseta){
    console.log(item += camiseta[item]);
}
```

## DOM

DOM significa Document Object Model, que em português significa Modelo de Documento do Objeto. iremos percorrer.

innerHTML: O innerHTML serve para a gente incluir trechos de códigos HTML dentro do nosso documento. Conseguimos acessá-lo através de atributos que permitem identificar classes e ids. Como vocês já sabem como funciona o getElementById(), podemos utilizá-los para encontrar os ids e incluir o HTML.

```html
document.getElementById("id").innerHTML = "<tag></tag>"
```