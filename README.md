# A Multi-Domain Benchmark of Pretrained Vision Architectures: Performance Analysis in Biomedical Image Classification

## Abstract

This study benchmarks 20 ImageNet-pretrained vision models (convolutional, transformer, and hybrid
architectures) on eight biomedical image datasets from six domains: brain tumor MRI, tuberculosis,
skin lesions, retinal disease, histopathology, and pediatric pneumonia. All models are fine-tuned
with the same hyperparameters, and every experiment is repeated with three random seeds (480
training runs). Where patient identifiers are available, the data are split so that no patient
appears in more than one partition. Swin-B reaches the highest mean accuracy (87.39%), but the
five leading models lie within 1.10 percentage points, and the lightweight ConvNeXtV2-Atto
(3.4M parameters) reaches 85.65% with no significant rank difference from the leader. On
histopathology, patient-disjoint evaluation gives far lower accuracy than the image-level results
commonly reported, which shows that the evaluation protocol can matter more than the choice of
architecture.

## Code

The code will be released in this repository upon acceptance of the article.
