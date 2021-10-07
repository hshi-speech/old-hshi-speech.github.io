 I am a (haoshi)research scientist at <b>Facebook AI (FAIR)</b> in NYC and study foundational topics in <b>machine learning</b> and <b>optimization</b>, recently involving reinforcement learning, control, optimal transport, and geometry. I am interested in building learning systems that understand and interact with our world. I freely publish my research code to <a href="https://github.com/bamos" target="_blank">GitHub</a> as science should be open and reproducible and well-crafted software enables new frontiers. <br><br>


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td>
      <strong>Ph.D. in Computer Science</strong>, Carnegie Mellon University
        (0.00/0.00)
      <br>
        <p style='margin-top:-1em;margin-bottom:0em' markdown='1'>
        <br> *<a href="https://github.com/bamos/thesis" target="_blank">Differentiable Optimization-Based Modeling for Machine Learning</a>*
        <br> Advisors: <a href="http://zicokolter.com" target="_blank">J. Zico Kolter</a> (2016 - 2019),  <a href="https://www.cs.cmu.edu/~satya/" target="_blank">Mahadev Satyanarayanan</a> (2014 - 2016)
        </p>
    </td>
    <td class="col-md-2" style='text-align:right;'>2014 - 2019</td>
  </tr>
  <tr>
    <td>
      <strong>B.S. in Computer Science</strong>, Virginia Tech
        (3.99/4.00)
      <br>
    </td>
    <td class="col-md-2" style='text-align:right;'>2011 - 2014</td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Research Internships
<table class="table table-hover">
<tr>
  <td>
<p markdown="1" style='margin: 0'>
<strong>Intel Labs</strong>,
Santa Clara
(Host: <a href="http://vladlen.info/" target="_blank">Vladlen Koltun</a>)
</p>
  </td>
  <td class='col-md-2' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
<p markdown="1" style='margin: 0'>
<strong>Google DeepMind</strong>,
London
(Hosts: <a href="http://mdenil.com/" target="_blank">Misha Denil</a> and <a href="https://scholar.google.com/citations?user=nzEluBwAAAAJ" target="_blank">Nando de Freitas</a>)
</p>
  </td>
  <td class='col-md-2' style='text-align:right;'>2017</td>
</tr>
<tr>
  <td>
<p markdown="1" style='margin: 0'>
<strong>Adobe Research</strong>,
San Jose
(Host: <a href="https://research.adobe.com/person/david-tompkins/" target="_blank">David Tompkins</a>)
</p>
  </td>
  <td class='col-md-2' style='text-align:right;'>2014</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Honors & Awards
<table class="table table-hover">
<tr>
  <td>
    NSF Graduate Research Fellowship
  </td>
  <td class='col-md-2' style='text-align:right;'>2016 - 2019</td>
</tr>
<tr>
  <td>
    Nine undergraduate scholarships
    <br><p style="color:grey;font-size:1.2rem">Roanoke County Public Schools Engineering,
Salem-Roanoke County Chamber of Commerce,
Papa John's,
Scottish Rite of Freemasonry,
VT Intelligence Community Conter for Academic Excellence,
VT Pamplin Leader,
VT Benjamin F. Bock, VT Gay B. Shober, VT I. Luck Gravett
</p>
  </td>
  <td class='col-md-2' style='text-align:right;'>2011 - 2014</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Publications

Representative publications that I am a primary author on are
<span style='background-color: #ffffd0'>highlighted.</span><br>
[<a href="https://scholar.google.com/citations?user=d8gdZR4AAAAJ">Google Scholar</a>]
[<a href="https://github.com/bamos/cv/blob/master/publications/all.bib">BibTeX</a>]

<h2>2021</h2>
<table class="table table-hover">

<tr id="tr-amos2021modelbased" style="background-color: #ffffd0">
<td>
    <em><a href='https://arxiv.org/abs/2008.12775' target='_blank'>On the model-based stochastic value gradient for continuous reinforcement learning</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://samuelstanton.github.io/' target='_blank'>Samuel&nbsp;Stanton</a>, <a href='https://cs.nyu.edu/~dy1042/' target='_blank'>Denis&nbsp;Yarats</a>, and <a href='https://people.orie.cornell.edu/andrew/' target='_blank'>Andrew&nbsp;Gordon&nbsp;Wilson</a><br>
    L4DC 2021 (Oral) <br>
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_amos2021modelbased").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/svg' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2021.svg.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_amos2021modelbased" style="text-align: justify; display: none" markdown="1">
Model-based reinforcement learning approaches add explicit domain
knowledge to agents in hopes of improving the
sample-efficiency in comparison to model-free
agents. However, in practice model-based methods are
unable to achieve the same asymptotic performance on
challenging continuous control tasks due to the
complexity of learning and controlling an explicit
world model. In this paper we investigate the
stochastic value gradient (SVG), which is a
well-known family of methods for controlling
continuous systems which includes model-based
approaches that distill a model-based value
expansion into a model-free policy. We consider a
variant of the model-based SVG that scales to larger
systems and uses 1) an entropy regularization to
help with exploration, 2) a learned deterministic
world model to improve the short-horizon value
estimate, and 3) a learned model-free value estimate
after the model's rollout. This SVG variation
captures the model-free soft actor-critic method as
an instance when the model rollout horizon is zero, and otherwise uses short-horizon model rollouts to
improve the value estimate for the policy update. We
surpass the asymptotic performance of other
model-based methods on the proprioceptive MuJoCo
locomotion tasks from the OpenAI gym, including a
humanoid. We notably achieve these results with a
simple deterministic world model without requiring
an ensemble.
</div>

</td>
</tr>


<tr id="tr-cohen2021riemannian" style="background-color: #ffffd0">
<td>
    <em><a href='https://arxiv.org/abs/2106.10272' target='_blank'>Riemannian Convex Potential Maps</a> </em><br>
    <a href='https://scholar.google.com/citations?user=CmdjfTsAAAAJ' target='_blank'>Samuel&nbsp;Cohen*</a>, <strong>Brandon&nbsp;Amos*</strong>, and <a href='https://www.wisdom.weizmann.ac.il/~ylipman/' target='_blank'>Yaron&nbsp;Lipman</a><br>
    ICML 2021  <br>
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_cohen2021riemannian").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/rcpm' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2021.rcpm.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_cohen2021riemannian" style="text-align: justify; display: none" markdown="1">
Modeling distributions on Riemannian manifolds is a crucial
component in understanding non-Euclidean data that
arises, e.g., in physics and geology. The budding
approaches in this space are limited by
representational and computational tradeoffs. We
propose and study a class of flows that uses convex
potentials from Riemannian optimal transport. These
are universal and can model distributions on any
compact Riemannian manifold without requiring domain
knowledge of the manifold to be integrated into the
architecture. We demonstrate that these flows can
model standard distributions on spheres, and tori, on synthetic and geological data.
</div>

</td>
</tr>


<tr id="tr-paulus2021comboptnet" >
<td>
    <em><a href='https://arxiv.org/abs/2105.02343' target='_blank'>CombOptNet: Fit the Right NP-Hard Problem by Learning Integer Programming Constraints</a> </em><br>
    <a href='https://scholar.google.com/citations?user=njZL5CQAAAAJ' target='_blank'>Anselm&nbsp;Paulus</a>, <a href='https://mrolinek.github.io/' target='_blank'>Michal&nbsp;Rol&iacute;nek</a>, <a href='https://scholar.google.com/citations?user=hA1rlU4AAAAJ' target='_blank'>V&iacute;t&nbsp;Musil</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='http://georg.playfulmachines.com/' target='_blank'>Georg&nbsp;Martius</a><br>
    ICML 2021  <br>
    [3] 
[<a href='javascript:;'
    onclick='$("#abs_paulus2021comboptnet").toggle()'>abs</a>] [<a href='https://github.com/martius-lab/CombOptNet' target='_blank'>code</a>] <br>
    
<div id="abs_paulus2021comboptnet" style="text-align: justify; display: none" markdown="1">
Bridging logical and algorithmic reasoning with modern machine
learning techniques is a fundamental challenge with
potentially transformative impact. On the
algorithmic side, many NP-hard problems can be
expressed as integer programs, in which the
constraints play the role of their "combinatorial
specification". In this work, we aim to integrate
integer programming solvers into neural network
architectures as layers capable of learning both the
cost terms and the constraints. The resulting
end-to-end trainable architectures jointly extract
features from raw data and solve a suitable
(learned) combinatorial problem with
state-of-the-art integer programming solvers. We
demonstrate the potential of such layers with an
extensive performance analysis on synthetic data and
with a demonstration on a competitive computer
vision keypoint matching benchmark.
</div>

</td>
</tr>


<tr id="tr-fickinger2021scalable" >
<td>
    <em><a href='https://arxiv.org/abs/2109.15316' target='_blank'>Scalable Online Planning via Reinforcement Learning Fine-Tuning</a> </em><br>
    <a href='https://scholar.google.com/citations?user=bBFN_qwAAAAJ' target='_blank'>Arnaud&nbsp;Fickinger</a>, <a href='https://scholar.google.com/citations?user=sJwwn54AAAAJ' target='_blank'>Hengyuan&nbsp;Hu</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='http://people.eecs.berkeley.edu/~russell/' target='_blank'>Stuart&nbsp;Russell</a>, and <a href='http://www.noambrown.com/' target='_blank'>Noam&nbsp;Brown</a><br>
    NeurIPS 2021  <br>
    [4] 
[<a href='javascript:;'
    onclick='$("#abs_fickinger2021scalable").toggle()'>abs</a>]<br>
    
