---
permalink: /research.html
title: "Research"
excerpt: "Our research"
author_profile: true
---

Here is an overview over three research directions:
<ul>
  <li><a href="#structure">The impact of data structure on learning</a></li>
  <li><a href="#dynamics">Dynamics of learning</a></li>
  <li><a href="#efficiency">Energetic efficiency of learning</a></li>
</ul>

<h2 id="structure">The impact of data structure on learning</h2>

<p>
<div style="float:right; text-align:center; width:300px">
<img src="images/data_structure.png" alt="The hidden manifold"
    title="The hidden manifold" width="300" height="300" style="
    margin: 5px" /><br/>
<i style="font-size:90%">Realistic images concentrate on a low-dimensional
manifold in input space.</i>
</div>

How does the structure of real-world data impact learning in neural networks?
This is a key challenge for the theory of deep learning. We started addressing
this question by introducing a model for structured data sets that we call the
“hidden manifold model” (HMM) [1]. The HMM is a statistical model for generating
high-dimensional data from low-dimensional inputs. We showed experimentally that
the HMM reproduces some effects seen when training neural networks on practical
data sets for image classification. We also introduced analytical techniques
[1,2] which allow us to study the dynamics and the performance of two-layer
neural networks analytically.  </p>

### References

1. SG, B. Loureiro, G. Reeves, M. Mézard, F. Krzakala, and L. Zdeborová <br/>
  _The Gaussian equivalence of generative models for learning with two-layer neural networks_<br/>
  [arXiv:2006.14709](https://arxiv.org/abs/2006.14709)
2. SG, M. Mézard, F. Krzakala, and L. Zdeborová<br/>
  _Modelling the influence of data structure on learning in neural networks: the
  hidden manifold model_<br/>
  [Phys. Rev. X *10*, 041044](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.10.041044)
  (2020) [arXiv:1911.00500](https://arxiv.org/abs/1909.11500)


<h2 id="dynamics">The dynamics of learning</h2>

<p>
<div style="float:right; text-align:center; width:300px">
<img src="images/dynamics.png" alt="The dynamics of learning"
    title="The dynamics of learning" width="300" height="300" style="
    margin: 5px" /><br/>
<i style="font-size:90%">The learning algorithm shapes the path of neural
networks in the losslandscape. Image courtesy of
S. d'Ascoli </i>
</div>

Understanding the dynamics of learning in neural networks is a key step in
understanding their performance. We are interested in the analysis of standard
algorithms to train neural networks, i.e. the backpropagation algorithm [1], but
we are increasingly interested in studying alternatives to backprop, such as
feedback alignment algorithms [2].  </p>

### References

- M. Refinetti, S. d'Ascoli, R. Ohana, SG<br/>
  _The dynamics of learning with feedback alignment_<br/>
  [arXiv:2011.12428](https://arxiv.org/abs/2011.12428)
- SG, M.S. Advani, A.M. Saxe, F. Krzakala, L. Zdeborová<br/>
  _Dynamics of stochastic gradient descent for two-layer neural networks in the teacher-student setup_<br/>
  Advances in Neural Information Processing [(NeurIPS) 6979-6989 (2019)](https://proceedings.neurips.cc/paper/2019/hash/cab070d53bd0d200746fb852a922064a-Abstract.html) [arXiv:1906.08632](https://arxiv.org/abs/1906.08632)



<h2 id="efficiency">Energetic efficiency of learning</h2>

<p>
<div style="float:right; text-align:center; width:320px">
<video width="320" height="240" controls style="
    margin: 5px" >
  <source src="files/NJP_video.mp4" type="video/mp4">
  <source src="files/NJP_video.webm" type="video/webm">
  Your browser does not support the video tag.
</video><br/>
<i style="font-size:90%">Video abstact on the energetic efficiency of learning. Click to play!</i>
</div>

Every organism needs to gather information about its noisy environment and build
models from that data to support future decisions. Information processing,
however, comes at a thermodynamic cost. Stochastic thermodynamics is a powerful
framework to analyse this interplay between information processing and
dissipation in small, fluctuating systems far from equilibrium.

We analysed simple models of neural networks and showed that the total entropy
production of a network, i.e. its dissipation, bounds the information it can
infer from data or learn from a teacher. </p>


### References

- SG, U. Seifert<br/>
  _Thermodynamic efficiency of learning from a teacher_<br/>
  [New J. of Phys. *19* 113001](https://iopscience.iop.org/article/10.1088/1367-2630/aa89ff/meta) (2017) [arXiv:1706.09713](https://arxiv.org/abs/1706.09713)
- SG, U. Seifert<br/>
  _Stochastic Thermodynamics of Learning_<br/>
  [Phys. Rev. Lett. *118*,
  010601](https://arxiv.org/ct?url=https%3A%2F%2Fdx.doi.org%2F10.1103%2FPhysRevLett.118.010601&v=dada96ea)
  (2017) [arXiv:1611.09428](https://arxiv.org/abs/1611.09428)

