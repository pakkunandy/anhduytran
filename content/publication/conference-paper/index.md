---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Quoc-Trung Nguyen
  - Anh-Minh Nguyen
  - Minh-Triet Tran

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: '10.1109/ICIS54925.2022.9882517'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE/ACIS 22nd International Conference on Computer and Information Science (ICIS)*
publication_short: In *ICIS 2022*

abstract: In the age of rapid development of the Internet of Things (IoT) world, more and more cybersecurity incidents have emerged in many IoT devices and systems. Therefore, the need for cybercrime investigation, especially for IoT devices, has become more imperative than ever. Memory forensics, the approach that inspects the memory dump to understand the current state or behavior of the attacked machine, contributes an important position in digital forensics and incident response for IoT systems. However, memory forensics encounter various challenges, including virtual address space (VAS) reconstruction or extracting kernel data structure in a given memory image. Most current tools and approaches leverage the knowledge of the operating system or propose heuristics to evade the commission of rebuilding VAS. In this research, we present our novel methodology to reconstruct the VAS for the memory images by using the paging mechanism of the Central Processing Unit (CPU), primarily for the ARM architectures (32 and 64 bit), one of the most popular microprocessors in the IoT world. In addition, with the support of VAS, we extract the typical kernel data structure like the process linked list. Finally, we build a MemInspect2 toolset that gathers all algorithms, and we also test the tool in many standard OS kernels like Linux and BSD.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [memory forensics, ARM architectures, paging structure, process lists, IoT forensics;]

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

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

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