<div id="abs_fickinger2021scalable" style="text-align: justify; display: none" markdown="1">
Lookahead search has been a critical component of recent AI successes, such as in the games of chess, go, and
poker. However, the search methods used in these
games, and in many other settings, are
tabular. Tabular search methods do not scale well
with the size of the search space, and this problem
is exacerbated by stochasticity and partial
observability. In this work we replace tabular
search with online model-based fine-tuning of a
policy neural network via reinforcement learning, and show that this approach outperforms
state-of-the-art search algorithms in benchmark
settings. In particular, we use our search algorithm
to achieve a new state-of-the-art result in
self-play Hanabi, and show the generality of our
algorithm by also showing that it outperforms
tabular search in the Atari game Ms. Pacman.
</div>

</td>
</tr>


<tr id="tr-cohen2020aligning" >
<td>
    <em><a href='https://arxiv.org/abs/2006.12648' target='_blank'>Aligning Time Series on Incomparable Spaces</a> </em><br>
    <a href='https://scholar.google.com/citations?user=CmdjfTsAAAAJ' target='_blank'>Samuel&nbsp;Cohen</a>, <a href='https://giulslu.github.io/' target='_blank'>Giulia&nbsp;Luise</a>, <a href='https://avt.im/' target='_blank'>Alexander&nbsp;Terenin</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='https://deisenroth.cc/' target='_blank'>Marc&nbsp;Peter&nbsp;Deisenroth</a><br>
    AISTATS 2021  <br>
    [5] 
