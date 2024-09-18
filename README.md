# Atividade 1 - Computação em Nuvem

## Objetivo
Desenvolver e contêinerizar uma aplicação web simples usando Flask (ou outra tecnologia) e Docker. O processo inclui a criação de um Dockerfile, execução da aplicação em um contêiner e exposição do serviço em uma porta mapeada.

## Dockerfile

- Utiliza a imagem base `python:3.9-slim`.
- Define o diretório de trabalho e copia os arquivos do projeto.
- Instala Flask e expõe a porta 8080.
- Configura o ambiente e executa o arquivo `script.py`.

## Passos para rodar

1. Clone o repositório e entre no diretório do projeto.
   
   ```bash
   git clone
   cd atividade-1-computacao-em-nuvem

2. Construa a imagem Docker com o comando:

    ```bash
    docker build -t atividade-1-computacao-em-nuvem

3. Execute o container:

    ```bash
    docker run -p 8080:8080 atividade-1-computacao-em-nuvem

