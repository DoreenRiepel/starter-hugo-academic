---
title: "Tightly-Secure Group Key Exchange with Perfect Forward Secrecy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Emanuele Di Giandomenico
- admin
- Sven Schäge

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-08-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ASIACRYPT 2024
publication_short: []

abstract: In this work, we present a new paradigm for constructing Group Authenticated Key Exchange (GAKE). This result is the first tightly secure GAKE scheme  in a strong security model that allows maximum exposure attacks (MEX) where the attacker is allowed to either reveal the secret session state or the long-term secret of all communication partners. Moreover, our protocol features the strong and realistic notion of (full) perfect forward secrecy (PFS), that allows the attacker to actively modify messages before corrupting parties. We obtain our results via a series of tightly secure transformations. Our first transformation is from weakly secure KEMs to unilateral authenticated key exchange (UAKE) with weak forward secrecy (WFS). Next, we show how to turn this into an UAKE with PFS in the random oracle model. Finally, and as one of our major novel conceptual contributions, we describe how to build GAKE protocols from UAKE protocols, also in the random oracle model. We apply our transformations to obtain two practical GAKE protocols with tight security. The first is based on the DDH assumption and features low message complexity. Our second result is based on the LWE assumption. In this way, we obtain the first GAKE protocol from a post-quantum assumption that is tightly secure in a strong model of security allowing MEX attacks. 

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: ''
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
