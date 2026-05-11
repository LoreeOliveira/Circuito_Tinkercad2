# Controle de LED com Botão no Arduino (Tinkercad)

Este projeto consiste em um sistema de controle de iluminação simples utilizando a plataforma Arduino. O objetivo é acionar um LED por meio de um botão (push-button), aplicando conceitos fundamentais de eletrônica e programação em C++.

##  Integrantes do Grupo
O projeto foi desenvolvido em trio por:
* **Caline Myrella**: [github.com/CalineMyrella](https://github.com/CalineMyrella)
* **Maria Eduarda**: [github.com/Mariabrito09](https://github.com/Mariabrito09)
* **Lorena Oliveira**: [github.com/LoreeOliveira](https://github.com/LoreeOliveira)

## 🛠️ Tecnologias e Ferramentas
* **Arduino Uno**: Microcontrolador utilizado.
* **Tinkercad**: Plataforma para simulação do circuito e código.
* **Linguagem C++**: Base para a lógica de programação da Arduino IDE.

## 📚 Pesquisa Técnica: Comandos Utilizados
Para o funcionamento deste sistema, foram utilizados os seguintes comandos e constantes, conforme detalhado na pesquisa técnica:

* [cite_start]**`pinMode()`**: Responsável por atribuir uma funcionalidade ao pino do Arduino (definindo se será entrada `INPUT` ou saída `OUTPUT`), devendo ser declarado dentro da função `setup()`[cite: 29, 30].
* [cite_start]**`digitalRead()`**: Informa se o pino apresenta um valor baixo (`LOW`) ou um valor alto (`HIGH`)[cite: 32, 33].
* [cite_start]**`digitalWrite()`**: Aciona um valor `HIGH` ou `LOW` em um pino digital configurado como saída[cite: 35, 36, 37].
* [cite_start]**`if`**: Estrutura de decisão que examina condições e decide quais instruções serão executadas[cite: 39, 40].
* [cite_start]**`delay()`**: Pausa a execução do programa por um tempo específico em milissegundos, controlando o tempo de loops ou intervalos entre comandos[cite: 42, 43, 44].
* [cite_start]**`HIGH`**: Macro que define um estado lógico alto (ligado) em um pino digital[cite: 46, 47].
* [cite_start]**`LOW`**: Constante pré-definida que representa um estado lógico baixo; em casos de LED, configura-o como desligado[cite: 49, 50, 51].

## 📂 Estrutura do Repositório
* `/Estrutura do Projeto`: Arquivos de organização.
* `Explicação do funcionamento do sistema.pdf`: Documento detalhando a lógica do circuito.
* `Pesquisa Técnica.docx`: Documentação teórica sobre os comandos utilizados.

## 🚀 Como visualizar
Você pode acessar o circuito simulado diretamente no Tinkercad através do link disponível nos arquivos do projeto.
