# Projeto Kali

[![Build Status](https://travis-ci.org/projetokali/projetokali.github.io.svg?branch=master)](https://travis-ci.org/projetokali/projetokali.github.io)

Página desenvolvida com base no tema [Creative](http://startbootstrap.com/template-overviews/creative/) de [Start Bootstrap](http://startbootstrap.com).

## Dev

### Organização de código

Cada página do site é descrita pelos arquivos `.html` presentes na pasta principal do repositório: `index.html`, `participe.html`, `sobre.html` e `google101861cb5388fd7c.html`.

Essas são as páginas que serão disponibilizadas publicamente e podem ser acessadas no link `https://projetokali.github.io/`.

Cada uma dessas páginas é escrita seguindo o modelo de [layouts do Jekyll](https://jekyllrb.com/docs/step-by-step/04-layouts/).

Por sua vez, os arquivos de layout estão definidos na página [`_layouts`](_layouts).

Um arquivo de layout é como o esqueleto de uma página, nele podemos ver em mais detalhes como uma página é montada.

Finalmente, um arquivo de layout é composto por vários arquivos `html` da pasta [`_includes`](_includes).

Os arquivos da pasta `_includes` descrevem componentes básicas do site, como por exemplo o arquivo [`_includes/contact.html`](_includes/contact.html) descreve a seção de contatos que pode ser vista em todas páginas do site:

![seção de contatos do site](img/contato.PNG "Contatos")

### Organização de dados

As imagens utilizadas no site estão todas organizadas sob a pasta [`img`](img), enquanto que as fontes (como a "DJB Chalk It Up") estão na pasta [`fonts`](fonts).

Informações básicas do projeto e links importantes estão definidos em [`_config.yml`](./_config.yml).

Para redefinir, por exemplo, o link do formulário de inscrição de novos voluntários, basta mudar o valor de `form_inscricao_voluntario` mostrado a seguir:

```yaml
[...]
facebook_url: "https://www.facebook.com/projetokali"

form_inscricao_voluntarios: "https://docs.google.com/forms/d/1ynp4C2z2nJff9wr5wSMIICFE4u2E2ehYPRh6jJpRAJs/viewform?edit_requested=true"
form_inscricao_alunos: "https://docs.google.com/forms/d/e/1FAIpQLSf2lxWhkuF1ROEvdannhD7AZ0HXx8jg7_J9SPjPc41yyNns9A/viewform"

n_voluntaries: "40"
[...]
```

Neste mesmo arquivo se encontram também informações como o número de voluntáries, alunes e turmas do projeto.

### Instalação

Instalar Ruby, Bundler, Jekyll e html-proofer.

No windows, você pode fazer isso instalando o [RubyInstaller](https://rubyinstaller.org/).
Após isso, rode no terminal:

```bash
gem install jekyll bundler html-proofer
```

Para testar se a instalação do jekyll aconteceu com sucesso, rode no terminal:

```bash
jekyll --version
```

Se instalado corretamente deve-se receber em resposta a versão do programa instalado, do seguinte modo:

```bash
jekyll 4.1.0
```

### Desenvolvendo localmente

Para rodar localmente o site:

```bash
jekyll serve
```

Se tudo rodou corretamente uma mensagem lhe indicará que o site pode ser acessado no endereço [http://127.0.0.1:4000/](http://127.0.0.1:4000/).
