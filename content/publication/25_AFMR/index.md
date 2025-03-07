---
title: "Lattice-Based Updatable Public-Key Encryption for Group Messaging"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Joël Alwen
- Georg Fuchsbauer
- Marta Mularczyk
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-03-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Cryptology ePrint Archive
publication_short: []

abstract: Updatable Public-Key Encryption (UPKE) augments the security of PKE with Forward Secrecy properties. While requiring more coordination between parties, UPKE enables much more efficient constructions than full-fledged Forward-Secret PKE. Alwen, Fuchsbauer and Mularczyk (AFM, Eurocrypt’24) presented the strongest security notion to date. It is the first to meet the needs of UPKE’s most important applications{:} Secure Group Messaging and Continuous Group Key Agreement. The authors provide a very efficient construction meeting their notion with classic security based on the Computational Diffie-Hellman (CDH) assumption in the Random Oracle Model (ROM). In this work we present the first post-quantum secure UPKE construction meeting (a slight relaxation of) the AFM security notion. Based on the Module LWE assumption, our construction is practically efficient. Moreover, public key sizes are about 1/2 and ciphertext sizes around 2/3 of those of the state-of-the-art lattice-based UPKE scheme in the ROM by Abou Haidar, Passelègue and Stehlé – despite only being shown to satisfy a significantly weaker security notion. As the AFM proofs relies on random self-reducibility of CDH, which has no analogue for lattices, we develop a new proof technique for strong UPKE, identifying the core properties required from the underlying (lattice-based) encryption scheme.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2025/365.pdf'
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
# slides: slides
---