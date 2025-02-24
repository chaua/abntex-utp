# :pencil: Projeto LaTeX - Trabalho Acadêmico UTP

Bem-vindo ao repositório do **Trabalho Acadêmico UTP**! :mortar_board:

Este projeto foi desenvolvido em LaTeX, seguindo as normas da **Universidade Tuiuti do Paraná (UTP)** e utilizando o
estilo **ABNT** com base no pacote **ABNTex**. Ele está pronto para ser usado como um template para os seus trabalhos
acadêmicos, como monografias, TCCs e dissertações.

## :file_folder: Estrutura do Projeto

Aqui está uma visão geral dos arquivos e diretórios presentes no projeto:

```
.
├── Makefile               # Script para compilar o projeto facilmente
├── referencias.bib        # Arquivo de referências bibliográficas no formato BibTeX
├── trabalho.pdf           # Arquivo PDF gerado (resultado final do trabalho)
├── trabalho.tex           # Arquivo principal em LaTeX
├── img/                   # Diretório com imagens usadas no trabalho
│   ├── fig1.png
│   ├── fig2.png
│   └── ...
└── packages/              # Diretório com pacotes customizados
    └── abnt-UTP.sty       # Estilo ABNT customizado para a UTP
```

### :open_file_folder: Diretório `img/`

Contém todas as imagens inseridas no documento, como figuras, gráficos e fontes visuais do projeto. Exemplos:

- `fig1.png`, `fig2.png`: Gráficos e figuras ilustrativas.
- `fonte.png`: Imagens de fontes utilizadas no trabalho.

### :open_file_folder: Diretório `packages/`

Aqui está o arquivo de estilo `abnt-UTP.sty`, que adapta as normas da ABNT para os documentos da UTP, facilitando a
formatação correta do seu trabalho.

## :wrench: Como Usar

### Pré-requisitos

Para compilar este projeto, você precisará de um ambiente LaTeX. Algumas opções recomendadas:

- [Overleaf](https://www.overleaf.com) (recomendado para uso online).
- Instalação local do LaTeX, utilizando o `Makefile` para compilar.

### Compilação Local

Para compilar o projeto no seu computador, certifique-se de ter o LaTeX instalado. Depois, basta rodar:

```bash
make
```

Isso irá gerar o arquivo PDF `trabalho.pdf`.

## :books: Recursos Úteis

Aqui estão alguns links que podem ajudar no desenvolvimento do seu trabalho:

- :open_book: [Normas UTP - Manual de Trabalhos Acadêmicos (2024)](https://tuiuti.edu.br/wp-content/uploads/2024/09/e-book_NT_UTP_2024-1.pdf)

- :blue_book: [ABNTex](https://www.abntex.net.br/) - Pacote LaTeX para formatação de trabalhos segundo as normas ABNT.

- :green_book: [Uma não tão pequena introdução ao LATEX 2ε](https://linorg.usp.br/CTAN/info/lshort/portuguese/pt-lshort.pdf) -
  O clássico livro sobre LaTeX.

- :globe_with_meridians: [Overleaf](https://www.overleaf.com) - Editor LaTeX online colaborativo.

## :hammer_and_wrench: Contribuindo

Sinta-se à vontade para sugerir melhorias ou abrir _issues_ para discutir problemas. Este projeto segue a
licença [MIT](LICENSE).