[<a href='javascript:;'
    onclick='$("#abs_cohen2020aligning").toggle()'>abs</a>] [<a href='https://github.com/samcohen16/Aligning-Time-Series' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2021.gdtw.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_cohen2020aligning" style="text-align: justify; display: none" markdown="1">
Dynamic time warping (DTW) is a useful method for aligning, comparing
and combining time series, but it requires them to
live in comparable spaces. In this work, we consider
a setting in which time series live on different
spaces without a sensible ground metric, causing DTW
to become ill-defined. To alleviate this, we propose
Gromov dynamic time warping (GDTW), a distance
between time series on potentially incomparable
spaces that avoids the comparability requirement by
instead considering intra-relational geometry. We
derive a Frank-Wolfe algorithm for computing it and
demonstrate its effectiveness at aligning, combining
and comparing time series living on incomparable
spaces. We further propose a smoothed version of
GDTW as a differentiable loss and assess its
properties in a variety of settings, including
barycentric averaging, generative modeling and
imitation learning.
</div>

</td>
</tr>


<tr id="tr-chen2021learning" >
<td>
    <em><a href='https://arxiv.org/abs/2011.03902' target='_blank'>Learning Neural Event Functions for Ordinary Differential Equations</a> </em><br>
    <a href='https://scholar.google.com/citations?user=7MxQd6UAAAAJ' target='_blank'>Ricky&nbsp;T.&nbsp;Q.&nbsp;Chen</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='https://mnick.github.io/' target='_blank'>Maximilian&nbsp;Nickel</a><br>
    ICLR 2021  <br>
    [6] 
[<a href='javascript:;'
    onclick='$("#abs_chen2021learning").toggle()'>abs</a>] [<a href='https://github.com/rtqichen/torchdiffeq' target='_blank'>code</a>] <br>
    
<div id="abs_chen2021learning" style="text-align: justify; display: none" markdown="1">
The existing Neural ODE formulation relies on an explicit
knowledge of the termination time. We extend Neural
ODEs to implicitly defined termination criteria
modeled by neural event functions, which can be
chained together and differentiated through. Neural
Event ODEs are capable of modeling discrete
(instantaneous) changes in a continuous-time system, without prior knowledge of when these changes should
occur or how many such changes should exist. We test
our approach in modeling hybrid discrete- and
continuous- systems such as switching dynamical
systems and collision in multi-body systems, and we
propose simulation-based training of point processes
with applications in discrete control.
</div>

</td>
</tr>


<tr id="tr-chen2021neural" >
<td>
    <em><a href='https://arxiv.org/abs/2011.04583' target='_blank'>Neural Spatio-Temporal Point Processes</a> </em><br>
    <a href='https://scholar.google.com/citations?user=7MxQd6UAAAAJ' target='_blank'>Ricky&nbsp;T.&nbsp;Q.&nbsp;Chen</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='https://mnick.github.io/' target='_blank'>Maximilian&nbsp;Nickel</a><br>
    ICLR 2021  <br>
    [7] 
[<a href='javascript:;'
    onclick='$("#abs_chen2021neural").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/neural_stpp' target='_blank'>code</a>] <br>
    
<div id="abs_chen2021neural" style="text-align: justify; display: none" markdown="1">
We propose a new class of parameterizations for spatio-temporal
point processes which leverage Neural ODEs as a
computational method and enable flexible, high-fidelity models of discrete events that are
localized in continuous time and space. Central to
our approach is a combination of recurrent
continuous-time neural networks with two novel
neural architectures, i.e., Jump and Attentive
Continuous-time Normalizing Flows. This approach
allows us to learn complex distributions for both
the spatial and temporal domain and to condition
non-trivially on the observed event history. We
validate our models on data sets from a wide variety
of contexts such as seismology, epidemiology, urban
mobility, and neuroscience.
</div>

</td>
</tr>


<tr id="tr-yarats2021improving" >
<td>
    <em><a href='https://arxiv.org/abs/1910.01741' target='_blank'>Improving Sample Efficiency in Model-Free Reinforcement Learning from Images</a> </em><br>
    <a href='https://cs.nyu.edu/~dy1042/' target='_blank'>Denis&nbsp;Yarats</a>, <a href='https://amyzhang.github.io/' target='_blank'>Amy&nbsp;Zhang</a>, <a href='https://scholar.google.com/citations?user=PTS2AOgAAAAJ' target='_blank'>Ilya&nbsp;Kostrikov</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://www.cs.mcgill.ca/~jpineau/' target='_blank'>Joelle&nbsp;Pineau</a>, and <a href='https://cs.nyu.edu/~fergus/pmwiki/pmwiki.php' target='_blank'>Rob&nbsp;Fergus</a><br>
    AAAI 2021  <br>
    [8] 
[<a href='javascript:;'
    onclick='$("#abs_yarats2021improving").toggle()'>abs</a>] [<a href='https://sites.google.com/view/sac-ae' target='_blank'>code</a>] <br>
    
<div id="abs_yarats2021improving" style="text-align: justify; display: none" markdown="1">
Training an agent to solve control tasks directly from
high-dimensional images with model-free
reinforcement learning (RL) has proven
difficult. The agent needs to learn a latent
representation together with a control policy to
perform the task. Fitting a high-capacity encoder
using a scarce reward signal is not only sample
inefficient, but also prone to suboptimal
convergence. Two ways to improve sample efficiency
are to extract relevant features for the task and
use off-policy algorithms. We dissect various
approaches of learning good latent features, and
conclude that the image reconstruction loss is the
essential ingredient that enables efficient and
stable representation learning in image-based
RL. Following these findings, we devise an
off-policy actor-critic algorithm with an auxiliary
decoder that trains end-to-end and matches
state-of-the-art performance across both model-free
and model-based algorithms on many challenging
control tasks. We release our code to encourage
future research on image-based RL.
</div>

</td>
</tr>


<tr id="tr-venkataraman2021neural" >
<td>
    <em><a href='https://arxiv.org/abs/2107.10254' target='_blank'>Neural Fixed-Point Acceleration for Convex Optimization</a> </em><br>
    <a href='https://scholar.google.com/citations?user=BFWurDEAAAAJ' target='_blank'>Shobha&nbsp;Venkataraman*</a> and <strong>Brandon&nbsp;Amos*</strong><br>
    ICML AutoML 2021  <br>
    [9] 
[<a href='javascript:;'
    onclick='$("#abs_venkataraman2021neural").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/neural-opt' target='_blank'>code</a>] <br>
    
<div id="abs_venkataraman2021neural" style="text-align: justify; display: none" markdown="1">
Fixed-point iterations are at the heart of numerical computing and
are often a computational bottleneck in real-time
applications that typically need a fast solution of
moderate accuracy. We present neural fixed-point
acceleration which combines ideas from meta-learning
and classical acceleration methods to automatically
learn to accelerate fixed-point problems that are
drawn from a distribution. We apply our framework to
SCS, the state-of-the-art solver for convex cone
programming, and design models and loss functions to
overcome the challenges of learning over unrolled
optimization and acceleration instabilities. Our
work brings neural acceleration into any
optimization problem expressible with CVXPY.
</div>

</td>
</tr>


<tr id="tr-pineda2021mbrl" >
<td>
    <em><a href='https://arxiv.org/abs/2104.10159' target='_blank'>MBRL-Lib: A Modular Library for Model-based Reinforcement Learning</a> </em><br>
    <a href='https://scholar.google.com/citations?user=rebEn8oAAAAJ' target='_blank'>Luis&nbsp;Pineda</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://amyzhang.github.io/' target='_blank'>Amy&nbsp;Zhang</a>, <a href='https://www.natolambert.com/' target='_blank'>Nathan&nbsp;Lambert</a>, and <a href='https://www.robertocalandra.com/about/' target='_blank'>Roberto&nbsp;Calandra</a><br>
    arXiv 2021  <br>
    [10] 
[<a href='javascript:;'
    onclick='$("#abs_pineda2021mbrl").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/mbrl-lib' target='_blank'>code</a>] <br>
    
<div id="abs_pineda2021mbrl" style="text-align: justify; display: none" markdown="1">
Model-based reinforcement learning is a compelling framework for
data-efficient learning of agents that interact with
the world. This family of algorithms has many
subcomponents that need to be carefully selected and
tuned. As a result the entry-bar for researchers to
approach the field and to deploy it in real-world
tasks can be daunting. In this paper, we present
MBRL-Lib - a machine learning library for
model-based reinforcement learning in continuous
state-action spaces based on PyTorch. MBRL-Lib is
designed as a platform for both researchers, to
easily develop, debug and compare new algorithms, and non-expert user, to lower the entry-bar of
deploying state-of-the-art algorithms.
</div>

</td>
</tr>

</table>
<h2>2020</h2>
<table class="table table-hover">

<tr id="tr-amos2020differentiable" style="background-color: #ffffd0">
<td>
    <em><a href='https://arxiv.org/abs/1909.12830' target='_blank'>The Differentiable Cross-Entropy Method</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong> and <a href='https://cs.nyu.edu/~dy1042/' target='_blank'>Denis&nbsp;Yarats</a><br>
    ICML 2020  <br>
    [11] 
[<a href='javascript:;'
    onclick='$("#abs_amos2020differentiable").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/dcem' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2020.dcem.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_amos2020differentiable" style="text-align: justify; display: none" markdown="1">
We study the Cross-Entropy Method (CEM) for the non-convex
optimization of a continuous and parameterized
objective function and introduce a differentiable
variant (DCEM) that enables us to differentiate the
output of CEM with respect to the objective
function's parameters. In the machine learning
setting this brings CEM inside of the end-to-end
learning pipeline where this has otherwise been
impossible. We show applications in a synthetic
energy-based structured prediction task and in
non-convex continuous control. In the control
setting we show on the simulated cheetah and walker
tasks that we can embed their optimal action
sequences with DCEM and then use policy optimization
to fine-tune components of the controller as a step
towards combining model-based and model-free RL.
</div>

</td>
</tr>


<tr id="tr-lambert2020objective" >
<td>
    <em><a href='https://arxiv.org/abs/2002.04523' target='_blank'>Objective Mismatch in Model-based Reinforcement Learning</a> </em><br>
    <a href='https://www.natolambert.com/' target='_blank'>Nathan&nbsp;Lambert</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=zSsW478AAAAJ' target='_blank'>Omry&nbsp;Yadan</a>, and <a href='https://www.robertocalandra.com/about/' target='_blank'>Roberto&nbsp;Calandra</a><br>
    L4DC 2020  <br>
    [12] 
[<a href='javascript:;'
    onclick='$("#abs_lambert2020objective").toggle()'>abs</a>]<br>
    
<div id="abs_lambert2020objective" style="text-align: justify; display: none" markdown="1">
Model-based reinforcement learning (MBRL) has been shown to be a powerful framework for data-efficiently learning control of continuous tasks. Recent work in MBRL has mostly focused on using more advanced function approximators and planning schemes, with little development of the general framework. In this paper, we identify a fundamental issue of the standard MBRL framework-what we call the objective mismatch issue. Objective mismatch arises when one objective is optimized in the hope that a second, often uncorrelated, metric will also be optimized. In the context of MBRL, we characterize the objective mismatch between training the forward dynamics model wrt the likelihood of the one-step ahead prediction, and the overall goal of improving performance on a downstream control task. For example, this issue can emerge with the realization that dynamics models effective for a specific task do not necessarily need to be globally accurate, and vice versa globally accurate models might not be sufficiently accurate locally to obtain good control performance on a specific task. In our experiments, we study this objective mismatch issue and demonstrate that the likelihood of one-step ahead predictions is not always correlated with control performance. This observation highlights a critical limitation in the MBRL framework which will require further research to be fully understood and addressed. We propose an initial method to mitigate the mismatch issue by re-weighting dynamics model training. Building on it, we conclude with a discussion about other potential directions of research for addressing this issue.
</div>

</td>
</tr>


<tr id="tr-amos2020QNSTOP" >
<td>
    <em><a href='https://vtechworks.lib.vt.edu/bitstream/handle/10919/49672/qnTOMS14.pdf' target='_blank'>QNSTOP: Quasi-Newton Algorithm for Stochastic Optimization</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://dblp.org/pid/75/8682.html' target='_blank'>David&nbsp;Easterling</a>, <a href='https://people.cs.vt.edu/~ltw/shortvita.html' target='_blank'>Layne&nbsp;T.&nbsp;Watson</a>, <a href='https://scholar.google.com/citations?user=2I6IgikAAAAJ' target='_blank'>William&nbsp;Thacker</a>, <a href='https://dblp.org/pid/142/1258.html' target='_blank'>Brent&nbsp;Castle</a>, and <a href='https://mtrosset.pages.iu.edu/' target='_blank'>Michael&nbsp;Trosset</a><br>
    ACM TOMS 2020  <br>
    [13] 
[<a href='javascript:;'
    onclick='$("#abs_amos2020QNSTOP").toggle()'>abs</a>] [<a href='https://github.com/vtopt/qnstop' target='_blank'>code</a>] <br>
    
<div id="abs_amos2020QNSTOP" style="text-align: justify; display: none" markdown="1">
QNSTOP consists of serial and parallel (OpenMP) Fortran 2003 codes for the
quasi-Newton stochastic optimization method of Castle and Trosset. For
stochastic problems, convergence theory exists for the particular
algorithmic choices and parameter values used in QNSTOP. Both the parallel
driver subroutine, which offers several parallel decomposition strategies, and the serial driver subroutine can be used for stochastic optimization or
deterministic global optimization, based on an input switch. QNSTOP is
particularly effective for “noisy” deterministic problems, using only
objective function values. Some performance data for computational systems
biology problems is given.
</div>

</td>
</tr>


<tr id="tr-sercu2020neural" >
<td>
    <em><a href='https://www.biorxiv.org/content/10.1101/2021.04.08.439084v1.abstract' target='_blank'>Neural Potts Model</a> </em><br>
    <a href='https://tom.sercu.me/' target='_blank'>Tom&nbsp;Sercu</a>, <a href='https://dblp.org/pid/296/8930.html' target='_blank'>Robert&nbsp;Verkuil</a>, <a href='https://scholar.google.com/citations?user=2M0OltAAAAAJ' target='_blank'>Joshua&nbsp;Meier</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=ZDjmMuwAAAAJ' target='_blank'>Zeming&nbsp;Lin</a>, <a href='https://www.linkedin.com/in/caroline-chen/' target='_blank'>Caroline&nbsp;Chen</a>, <a href='https://www.linkedin.com/in/jasonliu6/' target='_blank'>Jason&nbsp;Liu</a>, <a href='http://yann.lecun.com/' target='_blank'>Yann&nbsp;LeCun</a>, and <a href='https://scholar.google.com/citations?user=vqb78-gAAAAJ' target='_blank'>Alexander&nbsp;Rives</a><br>
    MLCB 2020  <br>
    [14] 
[<a href='javascript:;'
    onclick='$("#abs_sercu2020neural").toggle()'>abs</a>]<br>
    
<div id="abs_sercu2020neural" style="text-align: justify; display: none" markdown="1">
We propose the Neural Potts Model objective as an amortized
optimization problem. The objective enables training
a single model with shared parameters to explicitly
model energy landscapes across multiple protein
families. Given a protein sequence as input, the
model is trained to predict a pairwise coupling
matrix for a Potts model energy function describing
the local evolutionary landscape of the
sequence. Couplings can be predicted for novel
sequences. A controlled ablation experiment
assessing unsupervised contact prediction on sets of
related protein families finds a gain from
amortization for low-depth multiple sequence
alignments; the result is then confirmed on a
database with broad coverage of protein sequences.
</div>

</td>
</tr>


<tr id="tr-lou2020riemannian" >
<td>
    <em><a href='https://drive.google.com/file/d/1Ewro0Ne1tvK15nHyYopY4wZ59QTVB-1c/view' target='_blank'>Deep Riemannian Manifold Learning</a> </em><br>
    <a href='https://www.aaronlou.com/' target='_blank'>Aaron&nbsp;Lou</a>, <a href='https://mnick.github.io/' target='_blank'>Maximilian&nbsp;Nickel</a>, and <strong>Brandon&nbsp;Amos</strong><br>
    NeurIPS Geo4dl 2020  <br>
    [15] 
[<a href='javascript:;'
    onclick='$("#abs_lou2020riemannian").toggle()'>abs</a>]<br>
    
<div id="abs_lou2020riemannian" style="text-align: justify; display: none" markdown="1">
We present a new class of learnable Riemannian manifolds with a metric
parameterized by a deep neural network. The core manifold operations–specifically
the Riemannian exponential and logarithmic maps–are solved using approximate
numerical techniques. Input and parameter gradients are computed with an
adjoint sensitivity analysis. This enables us to fit geodesics and distances with
gradient-based optimization of both on-manifold values and the manifold itself.
We demonstrate our method’s capability to model smooth, flexible metric structures
in graph embedding tasks.
</div>

</td>
</tr>

</table>
<h2>2019</h2>
<table class="table table-hover">

<tr id="tr-amos2019differentiable" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/bamos/thesis/raw/master/bamos_thesis.pdf' target='_blank'>Differentiable Optimization-Based Modeling for Machine Learning</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong><br>
    Ph.D. Thesis 2019  <br>
    [16] 
[<a href='javascript:;'
    onclick='$("#abs_amos2019differentiable").toggle()'>abs</a>] [<a href='https://github.com/bamos/thesis' target='_blank'>code</a>] <br>
    
<div id="abs_amos2019differentiable" style="text-align: justify; display: none" markdown="1">
Domain-specific modeling priors and specialized components are becoming
increasingly important to the machine learning field. These components integrate specialized knowledge that we have as humans into model. We argue in
this thesis that optimization methods provide an expressive set of operations
that should be part of the machine learning practitioner’s modeling toolbox.
We present two foundational approaches for optimization-based modeling:
1) the OptNet architecture that integrates optimization problems as individual
layers in larger end-to-end trainable deep networks, and 2) the input-convex
neural network (ICNN) architecture that helps make inference and learning in
deep energy-based models and structured prediction more tractable.
We then show how to use the OptNet approach 1) as a way of combining
model-free and model-based reinforcement learning and 2) for top-k learning
problems. We conclude by showing how to differentiate cone programs and turn
the cvxpy domain specific language into a differentiable optimization layer that
enables rapid prototyping of the approaches in this thesis.
</div>

