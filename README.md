# Learning shared and non-redundant label-specific features for partial multi-label classification
<P>
  Partial multi-label learning (PML) is designed to address the challenge of having both ground-truth labels and noisy labels in the label set of training instances. In real-world applications, there are often noisy features in addition to noisy labels, but existing PML methods fail to filter out these noisy features or account for feature correlations, label correlations, and feature-label correlations together in the feature learning process. These oversights lead to poor classification accuracy, as the comprehensive exploration of feature and label information in PML can contribute significantly to disambiguation. To address this issue, we propose a novel PML framework that disambiguates candidate labels and learns label-specific features while taking into account all three types of correlations between features and labels. First, we capture high-order label correlations by employing the low-rank representation to obtain a complementary label matrix induced from the partial label matrix, which accounts for the presence of noisy labels. Then, we learn a shared and non-redundant label-specific data representation by incorporating intrinsic feature correlations and the learned label correlations to mitigate the impact of noisy features. Finally, we build a classifier by mapping the label-specific feature representation to the complementary label matrix to model the feature-label correlations. Various experiments validate the superiority of our method.
</P>

<H2>References</H2>
This work has been published in Information Science:
<P>
  Zou Y, Hu X, Li P. Gradient-based multi-label feature selection considering three-way variable interaction[J]. Pattern Recognition, 2024, 145: 109900.
</P>

<H2>Source codes</H2>
Please see details from the following github website:

https://github.com/AGuRu123/LSNRLS
