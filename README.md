# Port Scanner em Python

## 🚀 Recursos

- **Escaneamento de Portas:** Verifica a disponibilidade de portas TCP em um host.

## 🛠️ Como Funciona

Este script Python realiza uma varredura nas portas TCP de um endereço IP especificado para verificar se estão abertas ou fechadas. O processo envolve o envio de pacotes para as portas alvo e a interpretação das respostas recebidas.

### Exemplo de Funcionamento

![Exemplo de Port Scanner](https://raw.githubusercontent.com/di3g020/PortScanner/main/pic.png)

## 🔧 Requisitos

- Python 3.x
- Biblioteca `socket` (incluída na biblioteca padrão do Python)

## 📦 Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/di3g020/PortScanner.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd PortScanner
    ```

## 🖥️ Como Usar

1. Execute o script `scanner.py` com Python 3.x:

    ```bash
    python scanner.py <endereço_ip>
    ```

    - `<endereço_ip>`: O IP do host que você deseja escanear.

    **Exemplo:**

    ```bash
    python scanner.py 192.168.1.1
    ```

    Este comando escaneará as portas no IP `192.168.1.1`.

