---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['preprint']

authors:
  - Ali Ahmad Faour
  - Nabil Amacha
  - admin
  
url_pdf: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "50 Years of Water Body Monitoring: The Case of Qaraaoun Reservoir, Lebanon"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - qaraaoun-reservoir


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2025-10-27T00:00:00Z"

abstract: "The sustainable management of the Qaraaoun Reservoir, the largest surface water body in Lebanon, located in the Bekaa Plain, hinges on reliable monitoring of its storage volume despite frequent sensor malfunctions and limited maintenance capacity. This study introduces a sensor-free approach that integrates open-source satellite imagery, advanced water-extent segmentation, and machine learning to estimate the reservoir surface area and then the volume in near real-time. Sentinel-2 and Landsat 1-9 images are processed where surface water is delineated using a newly proposed water segmentation index. A machine learning model based on Support Vector Regression (SVR) is trained on a curated dataset that includes water surface, water level and water volume calculation using reservoir bathymetry survey. The model is then able to estimated waterbody volume relying solely on water surface, extracted from satellite imagery without the need of any ground measurements. Water segmentation using the proposed index aligns with ground truth over $95\%$ of the shoreline. Hyperparameter tuning with GridSearchCV yields an optimized SVR performance with error under $1.5\%$ of full reservoir capacity and coefficients of determination exceeding $0.98$. These results demonstrate the method’s robustness and cost-effectiveness, offering a practical solution for continuous, sensor-independent monitoring of reservoir storage. The proposed methodology can be replicated to other water bodies, and the resulting 50+ years of time-series data is crucial for researchers studying climate change and environmental patterns."
---
