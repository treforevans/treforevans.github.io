<img align="left" style="width: 250px; height: auto; object-fit: contain" hspace="10" src="/imgs/trefor.jpg">
I am currently a PhD candidate at the University of Toronto conducting machine learning research on Bayesian methods for big data.
Much of my work has involved scaling Gaussian Processes, as well as discrete latent variable models, and deep latent variable models.
I am an inherently curious individual with a diverse range of interests and I like dabbling in new fields and applications.
If you are interested in collaborating on an application, please reach out to me! <br /> 
<br /> 
[<a href="files/TreforEvans-CV.pdf">CV</a>]
[<a href="https://scholar.google.ca/citations?user=oNL-h7UAAAAJ">Google Scholar</a>]
[<a href="https://github.com/treforevans">Github</a>]
<br clear="left" />

# Publications
###  Discretely Relaxing Continuous Variables for tractable Variational Inference
<img align="right" style="width: 220px; height: auto; object-fit: contain" hspace="10" src="imgs/direct.png">
Trefor W. Evans and Prasanth B. Nair.  <br /> 
<!--Neural Information Processing Systems-->
NIPS 2018 (Spotlight Paper) <br /> 
[<a href="https://arxiv.org/abs/1809.04279">Paper</a>]
[<a href="https://github.com/treforevans/direct">Code</a>]
[<a href="https://youtu.be/x0XzyEJY0ds">Video (3 min)</a>]

We explore a new research direction in variational inference with discrete latent variable priors.
The proposed "DIRECT" approach
can *exactly* compute ELBO gradients,
its training complexity is *independent* of the number of training points, and
its posterior samples consist of sparse and low-precision quantized integers.
Using latent variables discretized as extremely low-precision 4-bit quantized integers, we
demonstrate accurate inference on datasets with over two-million points where training takes just seconds.
<br clear="right" />

### Scalable Gaussian Processes with Grid-Structured Eigenfunctions (GP-GRIEF)
<img align="right" style="width: 200px; height: auto; object-fit: contain" hspace="10" src="imgs/gp-grief.png">
Trefor W. Evans and Prasanth B. Nair.  <br /> 
<!--International Conference on Machine Learning -->
ICML 2018 (Long Talk) <br /> 
[<a href="https://arxiv.org/abs/1807.02125">Paper</a>]
[<a href="https://github.com/treforevans/gp_grief">Code</a>]
[<a href="files/gp-grief_icml_slides.pdf">Slides</a>]
[<a href="files/gp-grief_icml_poster.pdf">Poster</a>]

We introduce a kernel approximation strategy that enables computation of the Gaussian Process log marginal likelihood and all hyperparameter derivatives in O(*p*) time,
where *p* is the rank of our approximation.
This fast likelihood evaluation enables type-I or II Bayesian inference on large-scale datasets.
We benchmark our algorithms on real-world problems with up to two-million training points and 10<sup>33</sup> inducing points!
<br clear="right" />

### Exploiting Structure for Fast Kernel Learning
<img align="right" style="width: 200px; height: auto; object-fit: contain" hspace="10" src="imgs/gappy.png">
Trefor W. Evans and Prasanth B. Nair.  <br /> 
SIAM International Conference on Data Mining (SDM), 2018.  <br /> 
[<a href="https://arxiv.org/abs/1808.03351">Paper</a>]
[<a href="https://github.com/treforevans/gp_grid">Code</a>]
[<a href="files/gappy_sdm_slides.pdf">Slides</a>]
[<a href="files/gappy_sdm_poster.pdf">Poster</a>]

We introduce two new approaches to perform exact Gaussian Process (GP) inference on massive image, video, spatial-temporal, or multi-output datasets 
with missing observations.
We demonstrate exact GP inference for a spatial-temporal climate modelling problem with 3.7 million training points as well as a video reconstruction problem with 1 billion points;
to the best of our knowledge exact GP inference has not been attempted before on this scale.
<br clear="right" />

