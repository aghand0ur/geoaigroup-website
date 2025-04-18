---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['preprint']

authors:
  - mohamad_zahweh
  - hassan_wehbi
  - hasan_nasrallah
  - Zeinab Takach
  - veeraganesh_yalla
  - admin
  
url_pdf: "https://arxiv.org/pdf/2504.11366"
url_dataset: ""
url_project: "https://geogroup.ai/project/crop-monitoring/"
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "A Decade of Wheat Mapping for Lebanon"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - crop-monitoring


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2025-03-29T00:00:00Z"

abstract: "Wheat accounts for approximatly 20% of the world's caloric intake making it a vital component of global food secuirty. Given this significance, mapping wheat fields plays a crucial role in enabling various stakeholders including policymakers, researchers, and agricultural organizations to make informed decisions regarding food security, supply chain management, and resource allocation. 

In this paper, we tackle the problem of accurately mapping wheat fields out of satellite images by enhancing our previous work on winter wheat segmentation by creating an improved pipeline for processing data as well as presenting a decade-long analysis of wheat mapping in Lebanon. We integrate a Temporal Spatial Vision Transformer (TSViT) with Parameter-Efficient Fine Tuning (PEFT) and a novel post-processing pipeline based on the FOW delineation framework. 

Our enhanced pipeline addresses key challenges encountered in the previous approach such as clustering of small agricultural parcels in a single large field and sparse training labels. By merging wheat segmentation with precise field boundary extraction, our method produces geometrically coherent and semantically rich maps enabling us to perfom in-depth analysis such as calculating the total number of fields and tracking fields areas year over year. Extensive evaluations demonstrate improved boundary delineation and field-level precision, establishing the framework’s potential in operational agricultural monitoring and historical trend analysis.

This work lays the foundation for a range of critical studies and future advancements. Building on the accurate mapping of wheat fields, our approach provides a crucial step toward more sophisticated agricultural analyses. Future work can extend this methodology to improve yield estimation, crop monitoring and broader analysis of agricultural trends."

---
