Consiste em um padrão de Jogos em que os objetos do jogo se comunicam através de observações e mensagens, tornando o código bem mais encapsulado.

Basicamente, pegando o exemplo da Godot que eu fiz, um objeto Key listener tem a responsabilidade de observar se alguma tecla foi acionada e emitir um sinal avisando outros objetos.
![[ObjetoKey Lsitener.png]]

Esse exemplo pode também se conectar com o padrão da Godot de [[Definir atributos de um objeto como nodes filhos]], já que instancias do Key Listener podem ser usadas como nós filhos de outros objetos, criando uma boa encapsulação do código.
Nesse código, o nó só verifica duas teclas, mas em situações diferentes, poderia observar se uma tecla foi acionada e retornar qual tecla foi acionada.