### Undergraduate Thesis
<img align="right" style="width: 250px; height: auto; object-fit: contain" hspace="10" src="imgs/eta_ideal_cp.jpg">
Trefor W. Evans  <br /> 
University of Toronto, Engineering Science, 2014.  <br /> 
[<a href="files/undergrad_thesis.pdf">Thesis</a>]
[<a href="http://www.aerovelo.com/mission-log/2015/7/24/aerodynamic-design-of-eta">Blog Post</a>]

Developed a practical inverse aerodynamic shape optimization design process to achieve highly laminar flow bodies with an optimal pressure recovery.
Using this process, I designed Eta, a vehicle that I later built with AeroVelo, and which currently holds the world speed record at 144.17km/hr on a flat road!
Checkout
the [short video of our record-breaking run](https://www.youtube.com/watch?v=0JIB-rMGqCE), and
the [AeroVelo project page](http://www.aerovelo.com/our-projects/#eta-speedbike).
<br clear="right" />

# Teaching
I have been a teaching assistant in 12 engineering undergrad and graduate courses at the University of Toronto. 

**Coming soon ...**  <br /> 
During the winter 2019 term I will be co-instructing a new 3rd year Engineering Science course *ROB313 Learning from Data* alongside Prasanth B. Nair.

# Engineering
## D3ACE
<img align="right" style="width: 400px; height: auto; object-fit: contain" hspace="10" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Aircraft_Engine_%2840169504072%29.jpg/1024px-Aircraft_Engine_%2840169504072%29.jpg">
I am the lead developer for the library D3ACE which is currently being used in ongoing jet-engine development programs at Pratt & Whitney Canada.
D3ACE contains a suite of Bayesian machine learning models for design exploration and optimization.
<br clear="right" />

## Atlas Human-Powered Helicopter
<img align="right" style="width: 500px; height: auto; object-fit: contain" hspace="10" src="https://static1.squarespace.com/static/5500421ce4b028ce8ab9d39c/t/57ff9c4e37c581fd66484c4c/1476369509081/Atlas+RED+Comp_e.jpg?format=1500w">
Our team AeroVelo, a small group of 6 engineering students and graduates, developed the human-powered helicopter that won the Igor I. Sikorsky prize;
the third largest monetary prize in aviation history at 250,000 USD which stood unclaimed for 33 years.
I led the design, optimization and construction of the massive 20m x 20m x 4m helicopter structure which is currently on permanent display at the Ontario Science Center.
I was the lead test pilot for the aircraft and I hold the FAI world endurance record for human-powered helicopter flight.
Checkout 
the [short video of us winning the Sikorsky prize](https://www.youtube.com/watch?v=syJq10EQkog),
the [short video of my record-breaking endurance flight](https://www.youtube.com/watch?v=MfR85XTzeQc), as well as
our [project page](http://www.aerovelo.com/atlas-helicopter).
<br clear="right" />

## Eta Speedbike
<img align="right" style="width: 500px; height: auto; object-fit: contain" hspace="10" src="https://static1.squarespace.com/static/5500421ce4b028ce8ab9d39c/t/57fb17e1ff7c5085cbe52604/1476073665068/?format=1000w">
Developed a high-speed Human-Powered land vehicle that travelled at 144.17 km/hr on a flat road to break the world land-speed record.
For [my undergraduate thesis](files/undergrad_thesis.pdf), I developed a practical aerodynamic shape optimization process to design Eta's highly laminar flow body (see [my blog post](http://www.aerovelo.com/mission-log/2015/7/24/aerodynamic-design-of-eta)). 
I also conducted other extensive research projects including structural and aero-structural optimization to design the vehicle's frame and wheels, and was one of the vehicle's test pilots. 
Our small team of 3 to 6 people manufactured all components in-house.
Checkout
the [short video of our record-breaking run](https://www.youtube.com/watch?v=0JIB-rMGqCE), and
our [project page](http://www.aerovelo.com/our-projects/#eta-speedbike).
<br clear="right" />
