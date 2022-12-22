---
title: 'Analyzing the Shuffle Model through the Lens of Quantitative Information Flow'
subtitle: '(Under review)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mireya Jurado
  - Mário Alvim
  - Ramon Gonze
  - Catuscia Palamidessi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2022-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['4']

# Publication name and optional abbreviated publication name.
publication: Technical report
publication_short: Technical report

abstract: |2-
  Local differential privacy (LDP) was developed to avoid the necessity of a trusted central curator, but many implementations do so at the cost of accuracy. In response, the shuffle model has emerged as a way to provide greater anonymity to users by randomly permuting the messages such that the connection between users and values is lost. By combining a LDP mechanism with a shuffler, privacy can be improved at no cost for accuracy, thereby improving the trade-off between privacy and utility. However, the privacy implications of the shuffle layer are not always immediate nor are the derivations of the privacy bounds easy to understand. 

  In this paper, we interpret the shuffle model in the framework of quantitative information flow (QIF), thus providing an alternative view of it. We believe that such interpretation will contribute to make the shuffle model more intuitive and lay the basis for exploring its properties and for proving them formally. 

  In QIF, the privacy loss is measured in terms of information leakage. We provide formulas that show how the shuffler improves the protection against leaks in the local model, and study how the leakage decreases in function of the number of participants in the protocol, for various values of the privacy parameter of the LDP mechanism.

# Summary. An optional shortened abstract.
# summary: ''

tags: []

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
