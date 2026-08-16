---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article-journal']

authors:
  - khalil_alsalahat
  - mohamad_elmoussawi
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

title: "Quantum Meets SAR: A Novel Range-Doppler Algorithm for Next-Gen Earth Observation"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  -


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
  
featured: false
doi: "10.22059/eoge.2026.414020.1222"
date: "2025-10-27T00:00:00Z"

abstract: "Synthetic Aperture Radar (SAR) plays a vital role in remote sensing due to its ability to capture high-resolution images regardless of weather conditions or daylight. However, to transform the raw SAR signals into interpretable imagery, advanced data processing techniques are essential. A widely used technique for this purpose is the Range Doppler Algorithm (RDA), which takes advantage of Fast Fourier Transform (FFT) to convert signals into the frequency domain for further processing. However, the computational cost of this approach becomes significant when dealing with large datasets. This paper presents a Quantum Range Doppler Algorithm (QRDA) that utilizes the Quantum Fourier Transform (QFT) to offer a theoretical exponential processing speedup of up to N/(log N)^2 compared to the classical FFT. However, realizing this end-to-end acceleration in practice requires overcoming significant bottlenecks related to classical data amplitude encoding and quantum measurement overheads. Furthermore, it introduces a quantum implementation of the Range Cell Migration Correction (RCMC) in the Fourier domain, a critical step in the RDA pipeline that realigns the received echoes so that the energy from a target is concentrated in a single range bin across all azimuth positions. The performance of the quantum RCMC is evaluated and compared against its classical counterpart, as an isolated operation, and then as part of the full classical pipeline."

---
