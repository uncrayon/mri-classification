# Clasificación de MRI y extracción de tumor masks
Este proyecto resulta del curso [_Reoconocimiento de Patrones y Aprendizaje Automatizado_](http://www.fciencias.unam.mx/docencia/horarios/presentacion/317863)

La primer parte de la red detectaría si en la imagen de resonancia magnética hay un tumor, de haber qué clase de tumor es y además aislar el área en la cual está el mismo.  
Para poder lograr esto se contruirá un pipeline que constará de una procesado de datos (estándarización), una CNN profunda (o alguna variante)^\[2-6\] y al final una extracción de carácteristicas mediante una U-Net^\[1\].

[image]!(./ilustraciones/pipeline_allData.png)

# References
\[1\] Ronneberger, O., Fischer, P., & Brox, T. (2015). U-net: Convolutional networks for biomedical image segmentation. In Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics) (Vol. 9351, pp. 234–241). Springer Verlag. https://doi.org/10.1007/978-3-319-24574-4_28 

\[2\] Farooq, A., Anwar, S., Awais, M., & Rehman, S. (2017). A deep CNN based multi-class classification of Alzheimer’s disease using MRI. IST 2017 - IEEE International Conference on Imaging Systems and Techniques, Proceedings, 2018-Janua, 1–6. https://doi.org/10.1109/IST.2017.8261460

\[3\] Kwok, S. (2018). Multiclass Classification of Breast Cancer in Whole-Slide Images. In Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics): Vol. 10882 LNCS (Issue 1). Springer International Publishing. https://doi.org/10.1007/978-3-319-93000-8_106

\[4\] Niu, X. X., & Suen, C. Y. (2012). A novel hybrid CNN-SVM classifier for recognizing handwritten digits. Pattern Recognition, 45(4), 1318–1325. https://doi.org/10.1016/j.patcog.2011.09.021

\[5\] Pan, L., Pouyanfar, S., Chen, H., Qin, J., & Chen, S. C. (2017). DeepFood: Automatic Multi-Class Classification of Food Ingredients Using Deep Learning. Proceedings - 2017 IEEE 3rd International Conference on Collaboration and Internet Computing, CIC 2017, 2017-Janua, 181–189. https://doi.org/10.1109/CIC.2017.00033

\[6\] Ronneberger, O., Fischer, P., & Brox, T. (2015). U-net: Convolutional networks for biomedical image segmentation. Lecture Notes in Computer Science (Including Subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics), 9351, 234–241. https://doi.org/10.1007/978-3-319-24574-4_28


