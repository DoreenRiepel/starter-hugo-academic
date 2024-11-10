---
title: "On the Tight Security of the Double Ratchet"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Collins
- admin
- Si An Oliver Tran

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-08-12T00:00:00Z"
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

abstract: The Signal Protocol is a two-party secure messaging protocol used in applications such as Signal, WhatsApp, Google Messages and Facebook Messenger and is used by billions daily. It consists of two core components, one of which is the Double Ratchet protocol that has been the subject of a line of work that aims to understand and formalise exactly what security it provides. Existing models capture strong guarantees including resilience to state exposure in both forward security (protecting past secrets) and post-compromise security (restoring security), adaptive state corruptions, message injections and out-of-order message delivery. Due to this complexity, prior work has failed to provide security guarantees that do not degrade in the number of interactions, even in the single-session setting. Given the ubiquity of the Double Ratchet in practice, we explore tight security bounds for the Double Ratchet in the multi-session setting. To this end, we revisit the modelling of Alwen, Coretti and Dodis (EUROCRYPT 2019) who decompose the protocol into modular, abstract components, notably continuous key agreement (CKA) and forward-secure AEAD (FS-AEAD). To enable a tight security proof, we propose a CKA security model that provides one-way security under key checking attacks.  We show that multi-session security of the Double Ratchet can be tightly reduced to the multi-session security of CKA and FS-AEAD, capturing the same strong security guarantees as Alwen et al. Our result improves upon the bounds of Alwen et al. in the random oracle model. Even so, we are unable to provide a completely tight proof for the Double Ratchet based on standard Diffie-Hellman assumptions, and we conjecture it is not possible. We thus go a step further and analyse CKA based on key encapsulation mechanisms (KEMs). In contrast to previous works, our new analysis allows for tight constructions based on the DDH and post-quantum assumptions.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2024/1625.pdf'
url_code: ''
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