</td>
</tr>


<tr id="tr-amos2019differentiable3" style="background-color: #ffffd0">
<td>
    <em><a href='http://web.stanford.edu/~boyd/papers/pdf/diff_cvxpy.pdf' target='_blank'>Differentiable Convex Optimization Layers</a> </em><br>
    <a href='https://www.akshayagrawal.com/' target='_blank'>Akshay&nbsp;Agrawal*</a>, <strong>Brandon&nbsp;Amos*</strong>, <a href='https://web.stanford.edu/~sbarratt/' target='_blank'>Shane&nbsp;Barratt*</a>, <a href='https://web.stanford.edu/~boyd/' target='_blank'>Stephen&nbsp;Boyd*</a>, <a href='https://stevendiamond.me/' target='_blank'>Steven&nbsp;Diamond*</a>, and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter*</a><br>
    NeurIPS 2019  <br>
    [17] 
[<a href='javascript:;'
    onclick='$("#abs_amos2019differentiable3").toggle()'>abs</a>] [<a href='https://github.com/cvxgrp/cvxpylayers' target='_blank'>code</a>] <br>
    
<div id="abs_amos2019differentiable3" style="text-align: justify; display: none" markdown="1">
Recent work has shown how to embed differentiable optimization problems (that is, problems whose solutions can be backpropagated through) as layers within deep learning architectures. This method provides a useful inductive bias for certain problems, but existing software for differentiable optimization layers is rigid and difficult to apply to new settings. In this paper, we propose an approach to differentiating through disciplined convex programs, a subclass of convex optimization problems used by domain-specific languages (DSLs) for convex optimization. We introduce disciplined parametrized programming, a subset of disciplined convex programming, and we show that every disciplined parametrized program can be represented as the composition of an affine map from parameters to problem data, a solver, and an affine map from the solver’s solution to a solution of the original problem (a new form we refer to as affine-solver-affine form). We then demonstrate how to efficiently differentiate through each of these components, allowing for end-to-end analytical differentiation through the entire convex program. We implement our methodology in version 1.1 of CVXPY, a popular Python-embedded DSL for convex optimization, and additionally implement differentiable layers for disciplined convex programs in PyTorch and TensorFlow 2.0. Our implementation significantly lowers the barrier to using convex optimization problems in differentiable programs. We present applications in linear machine learning models and in stochastic control, and we show that our layer is competitive (in execution time) compared to specialized differentiable solvers from past work.
</div>

</td>
</tr>


<tr id="tr-amos2019limited" >
<td>
    <em><a href='https://arxiv.org/abs/1906.08707' target='_blank'>The Limited Multi-Label Projection Layer</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='http://vladlen.info/' target='_blank'>Vladlen&nbsp;Koltun</a>, and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter</a><br>
    arXiv 2019  <br>
    [18] 
[<a href='javascript:;'
    onclick='$("#abs_amos2019limited").toggle()'>abs</a>] [<a href='https://github.com/locuslab/lml' target='_blank'>code</a>] <br>
    
<div id="abs_amos2019limited" style="text-align: justify; display: none" markdown="1">
We propose the Limited Multi-Label (LML) projection layer as a new
primitive operation for end-to-end learning systems. The LML layer
provides a probabilistic way of modeling multi-label predictions
limited to having exactly k labels. We derive efficient forward and
backward passes for this layer and show how the layer can be used to
optimize the top-k recall for multi-label tasks with incomplete label
information. We evaluate LML layers on top-k CIFAR-100 classification
and scene graph generation. We show that LML layers add a negligible
amount of computational overhead, strictly improve the model's
representational capacity, and improve accuracy. We also revisit the
truncated top-k entropy method as a competitive baseline for top-k
classification.
</div>

</td>
</tr>


<tr id="tr-grefenstette2019generalized" >
<td>
    <em><a href='https://arxiv.org/abs/1910.01727' target='_blank'>Generalized Inner Loop Meta-Learning</a> </em><br>
    <a href='https://www.egrefen.com/' target='_blank'>Edward&nbsp;Grefenstette</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://cs.nyu.edu/~dy1042/' target='_blank'>Denis&nbsp;Yarats</a>, <a href='https://phumonhtut.me/' target='_blank'>Phu&nbsp;Mon&nbsp;Htut</a>, <a href='https://amolchanov86.github.io/' target='_blank'>Artem&nbsp;Molchanov</a>, <a href='https://fmeier.github.io/' target='_blank'>Franziska&nbsp;Meier</a>, <a href='https://douwekiela.github.io/' target='_blank'>Douwe&nbsp;Kiela</a>, <a href='https://kyunghyuncho.me/' target='_blank'>Kyunghyun&nbsp;Cho</a>, and <a href='https://soumith.ch/' target='_blank'>Soumith&nbsp;Chintala</a><br>
    arXiv 2019  <br>
    [19] 
[<a href='javascript:;'
    onclick='$("#abs_grefenstette2019generalized").toggle()'>abs</a>] [<a href='https://github.com/facebookresearch/higher' target='_blank'>code</a>] <br>
    
<div id="abs_grefenstette2019generalized" style="text-align: justify; display: none" markdown="1">
Many (but not all) approaches self-qualifying as "meta-learning" in
deep learning and reinforcement learning fit a
common pattern of approximating the solution to a
nested optimization problem. In this paper, we give
a formalization of this shared pattern, which we
call GIMLI, prove its general requirements, and
derive a general-purpose algorithm for implementing
similar approaches. Based on this analysis and
algorithm, we describe a library of our design, higher, which we share with the community to assist
and enable future research into these kinds of
meta-learning approaches. We end the paper by
showcasing the practical applications of this
framework and library through illustrative
experiments and ablation studies which they
facilitate.
</div>

</td>
</tr>

</table>
<h2>2018</h2>
<table class="table table-hover">

<tr id="tr-amos2018learning" style="background-color: #ffffd0">
<td>
    <em><a href='https://openreview.net/forum?id=r1HhRfWRZ' target='_blank'>Learning Awareness Models</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://laurent-dinh.github.io/' target='_blank'>Laurent&nbsp;Dinh</a>, <a href='https://scholar.google.com/citations?user=l-HhJaUAAAAJ' target='_blank'>Serkan&nbsp;Cabi</a>, <a href='https://dblp.org/pid/188/6045.html' target='_blank'>Thomas&nbsp;Roth&ouml;rl</a>, <a href='https://scholar.google.com/citations?user=0Dkf68EAAAAJ' target='_blank'>Sergio&nbsp;G&oacute;mez&nbsp;Colmenarejo</a>, <a href='https://scholar.google.com/citations?user=YfgdfyYAAAAJ' target='_blank'>Alistair&nbsp;Muldal</a>, <a href='https://scholar.google.com/citations?user=gVFnjOcAAAAJ' target='_blank'>Tom&nbsp;Erez</a>, <a href='https://scholar.google.com/citations?user=CjOTm_4AAAAJ' target='_blank'>Yuval&nbsp;Tassa</a>, <a href='https://scholar.google.com/citations?user=nzEluBwAAAAJ' target='_blank'>Nando&nbsp;de&nbsp;Freitas</a>, and <a href='https://mdenil.com/' target='_blank'>Misha&nbsp;Denil</a><br>
    ICLR 2018  <br>
    [20] 
[<a href='javascript:;'
    onclick='$("#abs_amos2018learning").toggle()'>abs</a>]<br>
    
<div id="abs_amos2018learning" style="text-align: justify; display: none" markdown="1">
We consider the setting of an agent with a fixed body interacting with an
unknown and uncertain external world. We show that models
trained to predict proprioceptive information about the
agent's body come to represent objects in the external world.
In spite of being trained with only internally available
signals, these dynamic body models come to represent external
objects through the necessity of predicting their effects on
the agent's own body. That is, the model learns holistic
persistent representations of objects in the world, even
though the only training signals are body signals. Our
dynamics model is able to successfully predict distributions
over 132 sensor readings over 100 steps into the future and we
demonstrate that even when the body is no longer in contact
with an object, the latent variables of the dynamics model
continue to represent its shape. We show that active data
collection by maximizing the entropy of predictions about the
body-touch sensors, proprioception and vestibular
information-leads to learning of dynamic models that show
superior performance when used for control. We also collect
data from a real robotic hand and show that the same models
can be used to answer questions about properties of objects in
the real world. Videos with qualitative results of our models
are available <a href="https://goo.gl/mZuqAV">here</a>.
</div>

</td>
</tr>


<tr id="tr-amos2018end" style="background-color: #ffffd0">
<td>
    <em><a href='https://arxiv.org/abs/1810.13400' target='_blank'>Differentiable MPC for End-to-end Planning and Control</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://ivandariojr.io/' target='_blank'>Ivan&nbsp;Dario&nbsp;Jimenez&nbsp;Rodriguez</a>, <a href='https://scholar.google.com/citations?user=Th4PuGkAAAAJ' target='_blank'>Jacob&nbsp;Sacks</a>, <a href='https://homes.cs.washington.edu/~bboots/' target='_blank'>Byron&nbsp;Boots</a>, and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter</a><br>
    NeurIPS 2018  <br>
    [21] 
