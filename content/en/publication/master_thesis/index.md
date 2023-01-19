---
title: 'A Quantitative Information Flow Model for Attribute-Inference Attacks and Utility in Data Releases by Sampling'

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
publication: Federal University of Minas Gerais

abstract: |2-
  Statistical disclosure is a process that has been present in society for a long time, however the concern about privacy is relatively recent. The interest in protecting individual data increased considerably especially after the elaboration of regulations about data protection around the world, such as the General Data Protection Regulation (GDPR) in the European Union and the *Lei Geral de Proteção de Dados* (LGPD) in Brazil. 

  The effort in the scientific community to develop methods for the mitigation of privacy risks and to understand the trade-off between privacy and utility compose a large research area. However, mathematical models that explain formally this trade-off are, in some situations, misunderstood by data curators, i.e., entities that collect data from a population and adopt a certain policy to publish them can not understand what are the risks and benefits of that policy. In this sense, models and solutions that ensure that all parties involved are aware of the risks and benefits of each policy adopted are important for well informed decision-making.

  As a first contribution of this work we propose a model that captures the vulnerability of publishing a sample from a population, in particular, the vulnerability of an attribute inference attack. We also describe the utility of the sample for data analysts who aim to infer the distribution of the values of an attribute in a population.

  The model was developed using the framework of Quantitative Information Flow (QIF) that provides a mathematical apparatus to formally model systems as informational channels. We developed the model with the goal of being easily understandable by non experts and to be used by data curators when making decisions about how to publish their data. As a second contribution we provide closed formulas for prior and posterior vulnerabilities of attribute inference attack and for prior utility loss. The closed formulas are useful when quantifying vulnerabilities and utility losses in large datasets/samples.

# Summary. An optional shortened abstract.
# summary: ''

tags: ['Statistical disclosure', 'Sampling', 'Privacy', 'Quantitative Information Flow']

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
