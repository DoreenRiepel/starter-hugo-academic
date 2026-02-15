---
title: "The Algebraic Isogeny Model: A General Model with Applications to SQIsign and Key Exchanges"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Marius A. Aardal
- Andrea Basso
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2026-01-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: EUROCRYPT 2026
publication_short: []

abstract: We introduce the Algebraic Isogeny Model (AIM){:} an algebraic model, akin to the Algebraic Group Model in the group setting, for isogenies and supersingular elliptic curves. This model is significantly more general than previous ones, such as the Algebraic Group Action Model{:} the AIM works with arbitrary isogenies over Fp^2, rather than being limited to oriented ones, which gives considerably more power to the adversary. Within this model, we obtain three results. First, we show that any result in the AGAM can be lifted to the AIM, strengthening previous results against more powerful adversaries. Then, we prove that the SQIsign identification protocol is ID-sound{:} in turn, this implies that SQIsign is EUF-CMA secure in the Quantum Random Oracle Model, resolving (in the AIM) a long-standing open problem. Lastly, we establish the equivalence of the DLOG and CDH problems for all SIDH-derived key exchanges, such as M-SIDH, binSIDH, and terSIDH.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:

url_pdf: 'https://eprint.iacr.org/2026/032.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# links:
# - name: Slides
#   url: uploads/slides.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

