# Training a deep operator network as a surrogate solver for 2D parabolic-equation
Train DeepONet as Surrogate solver of Underwater Acoustic Model(RAMv1.5).
Code and data will be publicly available after the peer review process is complete.

## Abstract
Parabolic equations (PEs) are useful for modeling sound propagation from a point
in a range-dependent environment. However, this approach entails approximating
a leading-order cross-derivative term in the PE square-root operators. Deep opera-
tor networks (DeepONets) are designed to approximate operators. Thus, we train
DeepONets to take the sound pressure and speed of sound of any depth location
of interest as inputs. In this paper, DeepONets are trained to approximate the PE
square-root operator in modeling 2D sound propagation. Once trained, a network can
predict the far field for a wide variety of environmental conditions, without needing
to approximate the operator or calculate the whole mode trajectory, and at a lower
computational cost. The original DeepONet learns the operator of a single function.
By contrast, the modified version presented here learns multiple-input operators with
Fourier features. Using computational and theoretical examples, we demonstrate that
DeepONet is eﬀicient for learning complex ocean acoustic physics with good accuracy.
