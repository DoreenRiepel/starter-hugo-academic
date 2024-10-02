---
title: "ISABELLA: Improving Structures of Attribute-Based Encryption Leveraging Linear Algebra"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Doreen Riepel
- Marloes Venema
- Tanya Verma

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-08-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM CCS 2024
publication_short: []

abstract: Attribute-based encryption (ABE) is a powerful primitive that has found applications in important real-world settings requiring access control. Compared to traditional public-key encryption, ABE has established itself as a considerably more complex primitive that is additionally less efficient to implement. It is therefore paramount that the we can simplify the design of ABE schemes that are efficient, provide strong security guarantees, minimize the complexity in their descriptions and support all practical features that are desirable for common real-world settings. One of such practical features that is currently still difficult to achieve is multi-authority support. Motivated by NIST's ongoing standardization efforts around multi-authority schemes, we put a specific focus on simplifying the support of multiple authorities in the design of schemes. To this end, we present ISABELLA, a framework for constructing pairing-based ABE with advanced functionalities under strong security guarantees. At a high level, our approach builds on various works that systematically and generically construct ABE schemes by reducing the effort of proving security to a simpler yet powerful "core" called pair encodings. To support the amount of adaptivity required by multi-authority ABE, we devise a new approach to designing schemes from pair encodings, while still being able to benefit from the advantages that pair encodings provide. As a direct result of our framework, we obtain various improvements for existing (multi-authority) schemes as well as new schemes.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2024/1352.pdf'
url_code: 'https://github.com/lincolncryptools/ISABELLA'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# links:
# - name: Slides
#  url: 

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