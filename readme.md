# QR Code Creator

Este projeto é um simples criador de QR codes usando a biblioteca `qrcode` do Python.

## Como usar

1. Certifique-se de ter a biblioteca `qrcode` instalada. Você pode instalá-la usando pip:
    ```sh
    pip install qrcode[pil]
    ```

2. Execute o script  para criar um QR code:
    ```sh
    python main.py
    ```

## Funções

### 

Cria uma imagem de QR code.

- : Os dados a serem codificados no QR code.
- : O nome do arquivo para salvar a imagem do QR code.
- : O tamanho de cada caixa no QR code.
- : O tamanho da borda ao redor do QR code.

## Exemplo de uso

O exemplo abaixo cria um QR code para o link "https://www.amazon.com" e salva a imagem como "amazon.png":

```python
create_qr_code("https://www.amazon.com", "amazon.png")#   Q R - c o d e 
 
 
