# dados
Geração de bases de dados para teste. A estratégia para o desenvolvimento do gerador será baseada em fases. A primeira delas é a léxica. 

### Requisitos versão léxica
1. Na fase léxica, o gerador simplesmente gera, conforme o tipo, um valor do domínio em questão.
  1. Alguns valores devem ser obtidos de domínios bem-definidos. Por exemplo, se um determinado atributo deve armazenar uma unidade de medida, então é desejável sortear uma unidade de medida dentre aquelas disponíveis, em vez de fazer uso de uma sequência qualquer de caracteres. 
 1. Ainda há cenários mais elaborados, por exemplo, endereço. Nesse caso, o logradouro e o número, além da cidade e do estado, deverão estar em conformidade com o CEP. 

### Links relevantes
- [Unisdades de medida](http://unitsofmeasure.org/ucum.html)
