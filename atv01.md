# Titulo

### 1. Descreva a arquitetura do sistema operacional Android<br><br>
-  a arquitetura do sistema android é formada por cinco módulos: kernel Linux, Biblioteca, Runtime(onde é realizada as execuções), framework de aplicações e aplicações <br>

- a arquitetura da plataforma é baseada no kernel do Linux, ele funciona como uma camada de abstração entre o hardware e o restante dos softwares da plataforma. com isso, ele tem várias formas de execução das aplicações. <br>

- acima do kernel linux, temos a Biblioteca, que são escritas em C/C++, compostas por uma série de bibliotecas utilizadas pelo android. <br>

- temos o Runtime, que é o ambiente de execução. ele é composto pela máquina virtual Dalvik, que foi desenvolvida para que os dispositivos possam suportar múltiplas máquinas virtuais de forma adequada. <br>

- o framework de aplicações consiste em componentes que permitirão que as novas estruturas sejam usadas para futuras aplicações, aproveitando o reuso desses componentes, sempre sujeito a restrições de segurança. <br>

- no topo da plataforma, temos as aplicações, onde está localizada uma lista de aplicações padrão que inclui um cliente de e-mail, calendário, navegador, contatos, mapas, programas, entre outros. <br><br>


### 2. Descreva como desenvolvemos interfaces em aplicações Android nativas em Kotlin <br><br>

- no kotlin o desenvolvimento é feito em orientação de objetos e um arquivo .xml que usado para criar a interface do app<br><br>

### 3. Defina o que é uma View <br><br>

- uma view é uma maneira alternativa de observação de dados de uma ou mais entidades, que compõem uma base de dados. pode ser considerada como uma tabela virtual ou uma consulta armazenada. <br><br>

### 4. Defina o que é um Event Listener <br><br>

- O método addEventListener() permite configurar funções a serem chamadas quando um evento especificado acontece, como quando um usuário clica em um botão. <br><br>

### 5. Defina o que é o Graddle <br><br>

- o gradle é um sistema de automação de build (compilação) open source que usa uma linguagem específica de domínio (DSL) em groovy e kotlin para definir tarefas. o gradle foi projetado para automatizar o build de vários projetos. <br><br>

### 6. Escreva o que é o SDK android <br><br>

- O Kit de Desenvolvimento de Software (Software Development Kit ou SDK) do Android é um conjunto de ferramentas que os desenvolvedores e programadores usam para criar aplicativos para smartphones e tablets com o sistema operacional da Google. <br><br>

### 7. Escreva o que sãos API level, e dentro das configs de build o que é Target API e minimal API level <br><br>

- API level é um identificador numérico composto de um único digito decimal. <br>

- Target API é uma API que possibilita que dois programas diferentes compartilhem informações entre si. <br>

- minimal API level é o requisito de quando você faz upload de um APK, ele precisa atender aos requisitos de nível de API de destino do Google Play. Novos aplicativos e atualizações de aplicativos devem ser direcionados à ultima versão do android. <br><br>

### 8. O que é o processo de Build <br><br>

- o processo de build de um software é responsável por verificar se todos os componentes do nosso código fonte estão sendo integrados de maneira correta.<br><br>

### 9.  Descreva como podemos testar aplicações android em nossos próprios celulares. <br><br>

- primeiramente temos que desbloquear as opções de desenvolvedor em nosso celular, ativando a depuração usb. conectamos o celular no computador(com o android studio ja aberto) e executamos o programa no celular. <br><br>





 





 








