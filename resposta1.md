### 1. Descreva a arquitetura do sistema operacional Android<br><br>
-  a arquitetura do sistema android é formada por cinco módulos: kernel Linux, Biblioteca, Runtime(onde é realizada as execuções), framework de aplicações e aplicações <br>

- a arquitetura da plataforma é baseada no kernel do Linux, ele funciona como uma camada de abstração entre o hardware e o restante dos softwares da plataforma. com isso, ele tem várias formas de execução das aplicações. <br>

- acima do kernel linux, temos a Biblioteca, que são escritas em C/C++, compostas por uma série de bibliotecas utilizadas pelo android. <br>

- temos o Runtime, que é o ambiente de execução. ele é composto pela máquina virtual Dalvik, que foi desenvolvida para que os dispositivos possam suportar múltiplas máquinas virtuais de forma adequada. <br>

- o framework de aplicações consiste em componentes que permitirão que as novas estruturas sejam usadas para futuras aplicações, aproveitando o reuso desses componentes, sempre sujeito a restrições de segurança. <br>

- no topo da plataforma, temos as aplicações, onde está localizada uma lista de aplicações padrão que inclui um cliente de e-mail, calendário, navegador, contatos, mapas, programas, entre outros. <br><br>