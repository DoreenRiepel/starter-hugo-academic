---
title: "Highly-Effective Backdoors for Hash Functions and Beyond"

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

date: "2024-04-12T00:00:00Z"
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

abstract: We study the possibility of schemes whose public parameters have been generated along with a backdoor. We consider the goal of the big-brother adversary to be two-fold{:} It desires utility (it can break the scheme) but also exclusivity (nobody else can). Starting with hash functions, we give new, strong definitions for these two goals, calling the combination high effectiveness. We then present a construction of a backdoored hash function that is highly effective, meaning provably meets our new definition. As an application, we investigate forgery of X.509 certificates that use this hash function. We then consider signatures, again giving a definition of high effectiveness, and showing that it can be achieved. But we also give some positive results, namely that for the Okamoto and Katz-Wang signature schemes, certain natural backdoor strategies are provably futile. Our backdoored constructions serve to warn that backdoors can be more powerful and damaging than previously conceived, and to help defenders and developers identify potential backdoors by illustrating how they might be built. Our positive results illustrate that some schemes do offer more backdoor resistance than others, which may make them preferable.

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
