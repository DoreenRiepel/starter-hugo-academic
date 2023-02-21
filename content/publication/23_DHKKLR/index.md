---
title: "Generic Models for Group Actions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Julien Duman
- Dominik Hartmann
- Eike Kiltz
- Sabrina Kunzweiler
- Jonas Lehmann
- Doreen Riepel

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-01-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: PKC 2023
publication_short: []

abstract: We define the Generic Group Action Model (GGAM), an adaptation of the Generic Group Model to the setting of group actions (such as CSIDH). Compared to a previously proposed definition by Montgomery and Zhandry (ASIACRYPT'22), our GGAM more accurately abstracts the security properties of group actions. We are able to prove information-theoretic lower bounds in the GGAM for the discrete logarithm assumption, as well as for non-standard assumptions recently introduced in the setting of threshold and identification schemes on group actions. Unfortunately, in a natural quantum version of the GGAM, the discrete logarithm assumption does not hold. To this end we also introduce the weaker Quantum Algebraic Group Action Model (QAGAM), where every set element (in superposition) output by an adversary is required to have an explicit representation relative to known elements. In contrast to the Quantum Generic Group Action Model, in the QAGAM we are able to analyze the hardness of group action assumptions{:} We prove (among other things) the equivalence between the discrete logarithm assumption and non-standard assumptions recently introduced in the setting of QROM security for Password-Authenticated Key Exchange, Non-Interactive Key Exchange, and Public-Key Encryption.


# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2023/186.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


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