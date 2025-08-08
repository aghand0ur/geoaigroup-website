---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

authors:
  - hasan_moughnieh
  - mohamad_chalhoub
  - hasan_nasrallah
  - cristiano_nattero
  - Paolo Campanella
  - Giovanni Nico
  - admin
  
url_pdf: 
url_dataset: ""
url_project: "https://geogroup.ai/project/vlm4eo/"
url_source: ""
url_video: ""
url_slides: "https://geogroup.ai/publication/2025igarss_efficientadaptation/Slides_2025IGARSS_EfficientAdaptation_FM.pdf"
url_poster: ""
url_code: ""
slides: null

title: "Efficient Adaptation For Remote Sensing Visual Grounding"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - VLM4EO


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "LaLGA: Multi-Scale Language-Aware Visual Grounding on Remote Sensing Data"
  focal_point: ""
  preview_only: false
  
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2025-02-25T00:00:00Z"

abstract: "Foundation models have revolutionized artificial intelligence (AI), offering remarkable capabilities across multi-modal domains. Their ability to precisely locate objects in complex aerial and satellite images, using rich contextual information and detailed object descriptions, is essential for remote sensing (RS). These models can associate textual descriptions with object positions through the Visual Grounding (VG) task, but due to domain-specific challenges, their direct application to RS produces sub-optimal results.
To address this, we applied Parameter Efficient Fine Tuning (PEFT) techniques to adapt these models for RS-specific VG tasks. Specifically, we evaluated LoRA placement across different modules in Grounding DINO and used BitFit and adapters to fine-tune the OFA foundation model pre-trained on general-purpose VG datasets. This approach achieved performance comparable to or surpassing current State Of The Art (SOTA) models while significantly reducing computational costs.
This study highlights the potential of PEFT techniques to advance efficient and precise multi-modal analysis in RS, offering a practical and cost-effective alternative to full model training."

---
