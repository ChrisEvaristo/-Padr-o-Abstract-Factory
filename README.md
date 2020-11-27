# -Padr-o-Abstract-Factory



 Intent-> é padrão criacional, comum em frameworks, possui um nível maior de abstração que Factory  Method. Fornece  uma interface para criar  familia de objeto dependentes.
 
 
 Objetivo ->  Prover  uma interface para criar uma família  de objetos  relacionados . Reduzir acoplmento  entre objetos  mesmo  quando estes tem depend~encias entre eles.
 
 
 Motivation ->  Cliente precisa  criar  determinados  objetos cuja  construção  efetiva  só é definida em tempo de execução. A aplicação cliente  não deve se preocupar  com criação  dos objetos.
 
 
 
 Applicabillity->  Quando  um sistema  deve ser  independente de como  seus  produtos são criados, composto e representados.Quando  um sistema deve ser configurado  com uma  entre  várias familias de produtos. Quando familia de produtos relacionados foi projetadas para uso conjunto e você deve implementar  está restrição. Quando  voçê quer fornecer uma bliblioteca  de classes e quer revelar  sua interface e não  sua implementação.
 
 
 
 
 Participantes
  Client->  É quem tem dependencia  com IProduct
  
  
  Creator -> Define o Factory  Method para retormar  instancia do ConcreteProduct.
  
  
  IProduct->  Define a interface  de objetos que o Factory cria
  
  
  Product A, Product B-> Implementa a interface  do produto.
