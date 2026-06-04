---
title: An iterative method for Helmholtz boundary value problems arising in wave propagation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- F. Bernal
- Xingyuan Chen
- Gonçalo dos Reis

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-05-29T13:12:17.526294Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Computational and Applied Mathematics*'
publication_short: ''

doi: 10.1016/j.cam.2025.116581

abstract: The complex Helmholtz equation (Δ+k2)u=f (where k∈R,u(⋅),f(⋅)∈ℂ) is a mainstay
  of computational wave simulation. Despite its apparent simplicity, efficient numerical
  methods are challenging to design and, in some applications, regarded as an open
  problem. Two sources of difficulty are the large number of degrees of freedom and
  the indefiniteness of the matrices arising after discretisation. Seeking to meet
  them within the novel framework of probabilistic domain decomposition, we set out
  to rewrite the Helmholtz equation into a form amenable to the Feynman–Kac formula
  for elliptic boundary value problems. We consider two typical scenarios, the scattering
  of a plane wave and the propagation inside a cavity, and recast them as a sequence
  of Poisson equations. By means of stochastic arguments, we find a sufficient and
  simulatable condition for the convergence of the iterations. Upon discretisation
  a necessary condition for convergence can be derived by adding up the iterates using
  the harmonic series for the matrix inverse—we illustrate the procedure in the case
  of finite differences. From a practical point of view, our results are ultimately
  of limited scope. Nonetheless, the unexpected—even paradoxical—new direction of
  attack on the Helmholtz equation proposed by this work offers a fresh perspective
  on this classical and difficult problem. Our results show that there indeed exists
  a predictable range k<kmax in which this new ansatz works, with kmax being far below
  the challenging situation. © 2025 Elsevier B.V.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Choquet integral; convergence of numerical methods; domain decomposition methods;
  inverse problems; iterative methods; matrix algebra; poisson equation; boundary-value
  problem; condition; 
- discretizations; domain decompositions; efficient numerical
  method; feynman-kac formula; helmholtz; helmholtz's equations; iterative method
  for pde; wave simulations; helmholtz equation

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85219496228&doi=10.1016%2fj.cam.2025.116581&partnerID=40&md5=c02b63d820385a437a84e580777a9f69
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
