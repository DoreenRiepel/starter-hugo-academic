---
title: "Intermundium-DL: Assessing the Resilience of Current Schemes to Discrete-Log-Computation Attacks on Public Parameters"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mihir Bellare
- admin
- Laura Shea

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-01-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: PKC 2025
publication_short: []

abstract: We consider adversaries able to perform a nonzero but small number of discrete logarithm computations, as would be expected with near-term quantum computers. Schemes with public parameters consisting of a few group elements are now at risk; could an adversary knowing the discrete logarithms of these elements go on to easily compromise the security of many users? We study this question for known schemes and find, across them, a perhaps surprising variance in the answers. In a first class are schemes, including Okamoto and Katz-Wang signatures, that we show fully retain security even when the discrete logs of the group elements in their parameters are known to the adversary. In a second class are schemes like Cramer-Shoup encryption and the SPAKE2 password-authenticated key exchange protocol that we show retain some partial but still meaningful and valuable security. In the last class are schemes we show by attack to totally break. The distinctions uncovered by these results shed light on the security of classical schemes in a setting of immediate importance, and help make choices moving forward.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://eprint.iacr.org/2025/663.pdf'
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
