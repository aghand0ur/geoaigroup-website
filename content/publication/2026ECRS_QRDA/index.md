---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

authors:
  - mohamad_elmoussawi
  - admin
  - khalil_alsalahat
  
url_pdf: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
url_slides: "https://geogroup.ai/publication/2026ECRS_QRDA/slides_2026ECRS_QRDA.pdf"
url_poster: ""
url_code: ""
slides: null

title: "Quantum Range-Doppler Algorithm: An End-to-End Quantum Circuit for SAR Image Formation"
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
#doi: "10.1109/JSTARS.2022.3181446"
date: "2026-10-19T00:00:00Z"

abstract: "Synthetic Aperture Radar (SAR) is a critical remote sensing technology widely used for Earth observation, but the processing of high-resolution SAR raw data remains computationally demanding on classical computing architectures. As quantum computing hardware and algorithms continue to advance, they offer a promising paradigm for accelerating computationally intensive signal processing tasks, motivating the development of quantum-native SAR image formation methods.

In our earlier work, we introduced a quantum implementation of Range Cell Migration Correction (RCMC), a critical stage of the Range-Doppler Algorithm (RDA). Building on that foundation, this paper presents a complete quantum realization of the RDA for SAR image formation. We introduce a dedicated quantum circuit architecture based on amplitude encoding, enabling efficient representation of complex SAR raw data within a quantum state space. The proposed framework performs the principal stages of the RDA entirely in the quantum domain, employing Quantum Fourier Transforms (QFTs) for spatial-frequency transformations and specialized diagonal unitary operators for range compression, RCMC, and azimuth compression.

To validate the proposed methodology, the architecture is simulated using the Qiskit Aer statevector simulator on a representative 4×4 SAR raw data matrix. The results demonstrate the successful execution of the complete processing chain, including all quantum phase operations and frequency-domain transformations. The recovered processed state exhibits mathematical consistency with the expected outcome of classical SAR focusing, confirming the correctness and feasibility of the proposed implementation.

By extending a quantum realization of a single RDA component to a complete end-to-end quantum SAR focusing pipeline, this work establishes a rigorous framework for translating classical SAR image formation algorithms into their quantum equivalents. These results provide a foundation for future scalable quantum SAR processing systems and next-generation Earth observation applications."

---
