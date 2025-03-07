---
title: "Count Corruptions, Not Users: Improved Tightness for Signatures, Encryption and Authenticated Key Exchange"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mihir Bellare
- admin
- Stefano Tessaro
- Yizhao Zhang

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

abstract: In the multi-user with corruptions (muc) setting there are n≥1 users, and the goal is to prove that, even in the face of an adversary that adaptively corrupts users to expose their keys, un-corrupted users retain security. This can be considered for many primitives including signatures and encryption. Proofs of muc security, while possible, generally suffer a factor n loss in tightness, which can be large. This paper gives new proofs where this factor is reduced to the number c of corruptions, which in practice is much smaller than n. We refer to this as corruption-parametrized muc (cp-muc) security. We give a general result showing it for a class of games that we call local. We apply this to get cp-muc security for signature schemes (including ones in standards and in TLS 1.3) and some forms of public-key and symmetric encryption. Then we give dedicated cp-muc security proofs for some important schemes whose underlying games are not local, including the Hashed ElGamal and Fujisaki-Okamoto KEMs and authenticated key exchange. Finally, we give negative results to show optimality of our bounds.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2024/1258.pdf'
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
