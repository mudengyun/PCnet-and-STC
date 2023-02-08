# A Hybrid PCNet and Spatiotemporal Classifier Model for Image Denoising and Classification
Abstract-Images usually suffer from noise in some real-world scenarios and thus degrade the classification performance. A natural solution is to first perform a denoising procedure and then feeding the restoration to a classification system. In this paper, we present a hybrid denoising and classification model in the pursuit of high-quality images and their meaningful information for optimal classification. To achieve this objective, we first compute a flexible and accurate solution for the denoising problem by a modified optimization method combined with deep neural networks and then unfold the solution into a deep network named predictor-corrector network (PCNet). Meanwhile, a novel unsupervised training strategy from our previous work is cited to optimize the PCNet without the need of clean targets. After denoising, a novel classification system is designed to encode spatial representations of dynamic images and hidden temporal representations of multivariate time series data into the spatiotemporal information, enabling the internal classifier to make accurate decisions. Exhaustive experiments are conducted in a real-world scenario to validate the hybrid model. Results show the necessity of the denoising procedure and the superiority of the proposed PCNet over the popular competing denoising methods as well as the effectiveness of the proposed classification system. In particular, the hybrid model achieves state-of-the-art classification performance with averaged accuracy = 0.852, averaged precision = 0.838, averaged recall = 0.959 and averaged F1-score = 0.880. While we demonstrate the proposed PCNet in the denoising problem, PCNet is generally applicable to arbitrary inverse problems.
https://github.com/weikechang/PCnet-and-STC/blob/main/fig1.png
