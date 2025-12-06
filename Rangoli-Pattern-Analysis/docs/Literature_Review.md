\# Literature Review



Computer vision research has increasingly focused on the recognition, interpretation, and preservation of cultural artifacts. Traditional visual crafts such as Mandalas, Islamic geometric art, and Indian Rangoli provide rich opportunities for computational pattern analysis due to their deep mathematical grounding in symmetry, geometry, and repetition.



\### 1. Deep Learning for Traditional Art Analysis

Convolutional Neural Networks (CNNs) have proven effective for pattern-based classification tasks across various cultural art domains. Studies on Mandala classification, Islamic tessellation recognition, and Warli tribal art segmentation highlight the capability of CNN architectures to learn visually discriminative spatial features. However, pure deep learning methods often treat cultural artwork as ordinary images, failing to capture underlying mathematical rules or symmetry constraints that govern artistic composition.



\### 2. Transform-Domain Feature Extraction

The Fast Fourier Transform (FFT) has been widely used for analyzing periodicity, rotational characteristics, and global structure of patterns. Laplace transforms greatly assist in detecting contour sharpness and variation, while Z-transforms offer efficient representation for discrete rotational variations. Prior works have successfully applied these transforms for:



\- Texture classification

\- Shape-based retrieval

\- Biomedical image symmetry assessment



Nevertheless, transform-based techniques lack the robust high-level semantic understanding that deep learning models provide.



\### 3. Hybrid Feature Fusion in Vision Research

Combining deep-learning-based features with handcrafted and mathematical descriptors has gained significant momentum in applications such as:



\- Medical image diagnostics

\- Remote sensing scene classification

\- Cultural object recognition



Hybrid systems often outperform individual methods by bridging spatial and frequency domains. Yet, there is limited research integrating transform-domain signal analysis with CNN features specifically for \*\*symmetry-driven cultural art classification\*\*, such as Rangoli.



\### 4. Computational Symmetry Assessment

Symmetry plays a critical role in aesthetic perception and structural stability in traditional art. Studies involving Fourier descriptors and radial projections demonstrate promising methods for symmetry measurement. Existing metrics primarily evaluate:



\- Radial symmetry magnitude

\- Axis-based reflection accuracy

\- Shape alignment error



However, none of these have been specifically adapted to analyze handcrafted cultural designs with free-form imperfections.



\### Research Gap



While deep learning can classify Rangoli patterns and transforms can analyze symmetry, there exists no unified framework that:



✔ Extracts hybrid deep and mathematical features  

✔ Classifies Rangoli based on symmetry characteristics  

✔ Introduces a \*\*novel symmetry scoring metric\*\*  

✔ Provides a publicly usable Rangoli dataset for future research  



\### Conclusion of Literature Gap



This study proposes the first hybrid CNN + FFT/Laplace/Z-transform approach for Rangoli symmetry modeling, combined with a new metric — the \*\*Fourier Symmetry Score (FSS)\*\* — to establish a quantifiable standard for visual balance and cultural pattern quality assessment.



