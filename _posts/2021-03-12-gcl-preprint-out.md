---
layout: post
title:  "Generalized Contrastive Loss preprint is out!"
date:   2021-03-12 20:00:00 +0200
categories: publications
---

I'm happy to share the preprint of my latest paper, titled "Generalized Contrastive Optimization of Siamese Networks for Place Recognition", which can be found on [arXiv](https://arxiv.org/abs/2103.06638). 

I propose a new contrastive loss function, namely the Generalized Contrastive Loss, that relies on a graded definition of image similarity ground truth. This function, together with the new ground truth allows us to train a siamese architecture without relying on overcomplicated pair mining strategies and using only simple pooling layers (GeM and average), outperforming more complex state-of-the-art approaches like NetVLAD.

Find the testing code and new sets of labels for the MSLS, TB-Places, and 7Scenes datasets on [the github repository](https://github.com/marialeyvallina/generalized_contrastive_loss).