---
title: 'Um modelo de Fluxo de Informação Quantitativo para Ataques de Inferência de Atributo e Utilidade em Divulgação de Dados por Amostragem'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ramon Gonçalves Gonze

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2023-01-11'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2022-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
publication: Universidade Federal de Minas Gerais

abstract: |2-
  Divulgação de dados estatísticos é um processo presente na sociedade há bastante tempo, entretanto, a preocupação com privacidade é relativamente recente. O interesse em proteger dados individuais aumentou consideravelmente depois da elaboração de regulações sobre proteção de dados ao redor do mundo, como a *General Data Protection Regulation* (GDPR) na União Européia e a Lei Geral de Proteção de Dados (LGPD) no Brasil.

  O esforço na comunidade científica para criar métodos de mitigação de risco à privacidade e para entender o compromisso entre privacidade e utilidade compõe uma grande área de pesquisa. Contudo, modelos matemáticos que buscam explicar formalmente este compromisso são, em alguma situações, incompreendidos pelos curadores de dados, i.e., entidades que coletam dados de uma população e adotam uma certa política para publicá-los podem não compreender quais os riscos e benefícios de tal política. Neste sentido, modelos e soluções que garantem que todas as partes envolvidas tenham ciência dos riscos e benefícios de cada política adotada se mostram importantes para que tomadas de decisões sejam realizadas de modo bem informado.

  Como primeira contribuição deste trabalho, nós propomos um modelo que captura a vulnerabilidade de publicar-se uma amostra de uma população, em particular, a vulnerabilidade sob um ataque de inferência de atributo. Além disso descrevemos a utilidade de se publicar uma amostra para analistas de dados que têm como objetivo inferir a distribuição dos valores de um atributo em uma população.

  O modelo foi desenvolvido utilizando o arcabouço *Quantitative Information Flow* (QIF) que fornece um aparato matemático para modelar formalmente sistemas como canais de informação. Nós desenvolvemos o modelo com o objetivo de ser facilmente explicável para não especialistas e para ser utilizado por curadores de dados quando estiverem tomando decisões sobre como publicar os seus dados. Como segunda contribuição, nós provemos fórmulas fechadas para vulnerabilidades à priori e à posteriori para ataques de inferência de atributo e para perda de utilidade à priori. As fórmulas fechadas são úteis para quantificar vulnerabilidades e perdas de utilidade em grandes amostras e populações.


# Summary. An optional shortened abstract.
# summary: ''

tags: ['Divulgação estatística', 'Amostragem', 'Privacidade', 'Fluxo de Informação Quantitativo']

# Display this page in the Featured widget?
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
