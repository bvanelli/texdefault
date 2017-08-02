# Texdefault

Esse é um documento LaTeX básico em Português-Brasil já configurado e que já possui os principais pacotes utilizados e alguns exemplos de codificação.

## Instalação do LaTeX

### Windows
Para utilizar LaTeX são necessários um compilador TeX/LaTeX e opcionalmente um editor de texto que facilitará na digitação.

- [MixTex](http://miktex.org/download) - Compilador padrão para Windows.

- [TexMaker](http://www.xm1math.net/texmaker/download.html) - Editor opcional, mas recomendado, que adiciona *autocompletion* facilita a visualização do *project tree*.

### Ubuntu

Para instalar o compilador sem toda a documentação do `texlive` utilize o comando:

```
sudo apt-get --no-install-recommends install texlive-{base,bibtex-extra,extra-utils,generic-recommended,fonts-recommended,font-utils,latex-base,latex-recommended,latex-extra,math-extra,pictures,pstricks,science,lang-portuguese} perl-tk purifyeps chktex latexmk dvipng xindy dvidvi fragmaster lacheck latexdiff libfile-which-perl dot2tex tipa latex-xcolor latex-beamer prosper pgf lmodern
```

Caso contrário, basta instalar o pacote `texlive-full`.

## Configuração do TexMaker

### Compilar bibliografia automaticamente

Para facilitar a visualização dos arquivos, vá até Comandos marque a opção **"Use a "build" subdirectory for output files"** e substitua o texto no campo Bib(La)Tex por:

> `bibtex build/%.aux`

Na área Compilar escolha compilação rápida como sendo:
 
> PdfLaTeX + Bib(La)Tex + PdfLaTeX (x2) + View Pdf

### Dicionário para checar ortografia

Copie o dicionário (arquivos `pt_BR.aff` e `pt_BR.dic`) incluso na pasta `texmaker` deste repositório ([ou baixe a versão do Libreoffice](https://pt-br.libreoffice.org/assets/Uploads/PT-BR-Documents/VERO/ptBR-2013-10-30AOC-2.zip))  para:

> `C:/Program Files (x86)/Texmaker/`

e selecione como dicionário na parte Editor.

## Licença

Esse documento pode ser copiado livremente sobre a licença GNU GENERAL PUBLIC LICENSE. Contribuições ao trabalho atual são bem vindas.
 
