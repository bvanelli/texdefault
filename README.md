# Texdefault

Esse é um documento LaTeX básico em Português-Brasil já configurado e que já possui os principais pacotes utilizados e alguns exemplos de codificação.

## Instalação do LaTeX

Para utilizar LaTeX são necessários um compilador TeX/LaTeX e opcionalmente um editor de texto que facilitará na digitação.

Compilador: [Mixtex](http://miktex.org/download)

Editor (opcional, mas recomendado): [TexMaker](http://www.xm1math.net/texmaker/download.html)

## Configuração do TexMaker

Para facilitar a visualização dos arquivos, vá até Comandos marque a opção "Use a "build" subdirectory for output files" e substitua o texto no campo Bib(La)Tex por:

> bibtex build/%.aux

Na área Compilar escolha compilação rápida como sendo:
 
> PdfLaTeX + Bib(La)Tex + PdfLaTeX (x2) + View Pdf

Copie o dicionário incluso na pasta TexMaker para 

> C:/Program Files (x86)/Texmaker/

e selecione como dicionário na parte Editor.
 