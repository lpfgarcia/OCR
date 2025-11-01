# OCR dos adesivos com DeepSeek-OCR

Este é o repositório para **Reconhecimento Óptico de Caracteres (OCR)** utilizando o modelo **DeepSeek-OCR**. O objetivo é realizar a leitura, extração e validação automática de texto dos adesivos.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```bash
    ├── ocr.ipynb # Notebook principal para execução e testes
    ├── requirements.txt # Dependências do projeto
    ├── results.txt # Resultados gerados pelos experimentos
    ├── .gitignore # Arquivos e pastas ignorados pelo Git
    └── README.md # Este arquivo
```

## Como Utilizar

Para utilizar este projeto, siga os passos abaixo:

1. Clone este repositório para o seu ambiente local:

```bash
    git clone https://github.com/lpfgarcia/OCR.git
    cd OCR
```
2. Crie e ative o ambiente Conda com Python 3.12.9:

```bash
    conda create -n ocr python=3.12.9 -y
    conda activate ocr
```

3. Instale as dependências necessárias:

```bash
    pip install -r requirements.txt
```

4. Execute o notebook principal:

```bash
    jupyter notebook ocr.ipynb
```
