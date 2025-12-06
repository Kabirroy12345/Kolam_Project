\# Dataset Annotation Guidelines



This document outlines the standardized annotation protocol for the Hybrid Transform Rangoli Dataset — Version 1 (HTRD-1). Proper annotation ensures the dataset remains consistent, reproducible, and reliable for machine learning-based symmetry analysis.



---



\## 1. Image Acquisition and Selection



1\. Sources may include:

&nbsp;  - Original hand-drawn Rangoli images (preferred)

&nbsp;  - Publicly available festival Rangoli photographs with permissible rights

&nbsp;  - Digitally reconstructed Rangoli paintings preserving structural integrity



2\. Exclude images that:

&nbsp;  - Contain human subjects or identifiable personal data

&nbsp;  - Have poor lighting or excessive background noise

&nbsp;  - Are partially cropped or incomplete patterns



3\. Maintain diversity across:

&nbsp;  - Pattern size and density

&nbsp;  - Color presence (later converted to grayscale)

&nbsp;  - Festival and cultural variations



---



\## 2. Preprocessing Standards for Dataset Uniformity



| Operation | Specification |

|----------|---------------|

| Image Resizing | 256 × 256 pixels |

| Color Conversion | Grayscale |

| Background Cleaning | Binary mask applied if necessary |

| Orientation Handling | Center-aligned pattern in frame |

| File Format | `.jpg` or `.png` |



Edge highlighting or contour extraction may be stored as supplementary data but not replace original images.



---



\## 3. Class Label Assignment



Each Rangoli image must be annotated with one of the following 5 symmetry-based classes:



\### Class Definitions



| Class ID | Class Name | Description |

|---------|-------------|-------------|

| C1 | Rotational Symmetry | Exhibits circular or radial repetition around a center |

| C2 | Reflection Symmetry | Features bilateral symmetry across one or more axes |

| C3 | Grid / Dot Geometry | Constructed using aligned dots or grid-based geometry |

| C4 | Curvilinear Floral | Includes prominent curved structures, petals, floral shapes |

| C5 | Abstract / Asymmetric | Creative patterns lacking strong symmetry structure |



Annotation rule:  

> Choose the class that represents the \*\*dominant structural property\*\*.



---



\## 4. Metadata Recording



The annotation of each image must include:



| Field | Definition |

|------|------------|

| Image\_ID | Unique numeric or alpha-numeric identifier |

| Class\_ID | One of: C1, C2, C3, C4, C5 |

| Source | Origin of the image (Own/Internet/Generated) |

| Symmetry\_Axes\_Count | Estimated number of reflection axes |

| Rotation\_Order | Dominant rotational symmetry (e.g., 4-fold) |

| Noise\_Level | Low / Medium / High |

| Annotation\_By | Annotator name/initials |



Fields such as \*\*Fourier Symmetry Score (FSS)\*\* will be computed later and added during later phases of the research.



---



\## 5. Dataset Volume and Distribution



| Class | Minimum Target Count |

|-------|---------------------|

| C1 – Rotational Symmetry | 40 |

| C2 – Reflection Symmetry | 40 |

| C3 – Grid Geometry | 40 |

| C4 – Curvilinear Floral | 40 |

| C5 – Abstract / Asymmetric | 40 |

| \*\*Total Minimum\*\* | \*\*200 images\*\* |



Balanced class distribution is \*\*mandatory\*\* to prevent classification bias.



---



\## 6. Quality Control



\- At least \*\*two annotators\*\* should cross-verify difficult cases.

\- Annotation discrepancies must be documented in logs.

\- Any image found misclassified during model evaluation should be rechecked.



---



Adhering to these guidelines ensures that HTRD-1 is a robust, standardized, and academically credible dataset for future research in computational cultural heritage and hybrid symmetry modeling.