[<a href='javascript:;'
    onclick='$("#abs_amos2018end").toggle()'>abs</a>] [<a href='https://locuslab.github.io/mpc.pytorch/' target='_blank'>code</a>] <br>
    
<div id="abs_amos2018end" style="text-align: justify; display: none" markdown="1">
In this paper we present foundations for using model predictive control (MPC) as a differentiable policy class in reinforcement learning. Specifically, we differentiate through MPC by using the KKT conditions of the convex approximation at a fixed point of the solver. Using this strategy, we are able to learn the cost and dynamics of a controller via end-to-end learning in a larger system. We empirically show results in an imitation learning setting, demonstrating that we can recover the underlying dynamics and cost more efficiently and reliably than with a generic neural network policy class
</div>

</td>
</tr>


<tr id="tr-brown2018depth" >
<td>
    <em><a href='http://arxiv.org/abs/1805.08195' target='_blank'>Depth-Limited Solving for Imperfect-Information Games</a> </em><br>
    <a href='http://www.noambrown.com/' target='_blank'>Noam&nbsp;Brown</a>, <a href='http://www.cs.cmu.edu/~sandholm/' target='_blank'>Tuomas&nbsp;Sandholm</a>, and <strong>Brandon&nbsp;Amos</strong><br>
    NeurIPS 2018  <br>
    [22] 
[<a href='javascript:;'
    onclick='$("#abs_brown2018depth").toggle()'>abs</a>]<br>
    
<div id="abs_brown2018depth" style="text-align: justify; display: none" markdown="1">
A fundamental challenge in imperfect-information games is that states do not have well-defined values. As a result, depth-limited search algorithms used in single-agent settings and perfect-information games do not apply. This paper introduces a principled way to conduct depth-limited solving in imperfect-information games by allowing the opponent to choose among a number of strategies for the remainder of the game at the depth limit. Each one of these strategies results in a different set of values for leaf nodes. This forces an agent to be robust to the different strategies an opponent may employ. We demonstrate the effectiveness of this approach by building a master-level heads-up no-limit Texas hold'em poker AI that defeats two prior top agents using only a 4-core CPU and 16 GB of memory. Developing such a powerful agent would have previously required a supercomputer.
</div>

</td>
</tr>


<tr id="tr-wang2018enabling" >
<td>
    <em><a href='https://dl.acm.org/citation.cfm?id=3209659' target='_blank'>Enabling Live Video Analytics with a Scalable and Privacy-Aware Framework</a> </em><br>
    <a href='https://junjuew.github.io/' target='_blank'>Junjue&nbsp;Wang</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://anupamdas.org/' target='_blank'>Anupam&nbsp;Das</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='https://www.normsadeh.org/' target='_blank'>Norman&nbsp;Sadeh</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    ACM TOMM 2018  <br>
    [23] 
[<a href='javascript:;'
    onclick='$("#abs_wang2018enabling").toggle()'>abs</a>]<br>
    
<div id="abs_wang2018enabling" style="text-align: justify; display: none" markdown="1">
We show how to build the components of a privacy-aware, live video
analytics ecosystem from the bottom up, starting
with OpenFace, our new open-source face recognition
system that approaches state-of-the-art
accuracy. Integrating OpenFace with interframe
tracking, we build RTFace, a mechanism for
denaturing video streams that selectively blurs
faces according to specified policies at full frame
rates. This enables privacy management for live
video analytics while providing a secure approach
for handling retrospective policy
exceptions. Finally, we present a scalable, privacy-aware architecture for large camera networks
using RTFace and show how it can be an enabler for a
vibrant ecosystem and marketplace of privacy-aware
video streams and analytics services.
</div>

</td>
</tr>

</table>
<h2>2017</h2>
<table class="table table-hover">

<tr id="tr-amos2017optnet" style="background-color: #ffffd0">
<td>
    <em><a href='http://arxiv.org/abs/1703.00443' target='_blank'>OptNet: Differentiable Optimization as a Layer in Neural Networks</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong> and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter</a><br>
    ICML 2017  <br>
    [24] 
