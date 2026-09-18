# Modelo Simplificado INPE para Iniciação Científica

Este repositório oferece um modelo LaTeX simplificado para relatórios de iniciação científica.

O material foi adaptado do [ModeloINPE_2022](https://www.overleaf.com/latex/templates/modeloinpe-2022/bytpkdzvmyqk), criado pelo Instituto Nacional de Pesquisas Espaciais (INPE) e disponibilizado sob a licença [Creative Commons Attribution 4.0 International — CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

O modelo original foi criado para teses e dissertações. Esta versão foi simplificada e adaptada, em 2025, para apoiar a elaboração de relatórios de iniciação científica. Trata-se de uma adaptação independente, sem endosso institucional do INPE.

## Como usar

### 1. Obtenha os arquivos

Baixe o repositório em **Code > Download ZIP** ou clone:

```bash
git clone https://github.com/felipeeliascs/INPE-IC-ICJr-LaTeX-Relatorio-Final.git
```

Para editar on-line, compacte os arquivos em formato ZIP e importe-os no [Overleaf](https://www.overleaf.com/) em **New Project > Upload Project**.

### 2. Conheça os arquivos principais

- `configuracao.tex` — título, autores, ano e demais informações iniciais
- `publicacao.tex` — arquivo principal usado para compilar o documento
- `docs/08_01_capitulo1.tex`, `docs/08_02_capitulo2.tex` e `docs/08_03_capitulo3.tex` — corpo do texto dividido por capítulos
- `docs/figuras/` — local recomendado para as imagens do relatório
- `bib/referencia.bib` — referências bibliográficas

### 3. Compile

No Overleaf, defina `publicacao.tex` como documento principal e use **Recompile**. Para trabalhar localmente, utilize uma distribuição LaTeX compatível com os pacotes empregados pelo modelo.

## Passo a passo rápido

1. Edite título, autor, orientador e demais informações iniciais em `configuracao.tex`.
2. Use `publicacao.tex` como arquivo principal para compilar o documento.
3. Escreva os capítulos nos arquivos da pasta `docs/`.
4. Inclua imagens em `docs/figuras/` e cite-as com o ambiente `figure`.
5. Adicione referências em `bib/referencia.bib` e cite-as com `\cite{chave}`.
6. Compile e revise o documento periodicamente.
7. Solicite a revisão do orientador antes da versão final.

## Recomendações

- Preserve os comandos e a estrutura de formatação do modelo.
- Leia os comentários presentes nos arquivos antes de alterá-los.
- Mantenha cópias de segurança e revise o PDF gerado.
- Use a aba **Issues** para relatar problemas ou sugerir melhorias.

## Licença, créditos e alterações

Este projeto é uma adaptação do [ModeloINPE_2022](https://www.overleaf.com/latex/templates/modeloinpe-2022/bytpkdzvmyqk), criado pelo Instituto Nacional de Pesquisas Espaciais (INPE) e disponibilizado sob a licença [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

- Adaptação: Prof. Felipe Elias (`@proffelipeelias`)
- Ano da adaptação: 2025
- Alterações: simplificação da estrutura e adaptação para relatórios de iniciação científica

Os materiais sujeitos a direitos autorais são distribuídos sob a licença CC BY 4.0. Consulte [LICENSE](LICENSE) para os termos e [NOTICE.md](NOTICE.md) para a atribuição detalhada. A licença não concede direitos sobre marcas ou logotipos.
