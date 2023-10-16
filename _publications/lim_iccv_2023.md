---
title: "Image Guided Inpainting with Parameter Efficient Learning"
collection: publications
permalink: /publication/lim_iccv_2023
date: Oct. 2023
venue: 'Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops, 2023'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2023W/LIMIT/html/Lim_Image_Guided_Inpainting_with_Parameter_Efficient_Learning_ICCVW_2023_paper.html'
---

**Abstract**

Conditional inpainting is the challenging task of generating images that fill in specific regions of an image while preserving the surrounding details, based on an arbitrary binary mask and a specified condition (e.g., text or image). Existing methods for conditional inpainting often struggle to preserve the appearance of the user's subject in the input images and can be computationally expensive to tune for each new condition. In this paper, we propose a novel approach to conditional inpainting that combines an Image Guided Inpainting model with a Denoising Diffusion Probabilistic Model (DDPM). Our approach trains the DDPM model using a small number of user-provided images, enabling users to insert a subject into any scene even if the poses and views were not present in the tuning data. We also propose a parameter-efficient method for training the DDPM that preserves its core performance while reducing the number of retrained parameters. Our experimental results demonstrate that our proposed approach outperforms existing methods in terms of both reconstruction quality and computational efficiency, making it well-suited for use in low-resource environments. Overall, our approach offers a valuable baseline for future research on guided inpainting and personalization.
