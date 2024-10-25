---
title: "Diffusion‐based Human Motion Style Transfer with Semantic Guidance"
collection: publications
permalink: /publication/2024-diffusion-based-style-transfer
excerpt: ''
date: 2024-08-01
venue: 'Proceedings of the ACM SIGGRAPH/Eurographics Symposium on Computer Animation'
paperurl: 'https://hlcdyy.github.io/diffusion-based-motion-style-transfer'
citation: 'Lei Hu, Zihao Zhang, Yongjing Ye, Yiwen Xu, and Shihong Xia. "Diffusion‐based Human Motion Style Transfer with Semantic Guidance. "SCA 24: Proceedings of the ACM SIGGRAPH/Eurographics Symposium on Computer Animation'
---
3D Human motion style transfer is a fundamental problem in computer graphic and animation processing. Existing AdaIN-based methods necessitate datasets with balanced style distribution and content/style labels to train the clustered latent space. However, we may encounter a single unseen style example in practical scenarios, but not in sufficient quantity to constitute a style cluster for AdaIN-based methods. Therefore, in this paper, we propose a novel two-stage framework for few-shot style transfer learning based on the diffusion model. Specifically, in the first stage, we pre-train a diffusion-based text-to-motion model as a generative prior so that it can cope with various content motion inputs. In the second stage, based on the single style example, we fine-tune the pre-trained diffusion model in a few-shot manner to make it capable of style transfer. The key idea is regarding the reverse process of diffusion as a motion-style translation process since the motion styles can be viewed as special motion variations. During the fine-tuning for style transfer, a simple yet effective semantic-guided style transfer loss coordinated with style example reconstruction loss is introduced to supervise the style transfer in CLIP semantic space. The qualitative and quantitative evaluations demonstrate that our method can achieve state-of-the-art performance and has practical applications. The source code is available at https://github.com/hlcdyy/diffusion-based-motion-style-transfer.

[Download paper here](https://dl.acm.org/doi/10.1111/cgf.15169)

Recommended citation: Hu, Lei, Zihao Zhang, Yongjing Ye, Yiwen Xu, and Shihong Xia. "Diffusion‐based Human Motion Style Transfer with Semantic Guidance." In Computer Graphics Forum, p. e15169. 2024.
