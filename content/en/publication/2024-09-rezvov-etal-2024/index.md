---
title: "Improving data-driven estimation of significant wave height through preliminary training on synthetic X-band radar sea clutter imagery"
authors:
- vadim_rezvov
- admin
- Alexander Gavrikov
- viktor_golikov
- mikhail_borisov
- Alexander Suslov
- Natalia Tilinina
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2024-09-27T00:00:00Z"
doi: "10.3389/fmars.2024.1363135"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Frontiers in Marine Science, 11-2024"
publication_short: ""

abstract: X-band marine radar captures the signal reflected from the sea surface. Theoretical studies indicate that the initial unfiltered signal contains meaningful information about wind wave parameters. Traditional methods of significant wave height (SWH) estimation rely on physical laws describing signal reflection from rough surfaces. However, recent studies suggest the feasibility of employing artificial neural networks (ANNs) for SWH approximation. Both classical and ANN based approaches necessitate costly in situ data. In this study, as a viable alternative, we propose generating synthetic radar images with specified wave parameters using Fourier-based approach and Pierson–Moskowitz wave spectrum. We generate synthetic images and use them for unsupervised learning approach to train a convolutional component of the reconstruction ANN. After that, we train the regression ANN based on the previous convolutional part to obtain SWH back from the synthetic images. Then, we apply preliminary trained weights for the regression model to train SWH approximation on the dataset of real sea clutter images. In this study, we demonstrate the increase in SWH estimation accuracy from radar images with preliminary training on synthetic data.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Applied deep learning
- Marine radars
- Wind waves 
featured: false

# links:
# - name: ""
# url: ""
# url_pdf: 
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