[<a href='javascript:;'
    onclick='$("#abs_amos2017optnet").toggle()'>abs</a>] [<a href='https://github.com/locuslab/optnet' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2017.optnet.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_amos2017optnet" style="text-align: justify; display: none" markdown="1">
This paper presents OptNet, a network architecture that integrates
optimization problems (here, specifically in the form of quadratic programs)
as individual layers in larger end-to-end trainable deep networks.
These layers encode constraints and complex dependencies
between the hidden states that traditional convolutional and
fully-connected layers often cannot capture.
In this paper, we explore the foundations for such an architecture:
we show how techniques from sensitivity analysis, bilevel
optimization, and implicit differentiation can be used to
exactly differentiate through these layers and with respect
to layer parameters;
we develop a highly efficient solver for these layers that exploits fast
GPU-based batch solves within a primal-dual interior point method, and which
provides backpropagation gradients with virtually no additional cost on top of
the solve;
and we highlight the application of these approaches in several problems.
In one notable example, we show that the method is
capable of learning to play mini-Sudoku (4x4) given just input and output games, with no a priori information about the rules of the game;
this highlights the ability of our architecture to learn hard
constraints better than other neural architectures.
</div>

</td>
</tr>


<tr id="tr-amos2017input" style="background-color: #ffffd0">
<td>
    <em><a href='http://arxiv.org/abs/1609.07152' target='_blank'>Input Convex Neural Networks</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://leix28.github.io/' target='_blank'>Lei&nbsp;Xu</a>, and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter</a><br>
    ICML 2017  <br>
    [25] 
[<a href='javascript:;'
    onclick='$("#abs_amos2017input").toggle()'>abs</a>] [<a href='https://github.com/locuslab/icnn' target='_blank'>code</a>]  [<a href='http://bamos.github.io/data/slides/2017.icnn.pdf' target='_blank'>slides</a>] <br>
    
<div id="abs_amos2017input" style="text-align: justify; display: none" markdown="1">
This paper presents the input convex neural network
architecture. These are scalar-valued (potentially deep) neural
networks with constraints on the network parameters such that the
output of the network is a convex function of (some of) the inputs.
The networks allow for efficient inference via optimization over some
inputs to the network given others, and can be applied to settings
including structured prediction, data imputation, reinforcement
learning, and others. In this paper we lay the basic groundwork for
these models, proposing methods for inference, optimization and
learning, and analyze their representational power. We show that many
existing neural network architectures can be made input-convex with
a minor modification, and develop specialized optimization
algorithms tailored to this setting. Finally, we highlight the
performance of the methods on multi-label prediction, image
completion, and reinforcement learning problems, where we show
improvement over the existing state of the art in many cases.
</div>

</td>
</tr>


<tr id="tr-donti2017task" >
<td>
    <em><a href='http://arxiv.org/abs/1703.04529' target='_blank'>Task-based End-to-end Model Learning</a> </em><br>
    <a href='https://priyadonti.com/' target='_blank'>Priya&nbsp;L.&nbsp;Donti</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='http://zicokolter.com/' target='_blank'>J.&nbsp;Zico&nbsp;Kolter</a><br>
    NeurIPS 2017  <br>
    [26] 
[<a href='javascript:;'
    onclick='$("#abs_donti2017task").toggle()'>abs</a>] [<a href='https://github.com/locuslab/e2e-model-learning' target='_blank'>code</a>] <br>
    
<div id="abs_donti2017task" style="text-align: justify; display: none" markdown="1">
As machine learning techniques have become more ubiquitous, it has
become common to see machine learning prediction algorithms operating
within some larger process. However, the criteria by which we train
machine learning algorithms often differ from the ultimate criteria on
which we evaluate them. This paper proposes an end-to-end approach for
learning probabilistic machine learning models within the context of
stochastic programming, in a manner that directly captures the
ultimate task-based objective for which they will be used. We then
present two experimental evaluations of the proposed approach, one as
applied to a generic inventory stock problem and the second to a
real-world electrical grid scheduling task. In both cases, we show
that the proposed approach can outperform both a traditional modeling
approach and a purely black-box policy optimization approach.
</div>

</td>
</tr>


<tr id="tr-chen2017quasi" >
<td>
    <em><a href='https://par.nsf.gov/servlets/purl/10111392' target='_blank'>Quasi-Newton Stochastic Optimization Algorithm for Parameter Estimation of a Stochastic Model of the Budding Yeast Cell Cycle</a> </em><br>
    <a href='https://chenm.sites.wfu.edu/publications/' target='_blank'>Minghan&nbsp;Chen</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://people.cs.vt.edu/~ltw/shortvita.html' target='_blank'>Layne&nbsp;T.&nbsp;Watson</a>, <a href='https://scholar.google.com/citations?user=syETjMMAAAAJ' target='_blank'>John&nbsp;Tyson</a>, <a href='https://people.cs.vt.edu/~ycao/' target='_blank'>Yang&nbsp;Cao</a>, <a href='https://people.cs.vt.edu/shaffer/' target='_blank'>Cliff&nbsp;Shaffer</a>, <a href='https://mtrosset.pages.iu.edu/' target='_blank'>Michael&nbsp;Trosset</a>, <a href='https://scholar.google.com/citations?user=Z4534DUAAAAJ' target='_blank'>Cihan&nbsp;Oguz</a>, and <a href='https://dblp.org/pid/235/5473.html' target='_blank'>Gisella&nbsp;Kakoti</a><br>
    IEEE/ACM TCBB 2017  <br>
    [27] 
[<a href='javascript:;'
    onclick='$("#abs_chen2017quasi").toggle()'>abs</a>]<br>
    
<div id="abs_chen2017quasi" style="text-align: justify; display: none" markdown="1">
Parameter estimation in discrete or continuous deterministic cell
cycle models is challenging for several reasons, including the nature of what can be observed, and
the accuracy and quantity of those observations. The
challenge is even greater for stochastic models, where the number of simulations and amount of
empirical data must be even larger to obtain
statistically valid parameter estimates. The two
main contributions of this work are (1) stochastic
model parameter estimation based on directly
matching multivariate probability distributions, and
(2) a new quasi-Newton algorithm class QNSTOP for
stochastic optimization problems. QNSTOP directly
uses the random objective function value samples
rather than creating ensemble statistics. QNSTOP is
used here to directly match empirical and simulated
joint probability distributions rather than matching
summary statistics. Results are given for a current
state-of-the-art stochastic cell cycle model of
budding yeast, whose predictions match well some
summary statistics and one-dimensional distributions
from empirical data, but do not match well the
empirical joint distributions. The nature of the
mismatch provides insight into the weakness in the
stochastic model.
</div>

</td>
</tr>


<tr id="tr-ha2017you" >
<td>
    <em><a href='https://dl.acm.org/doi/10.1145/3132211.3134453' target='_blank'>You can teach elephants to dance: agile VM handoff for edge computing</a> </em><br>
    <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='https://dblp.org/pid/18/1620.html' target='_blank'>Yoshihisa&nbsp;Abe</a>, <a href='https://dblp.org/pid/207/9122.html' target='_blank'>Thomas&nbsp;Eiszler</a>, <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://dblp.org/pid/207/9123.html' target='_blank'>Rohit&nbsp;Upadhyaya</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    SEC 2017  <br>
    [28] 
[<a href='javascript:;'
    onclick='$("#abs_ha2017you").toggle()'>abs</a>]<br>
    
<div id="abs_ha2017you" style="text-align: justify; display: none" markdown="1">
VM handoff enables rapid and transparent placement changes to
executing code in edge computing use cases where the
safety and management attributes of VM encapsulation
are important. This versatile primitive offers the
functionality of classic live migration but is
highly optimized for the edge. Over WAN bandwidths
ranging from 5 to 25 Mbps, VM handoff migrates a
running 8 GB VM in about a minute, with a downtime
of a few tens of seconds. By dynamically adapting to
varying network bandwidth and processing load, VM
handoff is more than an order of magnitude faster
than live migration at those bandwidths.
</div>

</td>
</tr>


<tr id="tr-chen2017empirical" >
<td>
    <em><a href='https://www.cs.cmu.edu/~zhuoc/papers/latency2017.pdf' target='_blank'>An Empirical Study of Latency in an Emerging Class of Edge Computing Applications for Wearable Cognitive Assistance</a> </em><br>
    <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <a href='https://junjuew.github.io/' target='_blank'>Junjue&nbsp;Wang</a>, <a href='https://www.siyanz.com/' target='_blank'>Siyan&nbsp;Zhao</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=0pF6i38AAAAJ' target='_blank'>Guanhang&nbsp;Wu</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='https://scholar.google.com/citations?user=R9r5_GIAAAAJ' target='_blank'>Khalid&nbsp;Elgazzar</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='https://www.cmu.edu/dietrich/psychology/people/core-training-faculty/klatzky-roberta.html' target='_blank'>Roberta&nbsp;Klatzky</a>, <a href='http://www.cs.cmu.edu/~dps/' target='_blank'>Daniel&nbsp;Siewiorek</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    SEC 2017  <br>
    [29] 
[<a href='javascript:;'
    onclick='$("#abs_chen2017empirical").toggle()'>abs</a>]<br>
    
<div id="abs_chen2017empirical" style="text-align: justify; display: none" markdown="1">
An emerging class of interactive wearable cognitive assistance
applications is poised to become one of the key
demonstrators of edge computing infrastructure. In
this paper, we design seven such applications and
evaluate their performance in terms of latency
across a range of edge computing configurations, mobile hardware, and wireless networks, including 4G
LTE. We also devise a novel multi-algorithm approach
that leverages temporal locality to reduce
end-to-end latency by 60% to 70%, without
sacrificing accuracy. Finally, we derive target
latencies for our applications, and show that edge
computing is crucial to meeting these targets.
</div>

</td>
</tr>


<tr id="tr-wang2017scalable" >
<td>
    <em><a href='http://elijah.cs.cmu.edu/DOCS/wang-mmsys2017.pdf' target='_blank'>A Scalable and Privacy-Aware IoT Service for Live Video Analytics</a> </em><br>
    <a href='https://junjuew.github.io/' target='_blank'>Junjue&nbsp;Wang</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://anupamdas.org/' target='_blank'>Anupam&nbsp;Das</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='https://www.normsadeh.org/' target='_blank'>Norman&nbsp;Sadeh</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    ACM MMSys 2017 (Best Paper) <br>
    [30] [<a href='http://cmusatyalab.github.io/openface/' target='_blank'>code</a>] <br>
    
</td>
</tr>

</table>
<h2>2016</h2>
<table class="table table-hover">

<tr id="tr-amos2016openface" style="background-color: #ffffd0">
<td>
    <em><a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2016/CMU-CS-16-118.pdf' target='_blank'>OpenFace: A general-purpose face recognition library with mobile applications</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://www.linkedin.com/in/bartosz-ludwiczuk-a677a760' target='_blank'>Bartosz&nbsp;Ludwiczuk</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    CMU 2016  <br>
    [31] 
[<a href='javascript:;'
    onclick='$("#abs_amos2016openface").toggle()'>abs</a>] [<a href='https://cmusatyalab.github.io/openface' target='_blank'>code</a>] <br>
    
<div id="abs_amos2016openface" style="text-align: justify; display: none" markdown="1">
Cameras are becoming ubiquitous in the Internet of Things (IoT) and
can use face recognition technology to improve context. There is a
large accuracy gap between today's publicly available face recognition
systems and the state-of-the-art private face recognition
systems. This paper presents our OpenFace face recognition library
that bridges this accuracy gap. We show that OpenFace provides
near-human accuracy on the LFW benchmark and present a new
classification benchmark for mobile scenarios. This paper is intended
for non-experts interested in using OpenFace and provides a light
introduction to the deep neural network techniques we use.

We released OpenFace in October 2015 as an open source library under
the Apache 2.0 license. It is available at:
<http://cmusatyalab.github.io/openface/>
</div>

</td>
</tr>


<tr id="tr-zhao2016collapsed" >
<td>
    <em><a href='http://proceedings.mlr.press/v48/zhaoa16.html' target='_blank'>Collapsed Variational Inference for Sum-Product Networks</a> </em><br>
    <a href='https://hanzhaoml.github.io/' target='_blank'>Han&nbsp;Zhao</a>, <a href='https://tameemadel.wordpress.com/' target='_blank'>Tameem&nbsp;Adel</a>, <a href='http://www.cs.cmu.edu/~ggordon/' target='_blank'>Geoff&nbsp;Gordon</a>, and <strong>Brandon&nbsp;Amos</strong><br>
    ICML 2016  <br>
    [32] 
[<a href='javascript:;'
    onclick='$("#abs_zhao2016collapsed").toggle()'>abs</a>]<br>
    
<div id="abs_zhao2016collapsed" style="text-align: justify; display: none" markdown="1">
Sum-Product Networks (SPNs) are probabilistic inference machines that admit
exact inference in linear time in the size of the network. Existing
parameter learning approaches for SPNs are largely based on the maximum
likelihood principle and hence are subject to overfitting compared to
more Bayesian approaches. Exact Bayesian posterior inference for SPNs is
computationally intractable. Both standard variational inference and
posterior sampling for SPNs are computationally infeasible even for
networks of moderate size due to the large number of local latent
variables per instance. In this work, we propose a novel deterministic
collapsed variational inference algorithm for SPNs that is
computationally efficient, easy to implement and at the same time allows
us to incorporate prior information into the optimization formulation.
Extensive experiments show a significant improvement in accuracy compared
with a maximum likelihood based approach.
</div>

</td>
</tr>


<tr id="tr-hu2016quantifying" >
<td>
    <em><a href='https://dl.acm.org/doi/10.1145/2967360.2967369' target='_blank'>Quantifying the impact of edge computing on mobile applications</a> </em><br>
    <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <a href='https://www.linkedin.com/in/joelyinggao/' target='_blank'>Ying&nbsp;Gao</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='https://junjuew.github.io/' target='_blank'>Junjue&nbsp;Wang</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    ACM SIGOPS 2016  <br>
    [33] 
[<a href='javascript:;'
    onclick='$("#abs_hu2016quantifying").toggle()'>abs</a>]<br>
    
<div id="abs_hu2016quantifying" style="text-align: justify; display: none" markdown="1">
Computational offloading services at the edge of the Internet for
mobile devices are becoming a reality. Using a wide
range of mobile applications, we explore how such
infrastructure improves latency and energy
consumption relative to the cloud. We present
experimental results from WiFi and 4G LTE networks
that confirm substantial wins from edge computing
for highly interactive mobile applications.
</div>

</td>
</tr>


<tr id="tr-davies2016privacy" >
<td>
    <em><a href='http://eprints.lancs.ac.uk/78255/1/44691.pdf' target='_blank'>Privacy mediators: helping IoT cross the chasm</a> </em><br>
    <a href='https://www.lancaster.ac.uk/sci-tech/about-us/people/nigel-davies' target='_blank'>Nigel&nbsp;Davies</a>, <a href='https://scholar.google.com/citations?user=BItCgjYAAAAJ' target='_blank'>Nina&nbsp;Taft</a>, <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a>, <a href='http://www.sclinch.com/' target='_blank'>Sarah&nbsp;Clinch</a>, and <strong>Brandon&nbsp;Amos</strong><br>
    HotMobile 2016  <br>
    [34] 
[<a href='javascript:;'
    onclick='$("#abs_davies2016privacy").toggle()'>abs</a>]<br>
    
<div id="abs_davies2016privacy" style="text-align: justify; display: none" markdown="1">
Unease over data privacy will retard consumer acceptance of IoT
deployments. The primary source of discomfort is a lack of user
control over raw data that is streamed directly from sensors to the
cloud. This is a direct consequence of the over-centralization of
today’s cloud-based IoT hub designs. We propose a solution that
interposes a locally-controlled software component called a privacy
mediator on every raw sensor stream. Each mediator is in the same
administrative domain as the sensors whose data is being collected, and dynamically enforces the current privacy policies of the owners
of the sensors or mobile users within the domain. This solution necessitates
a logical point of presence for mediators within the administrative
boundaries of each organization. Such points of presence
are provided by cloudlets, which are small locally-administered data
centers at the edge of the Internet that can support code mobility.
The use of cloudlet-based mediators aligns well with natural personal
and organizational boundaries of trust and responsibility.
</div>

</td>
</tr>

</table>
<h2>2015 and earlier</h2>
<table class="table table-hover">

<tr id="tr-satyanarayanan2015edge" >
<td>
    <em><a href='https://www.cs.cmu.edu/~satya/docdir/satya-edge2015.pdf' target='_blank'>Edge Analytics in the Internet of Things</a> </em><br>
    <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a>, <a href='https://www.ugent.be/ea/idlab/en/members/pieter-simoens.htm' target='_blank'>Pieter&nbsp;Simoens</a>, <a href='https://scholar.google.com/citations?user=ZeRhyWsAAAAJ' target='_blank'>Yu&nbsp;Xiao</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, and <strong>Brandon&nbsp;Amos</strong><br>
    IEEE Pervasive Computing 2015  <br>
    [35] 
[<a href='javascript:;'
    onclick='$("#abs_satyanarayanan2015edge").toggle()'>abs</a>]<br>
    
<div id="abs_satyanarayanan2015edge" style="text-align: justify; display: none" markdown="1">
High-data-rate sensors, such as video cameras, are becoming ubiquitous in the
Internet of Things. This article describes GigaSight, an Internet-scale
repository of crowd-sourced video content, with strong enforcement of privacy
preferences and access controls. The GigaSight architecture is a federated
system of VM-based cloudlets that perform video analytics at the edge of the
Internet, thus reducing the demand for ingress bandwidth into the cloud.
Denaturing, which is an owner-specific reduction in fidelity of video content
to preserve privacy, is one form of analytics on cloudlets. Content-based
indexing for search is another form of cloudlet-based analytics. This article
is part of a special issue on smart spaces.
</div>

</td>
</tr>


<tr id="tr-turner2015bad" >
<td>
    <em><a href='http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7118094' target='_blank'>Bad Parts: Are Our Manufacturing Systems at Risk of Silent Cyberattacks?</a> </em><br>
    <a href='https://scholar.google.com/citations?user=MRKab9cAAAAJ' target='_blank'>Hamilton&nbsp;Turner</a>, <a href='https://scholar.google.com/citations?user=10HSX90AAAAJ' target='_blank'>Jules&nbsp;White</a>, <a href='https://scholar.google.com/citations?user=tWmVBNwAAAAJ' target='_blank'>Jaime&nbsp;A.&nbsp;Camelio</a>, <a href='https://scholar.google.com/citations?user=AW81mosAAAAJ' target='_blank'>Christopher&nbsp;Williams</a>, <strong>Brandon&nbsp;Amos</strong>, and <a href='https://ieeexplore.ieee.org/author/37085729541' target='_blank'>Robert&nbsp;Parker</a><br>
    IEEE Security & Privacy 2015  <br>
    [36] 
[<a href='javascript:;'
    onclick='$("#abs_turner2015bad").toggle()'>abs</a>]<br>
    
<div id="abs_turner2015bad" style="text-align: justify; display: none" markdown="1">
Recent cyberattacks have highlighted the risk of physical equipment operating
outside designed tolerances to produce catastrophic failures. A related
threat is cyberattacks that change the design and manufacturing of a
machine's part, such as an automobile brake component, so it no longer
functions properly. These risks stem from the lack of cyber-physical models
to identify ongoing attacks as well as the lack of rigorous application of
known cybersecurity best practices. To protect manufacturing processes in the
future, research will be needed on a number of critical cyber-physical
manufacturing security topics.
</div>

</td>
</tr>


<tr id="tr-chen2015early" >
<td>
    <em><a href='http://www.cs.cmu.edu/~satya/docdir/chen-wearsys2015.pdf' target='_blank'>Early Implementation Experience with Wearable Cognitive Assistance Applications</a> </em><br>
    <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://www.lujiang.info/' target='_blank'>Lu&nbsp;Jiang</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='http://www.cs.cmu.edu/~alex/' target='_blank'>Alex&nbsp;Hauptmann</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    WearSys 2015  <br>
    [37] 
[<a href='javascript:;'
    onclick='$("#abs_chen2015early").toggle()'>abs</a>]<br>
    
<div id="abs_chen2015early" style="text-align: justify; display: none" markdown="1">
A cognitive assistance application combines a wearable device such
as Google Glass with cloudlet processing to provide step-by-step
guidance on a complex task. In this paper, we focus on user assistance
for narrow and well-defined tasks that require specialized
knowledge and/or skills. We describe proof-of-concept implementations
for four different tasks: assembling 2D Lego models, freehand
sketching, playing ping-pong, and recommending context-relevant
YouTube tutorials. We then reflect on the difficulties we faced in
building these applications, and suggest future research that could
simplify the creation of similar applications.
</div>

</td>
</tr>


<tr id="tr-hu2014case" >
<td>
    <em><a href='http://www.cs.cmu.edu/~satya/docdir/hu-hotmobile2015.pdf' target='_blank'>The Case for Offload Shaping</a> </em><br>
    <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='https://scholar.google.com/citations?user=vU6bKxEAAAAJ' target='_blank'>Wolfgang&nbsp;Richter</a>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, <a href='https://github.com/bgilbert' target='_blank'>Benjamin&nbsp;Gilbert</a>, <a href='https://scholar.google.com/citations?user=jj5tN8sAAAAJ' target='_blank'>Jan&nbsp;Harkes</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    HotMobile 2015  <br>
    [38] 
[<a href='javascript:;'
    onclick='$("#abs_hu2014case").toggle()'>abs</a>]<br>
    
<div id="abs_hu2014case" style="text-align: justify; display: none" markdown="1">
When offloading computation from a mobile device, we show
that it can pay to perform additional on-device work in order
to reduce the offloading workload. We call this offload shaping, and demonstrate its application at many different levels
of abstraction using a variety of techniques. We show that
offload shaping can produce significant reduction in resource
demand, with little loss of application-level fidelity
</div>

</td>
</tr>


<tr id="tr-gao2015cloudlets" >
<td>
    <em><a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2015/CMU-CS-15-139.pdf' target='_blank'>Are Cloudlets Necessary?</a> </em><br>
    <a href='https://www.linkedin.com/in/joelyinggao/' target='_blank'>Ying&nbsp;Gao</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    CMU 2015  <br>
    [39] 
[<a href='javascript:;'
    onclick='$("#abs_gao2015cloudlets").toggle()'>abs</a>]<br>
    
<div id="abs_gao2015cloudlets" style="text-align: justify; display: none" markdown="1">
We present experimental results from Wi-Fi and 4G LTE networks to validate the
intuition that low end-to-end latency of cloud services improves application
response time and reduces energy consumption on mobile devices. We focus
specifically on computational offloading as a cloud service. Using a wide
range of applications, and exploring both pre-partitioned and dynamically
partitioned approaches, we demonstrate the importance of low latency for
cloud offload services. We show the best performance is achieved by
offloading to cloudlets, which are small-scale edge-located data centers. Our
results show that cloudlets can improve response times 51% and reduce energy
consumption in a mobile device by up to 42% compared to cloud offload.
</div>

</td>
</tr>


<tr id="tr-ha2015adaptive" >
<td>
    <em><a href='http://ra.adm.cs.cmu.edu/anon/2015/CMU-CS-15-113.pdf' target='_blank'>Adaptive VM handoff across cloudlets</a> </em><br>
    <a href='http://krha.kr/' target='_blank'>Kiryong&nbsp;Ha</a>, <a href='https://dblp.org/pid/18/1620.html' target='_blank'>Yoshihisa&nbsp;Abe</a>, <a href='https://scholar.google.com/citations?user=-wKpBNkAAAAJ' target='_blank'>Zhuo&nbsp;Chen</a>, <a href='http://www.cs.cmu.edu/~wenluh/' target='_blank'>Wenlu&nbsp;Hu</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://www.andrew.cmu.edu/user/pspillai/' target='_blank'>Padmanabhan&nbsp;Pillai</a>, and <a href='https://www.cs.cmu.edu/~satya/' target='_blank'>Mahadev&nbsp;Satyanarayanan</a><br>
    CMU 2015  <br>
    [40] 
[<a href='javascript:;'
    onclick='$("#abs_ha2015adaptive").toggle()'>abs</a>]<br>
    
<div id="abs_ha2015adaptive" style="text-align: justify; display: none" markdown="1">
Cloudlet offload is a valuable technique for ensuring low end-to-end latency of
resource-intensive cloud processing for many emerging mobile applications.
This paper examines the impact of user mobility on cloudlet offload, and
shows that even modest user mobility can result in significant network
degradation. We propose VM handoff as a technique for seamlessly transferring
VMencapsulated execution to a more optimal offload site as users move. Our
approach can perform handoff in roughly a minute even over limited WANs by
adaptively reducing data transferred. We present experimental results to
validate our implementation and to demonstrate effectiveness of adaptation to
changing network conditions and processing capacity
</div>

</td>
</tr>


<tr id="tr-andrew2014global" >
<td>
    <em><a href='http://dl.acm.org/citation.cfm?id=2685662' target='_blank'>Global Parameter Estimation for a Eukaryotic Cell Cycle Model in Systems Biology</a> </em><br>
    <a href='https://scholar.google.com/citations?user=qpRt_KYAAAAJ' target='_blank'>Tricity&nbsp;Andrew</a>, <strong>Brandon&nbsp;Amos</strong>, <a href='https://dblp.org/pid/75/8682.html' target='_blank'>David&nbsp;Easterling</a>, <a href='https://scholar.google.com/citations?user=Z4534DUAAAAJ' target='_blank'>Cihan&nbsp;Oguz</a>, <a href='https://scholar.google.com/citations?user=fAmU38gAAAAJ' target='_blank'>William&nbsp;Baumann</a>, <a href='https://scholar.google.com/citations?user=syETjMMAAAAJ' target='_blank'>John&nbsp;Tyson</a>, and <a href='https://people.cs.vt.edu/~ltw/shortvita.html' target='_blank'>Layne&nbsp;T.&nbsp;Watson</a><br>
    SummerSim 2014  <br>
    [41] 
[<a href='javascript:;'
    onclick='$("#abs_andrew2014global").toggle()'>abs</a>]<br>
    
<div id="abs_andrew2014global" style="text-align: justify; display: none" markdown="1">
The complicated process by which a yeast cell divides, known as the cell
cycle, has been modeled by a system of 26 nonlinear ordinary differential
equations (ODEs) with 149 parameters. This model captures the chemical
kinetics of the regulatory networks controlling the cell division process
in budding yeast cells. Empirical data is discrete and matched against
discrete inferences (e.g., whether a particular mutant cell lives or dies)
computed from the ODE solution trajectories. The problem of
estimating the ODE parameters to best fit the model to the data is a
149-dimensional global optimization problem attacked by the deterministic
algorithm VTDIRECT95 and by the nondeterministic algorithms differential
evolution, QNSTOP, and simulated annealing, whose performances are
compared.
</div>

</td>
</tr>


<tr id="tr-amos2013applying" >
<td>
    <em><a href='http://bamos.github.io/data/papers/amos-iwcmc2013.pdf' target='_blank'>Applying machine learning classifiers to dynamic Android malware detection at scale</a> </em><br>
    <strong>Brandon&nbsp;Amos</strong>, <a href='https://scholar.google.com/citations?user=MRKab9cAAAAJ' target='_blank'>Hamilton&nbsp;Turner</a>, and <a href='https://scholar.google.com/citations?user=10HSX90AAAAJ' target='_blank'>Jules&nbsp;White</a><br>
    IWCMC 2013  <br>
    [42] 
[<a href='javascript:;'
    onclick='$("#abs_amos2013applying").toggle()'>abs</a>] [<a href='https://github.com/VT-Magnum-Research/antimalware' target='_blank'>code</a>] <br>
    
<div id="abs_amos2013applying" style="text-align: justify; display: none" markdown="1">
The widespread adoption and contextually sensitive
nature of smartphone devices has increased concerns over smartphone
malware. Machine learning classifiers are a current method
for detecting malicious applications on smartphone systems. This
paper presents the evaluation of a number of existing classifiers, using a dataset containing thousands of real (i.e. not synthetic)
applications. We also present our STREAM framework, which
was developed to enable rapid large-scale validation of mobile
malware machine learning classifiers.
</div>

</td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Invited Talks
<table class="table table-hover">
<tr>
  <td>
        Columbia University
  </td>
  <td class='col-md-1' style='text-align:right;'>2021</td>
</tr>
<tr>
  <td>
        IBM Research
  </td>
  <td class='col-md-1' style='text-align:right;'>2021</td>
</tr>
<tr>
  <td>
        Max Planck Institute for Intelligent Systems (Tübingen) Seminar
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        Montreal Institute for Learning Algorithms Seminar
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="https://anucvml.github.io/ddn-eccvt2020/">ECCV Deep Declarative Networks Tutorial</a>
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="https://anucvml.github.io/ddn-cvprw2020/">CVPR Deep Declarative Networks Workshop</a>
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="https://sites.google.com/view/cs-159-spring-2020/lectures">Caltech CS 159, Guest Lecture</a>
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        SIAM MDS Minisymposium on Learning Parameterized Energy Minimization Models
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        New York University CILVR Seminar
  </td>
  <td class='col-md-1' style='text-align:right;'>2019</td>
</tr>
<tr>
  <td>
        INFORMS Session on Prediction and Optimization
  </td>
  <td class='col-md-1' style='text-align:right;'>2019</td>
</tr>
<tr>
  <td>
        Facebook AI Research
  </td>
  <td class='col-md-1' style='text-align:right;'>2019</td>
</tr>
<tr>
  <td>
        ISMP Session on Machine Learning and Optimization
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        Google Brain
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        Bosch Center for AI
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        Waymo Research
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        Tesla AI
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        NVIDIA Robotics
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        Salesforce Research
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        OpenAI
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        NNAISENSE
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
<tr>
  <td>
        UC Berkeley
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Interns and Students
<table class="table table-hover">
<tr>
  <td>
        <a href="https://scholar.google.com/citations?user=CmdjfTsAAAAJ">Samuel Cohen</a> (visiting FAIR from UCL)
  </td>
  <td class='col-md-1' style='text-align:right;'>2021</td>
</tr>
<tr>
  <td>
        <a href="https://eugenevinitsky.github.io/">Eugene Vinitsky</a> (visiting FAIR from Berkeley)
  </td>
  <td class='col-md-1' style='text-align:right;'>2021</td>
</tr>
<tr>
  <td>
        <a href="https://www.linkedin.com/in/arnaudfickinger/">Arnaud Fickinger</a> (visiting FAIR from Berkeley)
  </td>
  <td class='col-md-1' style='text-align:right;'>2021</td>
</tr>
<tr>
  <td>
        <a href="https://www.aaronlou.com/">Aaron Lou</a> (visiting FAIR from Cornell, now: Ph.D. student at Stanford)
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="http://www.cs.toronto.edu/~rtqichen/">Ricky Chen</a> (visiting FAIR from Toronto, now: scientist at FAIR)
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="http://www.cs.cmu.edu/~pliang/">Paul Liang</a> (visiting FAIR from CMU)
  </td>
  <td class='col-md-1' style='text-align:right;'>2020</td>
</tr>
<tr>
  <td>
        <a href="https://phillipkwang.com/">Phillip Wang</a> (at CMU, now: CEO at <a href="https://gather.town/" target="_blank">Gather</a>)
  </td>
  <td class='col-md-1' style='text-align:right;'>2018</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Professional Activities
<table class="table table-hover">
<tr>
  <td>
      Reviewing: AAAI, ICML, NeurIPS, ICLR*, ICCV, CVPR, ICRA
  <br><p style="color:grey;font-size:1.2rem">*Outstanding reviewer</p>
  <td class='col-md-2' style='text-align:right;'></td>
  </td>
</tr>
<tr>
  <td>
     <a href="https://sites.google.com/view/lmca2020/home">NeurIPS Learning Meets Combinatorial Optimization Workshop Organizer</a>
  <td class='col-md-2' style='text-align:right;'>2020</td>
  </td>
</tr>
<tr>
  <td>
     <a href="https://anucvml.github.io/ddn-cvprw2020/">CVPR Deep Declarative Workshop Organizer</a>
  <td class='col-md-2' style='text-align:right;'>2020</td>
  </td>
</tr>
<tr>
  <td>
     <a href="https://anucvml.github.io/ddn-eccvt2020/">ECCV Deep Declarative Tutorial Organizer</a>
  <td class='col-md-2' style='text-align:right;'>2020</td>
  </td>
</tr>
<tr>
  <td>
      CMU CSD MS Admissions
  <td class='col-md-2' style='text-align:right;'>2014 - 2015</td>
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Teaching
<table class="table table-hover">
<tr>
  <td><strong>Graduate AI</strong> (CMU 15-780), TA</td>
  <td class='col-md-1' style='text-align:right;'>S2017</td>
</tr>
<tr>
  <td><strong>Distributed Systems</strong> (CMU 15-440/640), TA</td>
  <td class='col-md-1' style='text-align:right;'>S2016</td>
</tr>
<tr>
  <td><strong>Software Design and Data Structures</strong> (VT CS2114), TA</td>
  <td class='col-md-1' style='text-align:right;'>S2013</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Programming</td>
  <td>
C, C++, Fortran, Haskell, Java, Lua, Make, Mathematica, Python, R, Scala
  </td>
</tr>
<tr>
  <td class='col-md-2'>Frameworks</td>
  <td>
JAX, NumPy, Pandas, PyTorch, SciPy, TensorFlow, Torch7
  </td>
</tr>
<tr>
  <td class='col-md-2'>Tools</td>
  <td>
Linux, emacs, vim, evil, org, mu4e, xmonad, git, tmux, zsh
  </td>
</tr>
</table>
