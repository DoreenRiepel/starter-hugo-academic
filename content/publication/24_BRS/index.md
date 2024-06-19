---
title: "Algorithm Substitution Attacks on Public Functions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mihir Bellare
- Doreen Riepel
- Laura Shea

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-05-12T00:00:00Z"
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

abstract: We study the possibility of algorithm substitution attacks (ASAs) on functions with no secret-key material, such as hash functions, and verification algorithms of signature schemes and proof systems. We consider big-brother’s goal to be three-fold{:} It desires utility (it can break the scheme), exclusivity (nobody else can) and undetectability (outsiders can’t detect its presence). We start with a general setting in which big-brother is aiming to subvert an arbitrary public function. We give, in this setting, strong definitions for the three goals. We then present a general construction of an ASA, and prove that it meets these definitions. We use this to derive, as applications, ASAs on hash functions, signature schemes and proof systems. As a further application of the first two, we give an ASA on X.509 certificates. While ASAs were traditionally confined to exfiltrating secret keys, our work shows that they are possible and effective at subverting public functions where there are no keys to exfiltrate. Our constructions serve to help defenders and developers identify potential attacks by illustrating how they might be built.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2024/536.pdf'
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
