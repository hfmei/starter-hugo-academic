---
title: 'DE-CrossDet: Divisible and Extensible Crossline Representation for Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hefei Mei
  - Hongliang Li
  - Heqian Qiu
  - Jianhua Cui
  - Longrong Yang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-08-16T00:00:00Z'
doi: '10.1109/VCIP56404.2022.10008820'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Visual Communications and Image Processing*
publication_short: In *VCIP 2022*

abstract: Object detection aims to localize and classify objects. Suitable object representation plays an important role in accurate detection. Because a complete crossline inevitably passes through the noise of backgrounds or other objects, object features directly extracted by the whole crossline are often confused. In this paper, we present a new feature extraction method, DE-Crossline, which can enhance the original crossline representation to capture more accurate object information. Specifically, we divide the crossline into several segments, each of which extracts the maximum activation key point respectively to reduce the impact of noise mentioned above. Furthermore, considering various shapes and sizes of objects, we design a Deformable Width Extension Module to learn a suitable width of each crossline, so as to capture richer object information. Extensive experiments prove the effectiveness of our proposed method. The total performance of our proposed detector can reach 49.0% AP, using ResNet-101 as backbone on the MS-COCO dataset.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
