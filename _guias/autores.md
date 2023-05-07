---
title: "Autores"
layout: single
sidebar:
  nav: "seccoes"
---

Bem, este é relativamente simples, e é para quem opera o website.

**Um lembrete importante:** isto pressupõe que já sabem operar o site com Jekyll. Ainda farei o guia para isso, mas entretanto podem consultar os guias básicos de como utilizar Jekyll [aqui](https://jekyllrb.com).

Os autores encontram-se na pasta `_data` deste repositório, no ficheiro `authors.yml`. Como podem ver, dentro desse ficheiro os autores são apresentados da seguinte maneira:

```yml
# Identificador a usar no artigo:
# Fica em formato: "primeiro-ultimo" (nomes s/ acentos)
primeiro-ultimo:
  # Nome do autor (o que aparece)
  name      : "Primeiro Último"
  # Bio curta. Não deve ultrapassar 2 frases.
  bio       : "Descrição. Máximo 2 frases."
  # Fotografia. Deve ser quadrada, sem excessões.
  # Guardar em '/assets/images/autores/' em jpg com o nome
  # do autor.
  avatar    : /assets/images/autores/primeiro-ultimo.jpg
  # Esta secção é opcional, mas inclui as redes
  # sociais que o autor preferir
  links     :
      # Nome da rede social
    - label : "Rede Social"
      # Ícone (substituir "fa-rede" por
      # "fa-instagram" por exemplo)
      icon  : "fab fa-fw fa-rede"
      # URL do utilizador na rede.
      # Copiar por inteiro, não só o username.
      url   : "https://www.rede.com/username/"
      # Podem ter mais que uma rede.
      # Idealmente não exceder 4.
    - label : "Outra Rede"
      icon  : "fab fa-fw fa-rede2"
      url   : "https://www.rede2.com/username/"
```

**EXEMPLO PRÁTICO:**

(Lembrar de apagar todas as linhas que estavam com `#` anteriormente. Podem copiar e colar o exemplo abaixo como base.)

```yml
jon-snow:
  name      : "Jon Snow"
  bio       : "Filho bastardo. Perito em assuntos medievais."
  avatar    : /assets/images/autores/jon-snow.jpg
  links     :
    - label : "IMDB"
      icon  : "fab fa-fw fa-imdb"
      url   : "https://www.imdb.com/title/tt0944947/characters/nm3229685?ref_=tt_cl_c_3"
```