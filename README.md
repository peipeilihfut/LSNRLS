# Learning shared and non-redundant label-specific features for partial multi-label classification
<P>
  Nowadays, Multi-Label Feature Selection (MLFS) attracts more and more attention to tackle the high-dimensional problem in multi-label data. A key characteristic of existing gradient-based MLFS methods is that they typically consider two-way variable correlations between features and labels, including feature-feature and label-label correlations. However, two-way correlations are not sufficient to steer feature selection since such correlations vary given different additional variables in practical scenarios, which leads to the selected features with relatively-poor classification performance. Motivated by this, we capture three-way variable interactions including feature-feature-label and feature-label-label interactions to further characterize the fluctuating correlations in the context of another variable, and propose a new gradient-based MLFS approach incorporating the above three-way variable interactions into a global optimization objective. Specifically, based on information theory, we develop second-order regularization penalty terms to regard three-way interactions while jointly combining with the main loss term in regard to feature relevance. Then the objective function can be efficiently optimized via a block-coordinate gradient descent schema. Meanwhile, we provide a theoretical analysis demonstrating the effectiveness of the regularization terms in exploiting three-way interaction. In addition, experiments conducted on a series of benchmark data sets also verify the validity of the proposed method on multiple evaluation metrics.
</P>

<H2>References</H2>
This work has been published in Information Science:
<P>
  Zou Y, Hu X, Li P. Gradient-based multi-label feature selection considering three-way variable interaction[J]. Pattern Recognition, 2024, 145: 109900.
</P>

<H2>Source codes</H2>
Please see details from the following github website:

https://github.com/AGuRu123/G3WI
