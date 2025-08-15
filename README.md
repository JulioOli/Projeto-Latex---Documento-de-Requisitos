# Template LaTeX para Documento de Requisitos

Este projeto fornece um template completo para documentos de requisitos acadêmicos ou profissionais, seguindo estrutura ABNT e boas práticas de organização.

## Como usar

1. Clone ou baixe este repositório.
2. Edite os arquivos das seções em `sections-new/` conforme seu projeto.
3. Altere os comandos de nomes e dados em `config.sty` para os autores do novo documento.
4. Compile o arquivo principal `main.tex` usando o comando:
   ```sh
   latexmk -pdf main.tex
   ```
5. O PDF gerado estará disponível como `main.pdf`.

## Estrutura
- `main.tex`: Arquivo principal do documento.
- `config.sty`: Configurações gerais e comandos personalizados.
- `commands.sty`: Comandos auxiliares.
- `sections-new/`: Diretório com todas as seções do documento.
- `images/`: Imagens utilizadas (exemplo: logo da instituição).
- `referencias.bib`: Arquivo de referências bibliográficas (exemplo mínimo).
- `abnt/`: Arquivos de estilo ABNT para citações e referências.

## Personalização
- Substitua os comandos de nomes (`\julio`, `\otavio`, etc.) por nomes dos autores do novo documento.
- Preencha cada seção com o conteúdo do seu projeto.
- Use exemplos mínimos e referências como base para novos documentos.

## Requisitos
- Distribuição LaTeX completa (ex: TeX Live)
- Pacote latexmk para compilação automática

## Licença
Este template é livre para uso acadêmico e profissional.
