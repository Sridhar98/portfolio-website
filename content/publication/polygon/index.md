---
title: "Guarding A Polygon Without Losing Touch"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Barath Ashok
- John Augustine
- Aditya Mehekare
- Sridhar Ragupathi
- Srikkanth Ramachandran
- Suman Sourav

# Author notes (optional)
author_notes:
- "Indian Institute of Technology, Madras"
- "National Institute of Technology, Trichy"
- "Advanced Digital Sciences Center, Singapore"

date: "2020-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *27th International Colloquium on Structural Information and Communication Complexity*
publication_short: In *SIROCCO 2020*

abstract: We study the classical Art Gallery Problem first proposed by Klee in 1973 from a mobile multi-agents perspective. Specifically, we require an optimally small number of agents (also called guards) to navigate and position themselves in the interior of an unknown simple polygon with n vertices such that the collective view of all the agents covers the polygon. We consider the visibly connected setting wherein agents must remain connected through line of sight links – a requirement particularly relevant to multi-agent systems. We first provide a centralized algorithm for the visibly connected setting that runs in time O(n), which is of course optimal. We then provide algorithms for two different distributed settings. In the first setting, agents can only perceive relative proximity (i.e., can tell which of a pair of objects is closer) whereas they can perceive exact distances in the second setting. Our distributed algorithms work despite agents having no prior knowledge of the polygon. Furthermore, we provide lower bounds to show that our distributed algorithms are near optimal. Our visibly connected guarding ensures that (i) the guards form a connected network and (ii) the polygon is fully guarded. Consequently, this guarding provides the distributed infrastructure to execute any geometric algorithm for this polygon.

# Summary. An optional shortened abstract.
summary: We study the classical Art Gallery Problem first proposed by Klee in 1973 from a mobile multi-agents perspective. Specifically, we require an optimally small number of agents (also called guards) to navigate and position themselves in the interior of an unknown simple polygon with n vertices such that the collective view of all the agents covers the polygon.

tags: ['Theoretical Computer Science','Distributed Algorithms','Graph Theory']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-54921-3_6'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""#example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
