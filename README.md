# Controle de LED com Botão no Arduino (Tinkercad)

Este projeto consiste em um sistema de controle de iluminação simples utilizando a plataforma Arduino. O objetivo é acionar um LED por meio de um botão (push-button), aplicando conceitos fundamentais de eletrônica e programação em C++.

## 👥 Integrantes do Grupo
O projeto foi desenvolvido em trio por:
* **Caline Myrella**: [github.com/CalineMyrella](https://github.com/CalineMyrella)
* **Maria Eduarda**: [github.com/Mariabrito09](https://github.com/Mariabrito09)
* **Lorena Oliveira**: [github.com/LoreeOliveira](https://github.com/LoreeOliveira)

## 🛠️ Tecnologias e Ferramentas
* **Arduino Uno**: Microcontrolador utilizado.
* **Tinkercad**: Plataforma para simulação do circuito e código.
* **Linguagem C++**: Base para a lógica de programação da Arduino IDE.

## 📚 Pesquisa Técnica: Comandos e Constantes
Abaixo, apresentamos a finalidade dos principais comandos utilizados no código, com base na pesquisa técnica realizada pelo grupo:

| Comando / Constante | Descrição e Finalidade |
| :--- | :--- |
| **`pinMode()`** | Atribui uma funcionalidade ao pino (entrada `INPUT` ou saída `OUTPUT`). [cite_start]Deve ser definido no `setup()`[cite: 3, 4]. |
| **`digitalRead()`** | [cite_start]Lê o estado de um pino digital, informando se o valor é alto (`HIGH`) ou baixo (`LOW`)[cite: 7]. |
| **`digitalWrite()`** | [cite_start]Envia um sinal `HIGH` ou `LOW` para um pino configurado como saída[cite: 10, 11]. |
| **`if`** | [cite_start]Estrutura de decisão que executa instruções baseadas em condições específicas[cite: 14]. |
| **`delay()`** | [cite_start]Pausa a execução do programa por um tempo determinado em milissegundos[cite: 17]. |
| **`HIGH`** | [cite_start]Macro que define o estado lógico alto (ligado/presença de tensão)[cite: 21]. |
| **`LOW`** | [cite_start]Macro que define o estado lógico baixo (desligado/ausência de tensão)[cite: 24, 25]. |

## 📂 Estrutura do Repositório
* `/Estrutura do Projeto`: Arquivos de organização.
* `Explicação do funcionamento do sistema.pdf`: Documento detalhando a lógica do circuito.
* `Pesquisa Técnica.docx`: Documentação teórica completa.

## 🚀 Como visualizar
Você pode acessar o circuito simulado diretamente no Tinkercad através do link disponível nos arquivos do projeto ou conferindo o código na branch principal.
