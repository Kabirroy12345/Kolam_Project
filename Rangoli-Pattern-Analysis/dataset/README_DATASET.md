\# Hybrid Transform Rangoli Dataset – Version 1 (HTRD-1)



The Hybrid Transform Rangoli Dataset (HTRD-1) is an original dataset created for the research problem of symmetry-based pattern recognition in traditional Indian Rangoli art forms. The dataset currently consists of a minimum of 200 high-quality Rangoli images, categorized based on dominant symmetry characteristics.



This dataset is intended for academic and research purposes in the fields of computer vision, mathematical pattern analysis, and computational cultural heritage.



---



\## Dataset Description



| Property | Specification |

|---------|---------------|

| Total Images | Minimum 200 (Phase-1) |

| Classes | 5 Symmetry-based categories |

| Image Format | `.jpg` or `.png` |

| Resolution | Standardized to 256 × 256 px |

| Color Space | Grayscale |

| Preprocessing | Background noise cleaned, centered alignment |



\### Symmetry-based Class Labels



| Class Code | Class Name |

|------------|------------|

| C1 | Rotational Symmetry |

| C2 | Reflection Symmetry |

| C3 | Grid / Dot Geometry |

| C4 | Curvilinear Floral |

| C5 | Abstract / Asymmetric |



---



\## Folder Structure

dataset/

│

├─ images/

│ ├─ class\_01/ # Rotational symmetry

│ ├─ class\_02/ # Reflection symmetry

│ ├─ class\_03/ # Grid/dot geometry

│ ├─ class\_04/ # Curvilinear floral

│ └─ class\_05/ # Abstract/asymmetric

│

├─ metadata.csv

└─ README\_DATASET.md



---



\## Metadata Fields



Each image entry in the metadata.csv file contains:



\- Image\_ID

\- Class\_ID (C1–C5)

\- Symmetry\_Axes\_Count

\- Rotation\_Order

\- Source (Own/Internet/Generated)

\- Noise\_Level (Low/Medium/High)

\- Annotation\_By

\- Notes (optional)



---



\## Usage Policy



\- This dataset is allowed for \*\*non-commercial research and educational use\*\*.

\- Proper citation must be provided in any published work.

\- Redistribution without permission is discouraged until final publication.



\*\*Citation:\*\*

> Roy, K. \& Team (2025). Hybrid Transform Rangoli Dataset – Version 1 (HTRD-1).



---



\## Future Extensions



Next versions will incorporate:



✔ Fourier Symmetry Score (FSS) annotations  

✔ Transform-domain features  

✔ Larger dataset size (500+ images)  

✔ Additional cultural subclasses  



---



For questions or collaboration requests:  

\*\*Project Leads:\*\* Parshv Modi \& Kabir Roy — VIT Bhopal University







