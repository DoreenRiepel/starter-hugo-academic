---
title: "Multi-User CDH Problems and the Concrete Security of NAXOS and HMQV"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Eike Kiltz
- Jiaxin Pan
- Doreen Riepel
- Magnus Ringerud

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-01-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: CT-RSA 2023
publication_short: []

abstract: We introduce CorrGapCDH, the Gap Computational Diffie-Hellman problem in the multi-user setting with Corruptions. In the random oracle model, our assumption tightly implies the security of the authenticated key exchange protocols NAXOS in the eCK model and (a simplified version of) X3DH without ephemeral key reveal. We prove hardness of CorrGapCDH in the generic group model, with optimal bounds matching the one of the discrete logarithm problem. We also introduce CorrCRGapCDH, a stronger Challenge-Response variant of our assumption. Unlike standard GapCDH, CorrCRGapCDH implies the security of the popular AKE protocol HMQV in the eCK model, tightly and without rewinding. Again, we prove hardness of CorrCRGapCDH in the generic group model, with (almost) optimal bounds. Our new results allow implementations of NAXOS, X3DH, and HMQV without having to adapt the group sizes to account for the tightness loss of previous reductions. As a side result of independent interest, we also obtain modular and simple security proofs from standard GapCDH with tightness loss, improving previously known bounds.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2023/115.pdf'
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