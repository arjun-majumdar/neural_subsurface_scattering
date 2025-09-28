# Neural Acquisition and Representation of Subsurface Scattering

This repository accompanies the paper:

**Neural Acquisition and Representation of Subsurface Scattering**
_Accepted at the International Conference on Vision, Modeling, and Visualization (VMV 2025)._

## 📖 Abstract
We present a method to acquire and estimate the sub-surface scattering properties of light transport at a highly detailed level by learning the pixel footprint response at each point on the object surface. The reconstruction leverages 3D scanning techniques as
input to a U-Net CNN. A stereo projector-camera setup using phase-shifted profilometry (PSP) patterns efficiently captures the data for a variety of scattering objects. Reconstructing dense pixel footprints allows for relighting with arbitrary high-resolution
projector patterns. The final output is a relit color image. Qualitative and quantitative comparison against illuminated real-world captured images demonstrate that the predicted footprints are almost identical to the actual responses. The same model
is trained for multiple views across multiple objects such that the learned representations can be used to generalize to unseen sub-surface scattering materials as well.


## 🧩 Contributions
1. We learn anisotropic pixel footprint responses to capture subsur-face scattering properties by only using projected high-frequency phase-shift patterns which can at the same time be used for 3D
scanning.
2. A neural network estimates footprint responses for each point on the object which then are used to perform relighting with spatially varying light patterns in RGB colorspace of the image.
3. Our neural network architecture is able to generalize across multiple views and multiple objects, which we verify both qualitatively and quantitatively.


## 📊 Results
Our method produces a relightable representation of subsurface scattering objects by predicting per-pixel, spatially varying scattering footprints from only six input images. These images are captured using high-frequency horizontal and vertical sinusoidal patterns. A trained U-Net translates the phase-shifted profilometry inputs into scattering representations, which can simultaneously be used for 3D geometry acquisition.
Representative comparisons and visual results are provided in the paper and supplementary material.


## 📨 Contact
For questions, comments, or collaborations, please contact:
1. [Arjun Majumdar] – [arjun.majumdar@uni-tuebingen.de
2. [Raphael Braun] - [keyraphi@gmail.com]
3. [Prof. Dr. Hendrik Lensch] - [hendrik.lensch@uni-tuebingen.de]


## 🔗 Citation
Coming soon!

