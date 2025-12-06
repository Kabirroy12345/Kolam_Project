\# Problem Statement



Rangoli is a traditional Indian geometric art form characterized by intricate patterns, rotational symmetry, reflectional symmetry, and culturally significant motifs. While Rangoli holds strong cultural value, its mathematical structure remains largely unexplored in computational research. Existing computer vision studies on traditional art focus predominantly on motif recognition or basic pattern analysis but do not investigate hybrid feature extraction strategies or quantitative symmetry assessment.



Recent advancements in deep learning, particularly Convolutional Neural Networks (CNNs), have shown remarkable performance in visual feature extraction for image classification. Meanwhile, classical mathematical transforms such as the Fast Fourier Transform (FFT), Laplace Transform, and Z-transform are highly effective in analyzing frequency-domain characteristics, structural textures, and boundary variations of images. However, these two domains have rarely been combined to study handcrafted cultural visual patterns like Rangoli.



This research aims to bridge this gap by developing a hybrid feature extraction pipeline utilizing both CNN-based deep descriptors and transform-domain mathematical features to model the underlying symmetry properties of Rangoli patterns. Furthermore, a novel metric termed the \*\*Fourier Symmetry Score (FSS)\*\* will be introduced to quantitatively evaluate symmetry fidelity and structural quality of Rangoli designs.



The primary objectives of this study are:



1\. To create a labeled dataset of traditional Rangoli patterns categorized based on symmetry characteristics, including rotational symmetry, reflectional symmetry, grid-based geometry, curvilinear floral patterns, and asymmetric/abstract patterns.

2\. To design a hybrid deep learning architecture that integrates CNN-derived visual features with FFT/Laplace/Z-transform based frequency and contour features.

3\. To propose and mathematically define the \*\*Fourier Symmetry Score (FSS)\*\* as a measure to quantify visual balance and symmetry consistency in Rangoli patterns.

4\. To evaluate the performance of hybrid feature extraction against standalone CNN and transform-based classification models.

5\. To conduct comparative experiments demonstrating improvements in classification performance, interpretability, and symmetry quality assessment.



This work contributes to the emerging intersection of \*\*computer vision\*\*, \*\*mathematical morphometry\*\*, and \*\*cultural computational analysis\*\*. Through this framework, we aim to establish a reproducible methodology and publish a foundational dataset for future research in computational cultural heritage and symmetry-based pattern recognition.



