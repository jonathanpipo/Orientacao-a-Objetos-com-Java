# Orientação a Objetos com Java
Coursera: https://www.coursera.org/learn/orientacao-a-objetos-com-java

### Avaliações
#### :white_check_mark: Módulo 1 - Calculadora IMC 
Implemente no Eclipse uma classe chamada Paciente que possui um construtor que recebe o seu peso em quilos e sua altura em metros, ambos utilizando o tipo double. Crie um método chamado calcularIMC() que calcula o índice de Massa Corporal de acordo com a fórmula IMC = peso (quilos) / (altura * altura (metros)). Crie também um método chamado diagnostico() que utiliza o método calcularIMC() e retorna uma String de acordo com as seguintes faixas de valor:

* Baixo peso muito grave = IMC abaixo de 16 kg/m².
* Baixo peso grave = IMC entre 16 e 16,99 kg/m².
* Baixo peso = IMC entre 17 e 18,49 kg/m².
* Peso normal = IMC entre 18,50 e 24,99 kg/m².
* Sobrepeso = IMC entre 25 e 29,99 kg/m².
* Obesidade grau I = IMC entre 30 e 34,99 kg/m².
* Obesidade grau II = IMC entre 35 e 39,99 kg/m².
* Obesidade grau III (obesidade mórbida) = IMC igual ou maior que 40 kg/m².

Implemente no Eclipse uma classe chamada Principal em que se criam 3 instâncias da classe Paciente com valores diferentes e se imprime no console o resultado dos dois métodos criados.

<hr>

#### :white_check_mark: Módulo 2 - Pizzaria
Crie uma classe Pizza que possua o método adicionaIngrediente() que recebe uma String com o ingrediente a ser adicionado. Essa classe também deve possuir o método getPreco() que calcula da seguinte forma: 2 ingredientes ou menos custam 15 reais, de 3 a 5 ingredientes custam 20 reais e mais de 5 ingredientes custa 23 reais.

É preciso contabilizar os ingredientes gastos por todas as pizzas! Utilize uma variável estática na classe Pizza para guardar esse tipo de informação (dica: utilize a classe HashMap para guardar o ingrediente como chave e um Integer como valor). Crie o método estático contabilizaIngrediente() para ser chamado dentro de adicionaIngrediente() e fazer esse registro.

Crie uma nova classe chamada CarrinhoDeCompras que pode receber objetos da classe Pizza. Ela deve ter um método que retorna o valor total de todas as pizzas adicionadas. O Carrinho não pode aceitar que seja adicionada uma pizza sem ingredientes.

* Crie uma classe Principal com o método main() que faz o seguinte:

* Cria 3 pizzas com ingredientes diferentes

* Adiciona essas Pizzas em um CarrinhoDeCompra

* Imprime o total do CarrinhoDeCompra

* Imprime a quantidade utilizada de cada ingrediente

      
 
