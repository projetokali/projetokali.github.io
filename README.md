# Projeto Kali

[![Build Status](https://travis-ci.org/projetokali/projetokali.github.io.svg?branch=master)](https://travis-ci.org/projetokali/projetokali.github.io)

Página desenvolvida com base no tema [Creative](http://startbootstrap.com/template-overviews/creative/) de [Start Bootstrap](http://startbootstrap.com).

## Dev

### Organização

Cada página do site é descrita pelos arquivos `.html` presentes na pasta principal do repositório: `index.html`, `participe.html`, `sobre.html` e `google101861cb5388fd7c.html`.

Essas são as páginas que serão disponibilizadas publicamente e podem ser acessadas no link `https://projetokali.github.io/`.

Cada uma dessas páginas é escrita seguindo o modelo de [layouts do Jekyll](https://jekyllrb.com/docs/step-by-step/04-layouts/).

Por sua vez, os arquivos de layout estão definidos na página [_layouts](_layouts).

Um arquivo de layout é como o esqueleto de uma página, nele podemos ver em mais detalhes como uma página é montada.

Finalmente, um arquivo de layout é composto por vários arquivos `html` da pasta [_includes](_includes).

Os arquivos da pasta `_includes` descrevem componentes básicas do site, como por exemplo o arquivo [_includes/contact.html](_includes/contact.html) descreve a seção de contatos:

![seção de contatos do site](img/contato.PNG "Contatos")

### Instalação

Instalar Ruby, Bundler, Jekyll e html-proofer.

No windows, você pode fazer isso instalando o [RubyInstaller](https://rubyinstaller.org/).
Após isso, rode:

```bash
gem install jekyll bundler html-proofer
```

### Desenvolvendo localmente

Para rodar localmente o site:

```bash
jekyll serve
```

### Manutenção do site

Informações básicas do projeto e links importantes do site estão definidos em [`_config.yml`](./_config.yml).

Para redefinir, por exemplo, o link do formulário de inscrição de novos voluntários, basta mudar o valor de `form_inscricao_voluntario`.

Neste mesmo arquivo se encontram também informações como o número de voluntáries, alunes e turmas.