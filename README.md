# Biblioteca AB1805 para HTNB32L

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Esta é uma biblioteca C de minha autoria, **Weslley Fábio**, desenvolvida especificamente para facilitar a comunicação e o uso do Real-Time Clock (RTC) **AB1805** com o microcontrolador **HTNB32L**.

O objetivo principal desta biblioteca é simplificar a integração do RTC em projetos embarcados baseados no HTNB32L, oferecendo uma interface robusta e fácil de usar para gerenciar as funcionalidades do AB1805.

---

## Funcionalidades Principais

* **Configuração e Leitura/Escrita de Registradores:** Acesso direto e abstrato aos registradores do AB1805.
* **Gestão de Data e Hora:** Funções para configurar, ler e formatar data e hora.
* **Configuração de Alarmes:** Suporte para múltiplos modos de alarme, permitindo eventos temporizados.
* **Controle de Interrupções:** Habilitação e desabilitação de interrupções para eventos específicos do RTC (alarme, timer, bateria baixa, etc.).
* **Gerenciamento de Energia:** Funções para controle de **Trickle Charge** (carga lenta da bateria de backup) e modos de **baixa energia/sleep**.
* **Watchdog e Countdown Timer:** Suporte para o timer de contagem regressiva e watchdog, aumentando a robustez da aplicação.
* **Utilitários:** Funções de conversão BCD para Decimal e vice-versa.

---

## Como Usar

Para usar esta biblioteca em seu projeto, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone [[https://github.com/SeuUsuario/AB1805-HTNB32L.git](https://github.com/SeuUsuario/AB1805-HTNB32L.git)](https://github.com/WeslleyFabio/AB1805.git)
    ```
    (Lembre-se de substituir `SeuUsuario` pelo seu nome de usuário do GitHub e `AB1805-HTNB32L` pelo nome real do seu repositório.)

2.  **Adicione os Arquivos ao seu Projeto:**
    Inclua os arquivos `AB1805.h` e `AB1805.c` (ou o nome do seu arquivo `.c` de implementação) na estrutura do seu projeto HTNB32L. Certifique-se de que seu compilador possa encontrá-los.

3.  **Inclua a Biblioteca:**
    No seu código-fonte, inclua o cabeçalho da biblioteca:
    ```c
    #include "AB1805.h"
    ```

4.  **Exemplos:**
    Consulte a pasta `examples/` (crie essa pasta no seu repositório e adicione exemplos simples lá!) para ver demonstrações de como inicializar o RTC, configurar a hora, ler a data e usar as funções de alarme.

---

## Compatibilidade

Esta biblioteca foi desenvolvida e testada com o microcontrolador **HTNB32L**. O hardware de comunicação é baseado em I2C.

---

## Contribuição

Contribuições são **muito bem-vindas**! Se você encontrar bugs, tiver sugestões para novas funcionalidades, melhorias no código ou na documentação, sinta-se à vontade para:

1.  Abrir uma **Issue** para relatar problemas ou sugerir ideias.
2.  Criar um **Pull Request** com suas implementações.

---

## Licença

Este projeto é distribuído sob a licença **Apache License 2.0**. Isso significa que você é livre para usar, modificar e distribuir este software, desde que respeite os termos da licença. Uma cópia completa da licença pode ser encontrada no arquivo [`LICENSE`](LICENSE) neste repositório.

**Copyright (c) 2025 Weslley Fábio**

---

## Contato

Para dúvidas, sugestões ou apenas para dizer um "oi", você pode entrar em contato através do meu perfil no GitHub ou pelo e-mail: [SeuEmail@exemplo.com]

---
