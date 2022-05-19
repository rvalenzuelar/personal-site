---
title: Read CR2 meteorological dataset
subtitle: 

# Summary for listings and search engines
summary: .

# Link this post with a project
projects: []

# Date published
date: '2019-12-12T00:00:00Z'

# Date updated
lastmod: '2019-12-12T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
#   focal_point: ''
#   placement: 2
#   preview_only: false

authors:
  - admin

tags:
  - snippets
  - python

categories:
  - python
---

This is a python snippet to read the csv file:

```python
import pandas as pd

data_file = 'cr2_prDaily_2019.txt'
meta_file = 'cr2_prDaily_2019_stations.txt'

ds = pd.read_csv(data_file, skiprows=range(1,17),
                            parse_dates=[0],
                            index_col=0,
                            na_values=-9999.0)

st = pd.read_csv('cr2_prDaily_2019_stations.txt')
```