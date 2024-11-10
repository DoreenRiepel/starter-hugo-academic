---
title: "CCA Secure Updatable Encryption from Non-Mappable Group Actions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jonas Meers
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-04-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: PQCrypto 2024
publication_short: []

abstract: Ciphertext-independent updatable encryption (UE) allows to rotate encryption keys and update ciphertexts via a token without the need to first download the ciphertexts. Although, syntactically, UE is a symmetric-key primitive, ciphertext-independent UE with forward secrecy and post-compromise security is known to imply public-key encryption (Alamati, Montgomery and Patranabis, CRYPTO 2019). Constructing post-quantum secure UE turns out to be a difficult task. While lattices offer the necessary homomorphic properties, the introduced noise allows only a bounded number of updates. Group actions have become an important alternative, however, their structure is limited. The only known UE scheme by Leroux and Roméas (IACR ePrint 2022/739) uses effective triple orbital group actions which uses additional algebraic structure of CSIDH. Using an ideal cipher, similar to the group-based scheme SHINE (Boyd et al., CRYPTO 2020), requires the group action to be mappable, a property that natural isogeny-based group actions do not satisfy. At the same time, other candidates based on non-commutative group actions suffer from linearity attacks. For these reasons, we explicitly ask how to construct UE from group actions that are not mappable. As a warm-up, we present BIN-UE which uses a bit-wise approach and is CPA secure based on the well-established assumption of weak pseudorandomness and in the standard model. We then construct the first actively secure UE scheme from post-quantum assumptions. Our scheme COM-UE extends BIN-UE via the Tag-then-Encrypt paradigm. We prove CCA security in the random oracle model based on a stronger computational assumption. We justify the hardness of our new assumption in the algebraic group action model.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2024/499.pdf'
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
