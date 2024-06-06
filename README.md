# type conversion(conversão de tipo) / type coercion (coerção de tipo) 

...js
var x = nuber("0") //type conversion, nessa linha é feita uma conversão de tipo explicita

var y = "2" +3// type coercion, nessa linha é feita uma conversão implícito do valor 3 que é numerico (number) para texto (string)

//onde usa expresão condicional e repetição, faz necessário um valor boolean (true ou false).
//Ex:
   if(true){
}

 //caso não for informado uma expressão ou um valor boolean diretamente, ele fará um type coercion (coerção de tipo)
 //Ex:
 if(0) { //nessa linha ele ira fazer uma conversão do 0 para um boolean (verdadeiro ou falso ), nesse caso o será falso .}
...
