---
# DEFINIÇÕES DO ARTIGO
# Todas as linhas com '#' podem ser apagadas.

# Nome do ficheiro no seguinte formato:
# YYYY-MM-DD-titulo-separado-com-hifenes.md

# *  -> Obrigatórios
# ** -> Obrigatórios, mas com escolha

# Cabeça
# - * Título
title: "Exemplo"
# - * Autor
author: jon-snow
# - * Data (yyyy-mm-ddThh:mm:ss-00:00)
date: 2023-04-30T00:00:00-00:00
# - Excerto do texto para aparecer em partilha (aparece no cabeçalho com overlay). Opcional: se vazio, gera um automático.
excerpt: ""
# - Tagline (substitui o excerto quando existe e o post tem overlay). Opcional.
tagline:

# * Categorias
categories:
  - XXe          # * Edição (número + "e")
  - PT           # * Língua ("PT" ou "EN")
  - Cá dentro    # Secção (ver abaixo; a escolher pelos editores?)

# Secções (copiar):
# - Cá dentro
# - Lá fora
# - (Cria)tividade
# - Núcleo musical
# - (Há) conversa
# - Sugestões culturais
# - A meu ver

# * Assuntos (países, temas, etc...)
tags:
  - Exemplo
  - Markdown

# * Design
# - Tabela de conteúdos (opcional, recomendado APENAS para quem utiliza títulos de separação)
toc: true
header:
  # - ** Imagem (escolher entre imagem inteira ou overlay)
  image          : https://upload.wikimedia.org/wikipedia/commons/f/f7/24.04.2023_-_Sess%C3%A3o_de_Abertura_do_F%C3%B3rum_Empresarial_Brasil-Portugal_%2852850986846%29.jpg
  # - ** Imagem em overlay (quando querem o título em cima da imagem com excerto por baixo)
  overlay_image  :
  # - Filtro de overlay (quando a imagem é muito clara, escolher um valor entre 0 e 1 para o texto ser visível; recomendo 0.5)
  overlay_filter :
  # - * Créditos de imagem (MUITO IMPORTANTE, VER EXEMPLO ABAIXO)
  caption        : "Fotografia: [Palácio do Planalto, via Wikimedia Commons](https://commons.wikimedia.org/wiki/File:24.04.2023_-_Sess%C3%A3o_de_Abertura_do_F%C3%B3rum_Empresarial_Brasil-Portugal_(52850986846).jpg)"

# COMO CREDITAR UMA IMAGEM:
# Fotografia: [Autor, via Fonte](link)
# PREFERIR:
# - Unsplash
# - Wikimedia Commons (ou Wikipédia em geral)
# - Trabalho próprio
# - Qualquer trabalho com licença Creative Commons
# - Multimédia de instituições públicas ou internacionais
# - Domínio público
# EVITAR(!!!):
# - Agências de notícias
# - Fotos aleatórias encontradas no Google
---

**NOTA:** Nada disto impede que continuem com o vosso workflow e que enviem os ficheiros como os têm atualmente. Mas se escreverem no Word ou Docs e depois fizerem um documento como estes (ou copiarem do Word/Docs para um dos programas recomendados abaixo, costuma funcionar), poupam imenso trabalho. Usually, cada artigo individualmente requer ~30m a ~1h a editar e a colocar funcional. Se preencherem a parte de cima deste ficheiro já poupam ~metade deste trabalho, e se enviarem um ficheiro completo com o texto já formatado com bolds, itálicos, listas, e etc como aqui abaixo, então o processo de colocar os artigos online torna-se muito mais rápido, e o foco pode ser posto em de facto colocar o site a funcionar. Podem verificar o ["código" deste artigo aqui]() para saberem como as coisas funcionam "under the hood".

Este artigo foi escrito com **Markdown**. E já agora, este parágrafo é um "aviso". Lembrem-se, sejam originais a usar isto, mas o que vem abaixo é mais recomendações do que outra coisa.
{: .notice--warning}

Adiciono que recomendo usarem um dos seguintes editores para formatar o vosso texto (são extremamente úteis além da vossa escrita para o DDEP, eu uso para fazer ensaios, por exemplo, e faz-vos metade do trabalho de escrever com este "código"). Por favor, não se assustem com este "código": ele está todo feito, só precisam de preencer com o que querem que apareça.

- [Typora](https://typora.io) (pago, mas barato e muito bom para uma escrita suave, foi uma salvação na licenciatura)
- [Obsidian](https://obsidian.md) (muito bom para escrever e organizar trabalho e é gratuito, é uma salvação no mestrado)

Este parágrafo é normal. Não tem formatação nenhuma.

# Isto é um Título 1

E aqui temos o texto que cabe no tal título.

## Com dois '#' fazemos um Título 2

Que fica abaixo do título 1 em termos organizacionais. Podem usar estes "títulos" até ao número 6 (para quem faz artigos super longos). 

### Título 3

#### Título 4

##### Título 5

###### Título 6

Abaixo desta frase vou introduzir um "separador" (uma linha, vá).

---

Como fazer listas? Assim:

- Era
- Uma
- Vez
- Uma lista

Ou, se quiserem numerar a mesma:

1. Um
2. Dois
3. Três
4. Vou nascer outra vez

---

Para fazerem um link basta fazerem [assim](https://youtu.be/dQw4w9WgXcQ). Desculpem.

---

- Esta frase está formatada para ter **bold**, *itálico*, ser um ponto de uma lista, e ter um [link](https://youtu.be/dQw4w9WgXcQ).

---

Se querem fazer citações, podem preferir dar-lhes destaque assim:

> Never gonna give you up.[^ola]

E se quiserem apresentar uma fonte, devem fazê-lo assim como fiz antes.

[^ola]: Se estão a ver o código disto, notam que a citação pode ter o identificador que quiserem, mas vai estar sempre numerada automaticamente. Esta será o número 1. Podem também colocar esta "peça" onde quiserem no artigo (fim, início, o que quiserem, mas tem que ser uma linha própria dedicada só à citação).

---

# Imagens

Apesar de existir uma forma mais simples de inserir imagens a meio do artigo, o padrão a utilizar para poder referenciar devidamente as imagens é mais complexo.

{% include figure image_path="https://upload.wikimedia.org/wikipedia/commons/8/85/Ron_DeSantis_CFDD.jpg" caption="Ron DeSantis, governador da Flórida (Republicano). Fotografia: [Office of the Governor of Florida, Public domain, via Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Ron_DeSantis_CFDD.jpg)" %}

Lembrar sempre de referenciar devidamente as fotos, como aqui está demonstrado, para não infringir em copyright.