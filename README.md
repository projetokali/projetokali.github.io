# Projeto Kali

[![Build Status](https://travis-ci.org/github/projetokali/blog.png)](https://travis-ci.org/github/projetokali/blog)

Página desenvolvida com base no tema [Creative](http://startbootstrap.com/template-overviews/creative/) de [Start Bootstrap](http://startbootstrap.com).

## Dev

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