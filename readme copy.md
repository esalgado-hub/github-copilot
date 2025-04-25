# Identificador de Bandeira de Cartão

Este projeto é um identificador de bandeira de cartão de crédito, disponível em versões Python e JavaScript, que reconhece as principais bandeiras a partir do número informado.

## Funcionalidades
- Identificação automática das bandeiras:
  - MasterCard
  - Visa (16 Dígitos)
  - American Express
  - Diners Club
  - Discover
  - EnRoute
  - JCB
  - Voyager
  - Hipercard
  - Aura
- Interface interativa no terminal
- Aceita números de cartão com ou sem espaços
- Exibe o nome da bandeira colorido conforme as cores da marca (no terminal compatível)
- Opção de continuar ou sair após cada consulta
- Limpeza automática da tela a cada operação

## Como executar

### Python
1. Certifique-se de ter o Python 3 instalado.
2. (Opcional) Ative o ambiente virtual:
   ```sh
   .\\venv-dio\\Scripts\\activate
   ```
3. Execute o script:
   ```sh
   python src/index.py
   ```

### JavaScript (Node.js)
1. Certifique-se de ter o Node.js instalado.
2. Execute o script:
   ```sh
   node src/index.js
   ```

## Exemplo de uso
```
----------------------------------------
      Identificador de Bandeira de Cartão
----------------------------------------
Digite o número do cartão: 4111 1111 1111 1111

A bandeira do cartão é: Visa (em azul)

Deseja verificar outro cartão? [S/N]: n

----------------------------------------
      Encerrando o programa. Até logo!
----------------------------------------
```

## Estrutura do Projeto
- `src/index.py`: Script principal em Python
- `src/index.js`: Script principal em JavaScript
- `assets/`: Pasta para arquivos estáticos
- `venv-dio/`: Ambiente virtual Python

## Requisitos
- Python 3.x
- Node.js (para versão JS)
- Terminal que suporte cores ANSI para melhor visualização

## Licença
Este projeto é livre para uso educacional e pessoal.

## Contato
- [LinkedIn - Edson Oliveira Salgado](https://www.linkedin.com/in/edson-oliveira-salgado-6bb9b232)