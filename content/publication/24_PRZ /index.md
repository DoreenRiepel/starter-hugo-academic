---
title: "Key Exchange with Tight (Full) Forward Secrecy via Key Confirmation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiaxin Pan
- admin
- Runzhi Zeng

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: EUROCRYPT 2024
publication_short: []

abstract: Weak forward secrecy (wFS) of authenticated key exchange (AKE) protocols is a pas- sive variant of (full) forward secrecy (FS). A natural mechanism to upgrade from wFS to FS is the use of key confirmation messages which compute a message authentication code (MAC) over the transcript. Unfortunately, Gellert, Gjøsteen, Jacobson and Jager (GGJJ, CRYPTO 2023) show that this mechanism inherently incurs a loss proportional to the number of users, leading to an overall non-tight reduction, even if wFS was established using a tight reduction. Inspired by GGJJ, we propose a new notion, called one-way verifiable weak forward secrecy (OW-VwFS), and prove that OW-VwFS can be transformed tightly to FS using key confirmation in the random oracle model (ROM). To implement our generic transformation, we show that several tightly wFS AKE protocols additionally satisfy our OW-VwFS notion tightly. We highlight that using the recent lattice-based protocol from Pan, Wagner, and Zeng (CRYPTO 2023) can give us the first lattice-based tightly FS AKE via key confirmation in the classical random oracle model. Besides this, we also obtain a Decisional-Diffie-Hellman-based protocol that is considerably more efficient than the previous ones. Finally, we lift our study on FS via key confirmation to the quantum random oracle model (QROM). While our security reduction is overall non-tight, it matches the best existing bound for wFS in the QROM (Pan, Wagner, and Zeng, ASIACRYPT 2023), namely, it is square-root- and session-tight. Our analysis is in the multi-challenge setting, and it is more realistic than the single-challenge setting as in Pan et al..

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2024/361.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# links:
# - name: Slides
#   url: uploads/slides_HJKLPRS21.pdf


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
# slides: slides
---
