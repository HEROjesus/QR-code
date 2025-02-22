# QR Code Creator

Este projeto é um simples criador de QR codes utilizando a biblioteca `qrcode` do Python.

---

## Como usar

1. Certifique-se de ter a biblioteca `qrcode` instalada. Você pode instalá-la com o seguinte comando:
    ```sh
    pip install qrcode[pil]
    ```

2. Execute o script para criar um QR code:
    ```sh
    python main.py
    ```

---

## Funções

### `create_qr_code`

Cria uma imagem de QR code.

**Parâmetros:**
- **data**: Os dados a serem codificados no QR code (por exemplo, um link ou texto).
- **file_name**: O nome do arquivo para salvar a imagem do QR code (ex.: "output.png").
- **box_size**: O tamanho de cada caixa no QR code (valor padrão sugerido: 10).
- **border**: O tamanho da borda ao redor do QR code (valor padrão sugerido: 4).

---

## Exemplo de uso

O exemplo abaixo cria um QR code para o link "https://www.amazon.com" e salva a imagem como "amazon.png":

```python
from main import create_qr_code

create_qr_code("https://www.amazon.com", "amazon.png", box_size=10, border=4)
