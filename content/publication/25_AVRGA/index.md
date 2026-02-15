---
title: "ABE Cubed: Advanced Benchmarking Extensions for ABE Squared"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sven Argo
- Marloes Venema
- admin
- Tim Güneysu
- Diego F. Aranha

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-06-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: CHES 2025
publication_short: []

abstract: Since attribute-based encryption (ABE) was proposed in 2005, it has established itself as a valuable tool in the enforcement of access control. For practice, it is important that ABE satisfies many desirable properties such as multi-authority and negations support. Nowadays, we can attain these properties simultaneously, but none of these schemes have been implemented. Furthermore, although simpler schemes have been optimized extensively on a structural level, there is still much room for improvement for these more advanced schemes. However, even if we had schemes with such structural improvements, we would not have a way to benchmark and compare them fairly to measure the effect of such improvements. The only framework that aims to achieve this goal, ABE Squared (TCHES '22), was designed with simpler schemes in mind. In this work, we propose the ABE Cubed framework, which provides advanced benchmarking extensions for ABE Squared. To motivate our framework, we first apply structural improvements to the decentralized ciphertext-policy ABE scheme supporting negations presented by Riepel, Venema and Verma (ACM CCS '24), which results in five new schemes with the same properties. We use these schemes to uncover and bridge the gaps in the ABE Squared framework. In particular, we observe that advanced schemes depend on more "variables" that affect the schemes' efficiency in different dimensions. Whereas ABE Squared only considered one dimension (as was sufficient for the schemes considered there), we devise a benchmarking strategy that allows us to analyze the schemes in multiple dimensions. As a result, we obtain a more complete overview on the computational efficiency of the schemes, and ultimately, this allows us to make better-founded choices about which schemes provide the best efficiency trade-offs for practice.

# Summary. An optional shortened abstract.
# summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2025/1230.pdf'
url_code: 'https://github.com/lincolncryptools/ABE_Cubed'
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