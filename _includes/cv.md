 I am a Ph.D. student in Speech and Audio Processing Lab., (Kyoto University, Japan) where I studied under the supervision of Prof. Tatsuya Kawahara. I received the Master’s degree from College of Intelligence and Computing, Tianjin University. My main topics are speech enhancement and robust automatic speech recognition. <br><br>


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td>
      <strong>Ph.D. in Computer Science</strong>, Carnegie Mellon University
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
      <br>
    </td>
    <td class="col-md-2" style='text-align:right;'>2011 - 2014</td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Research Experience
<table class="table table-hover">
<tr>
  <td class='col-md-3'>May 2019 - Present</td>
  <td>
    <strong>Facebook AI</strong>,  <br>
    Machine learning and optimization
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Publications

Representative publications that I am a primary author on are
<span style='background-color: #ffffd0'>highlighted.</span><br>
[<a href="https://scholar.google.com/citations?user=DclFbLwAAAAJ&hl">Google Scholar</a>]
[<a href="https://github.com/bamos/cv/blob/master/publications/all.bib">BibTeX</a>]

<h2>2020</h2>
<table class="table table-hover">

<tr id="tr-9054661" style="background-color: #ffffd0">
<td>
    <em><a href='https://hshi-speech.github.io/resume/pdf/Wed-1-11-1.pdf' target='_blank'>Singing Voice Extraction with Attention-Based Spectrograms Fusion</a> </em><br>
    <a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, Chenchen&nbsp;Ding, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and Hiroshi&nbsp;Seki<br>
    INTERSPEECH 2020  <br>
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_9054661").toggle()'>abs</a>]<br>
    
<div id="abs_9054661" style="text-align: justify; display: none" markdown="1">
We propose a novel attention mechanism-based spectrograms fusion system with minimum difference masks (MDMs)
estimation for singing voice extraction. Compared with previous works that use a fully connected neural
network, our system takes advantage of the multi-head attention mechanism. Specifically, we 1) try a variety
of embedding methods of multiple spectrograms as the input of attention mechanisms, which can provide
multi-scale correlation information between adjacent frames in the spectrograms; 2) add a regular term to
loss function to obtain better continuity of spectrogram; 3) use the phase of the linear fusion waveform to
reconstruct the final waveform, which can reduce the impact of the inconsistent spectrogram. Experiments on
the MIR-1K dataset show that our system consistently improves the quantitative evaluation by the perceptual
evaluation of speech quality, signal-to-distortion ratio, signal-to-interference ratio, and signal-to-artifact ratio.
</div>

</td>
</tr>


<tr id="tr-9054661" style="background-color: #ffffd0">
<td>
    <em><a href='https://hshi-speech.github.io/resume/pdf/0007539.pdf' target='_blank'>Spectrograms Fusion with Minimum Difference Masks Estimation for Monaural Speech Dereverberation</a> </em><br>
    <a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICASSP 2020  <br>
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_9054661").toggle()'>abs</a>]<br>
    
<div id="abs_9054661" style="text-align: justify; display: none" markdown="1">
Spectrograms fusion is an effective method for incorporating complementary speech dereverberation systems.
Previous linear spectrograms fusion by averaging multiple spectrograms shows outstanding performance.
However, various systems with different features cannot apply this simple method. In this study, we design
the minimum difference masks (MDMs) to classify the time-frequency (T-F) bins in spectrograms according to
the nearest distances from labels. Then, we propose a two-stage nonlinear spectrograms fusion system for
speech dereverberation. First, we conduct a multitarget learning-based speech dereverberation front-end
model to get spectrograms simultaneously. Then, MDMs are estimated to take the best parts of different
spectrograms. We are using spectrograms in the first stage and MDMs in the second stage to recombine T-F
bins. The experiments on the REVERB challenge show that a strong feature complementarity between
spectrograms and MDMs. Moreover, the proposed framework can consistently and significantly improve PESQ
and SRMR, both real and simulated data, e.g., an average PESQ gain of 0.1 in all simulated data and an
average SRMR gain of 1.22 in all real data.
</div>

</td>
</tr>

</table>
<h2>2019</h2>
<table class="table table-hover">

<tr id="tr-ge19_interspeech" >
<td>
    <em><a href='https://hshi-speech.github.io/resume/pdf/1477.pdf' target='_blank'>Environment-Dependent Attention-Driven Recurrent Convolutional Neural Network for Robust Speech Enhancement</a> </em><br>
    <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and Xiangang&nbsp;Li<br>
    INTERSPEECH 2019  <br>
    [3] 
[<a href='javascript:;'
    onclick='$("#abs_ge19_interspeech").toggle()'>abs</a>]<br>
    
<div id="abs_ge19_interspeech" style="text-align: justify; display: none" markdown="1">
Speech enhancement aims to keep the real speech signal and reduce noise for building robust communication systems.
Under the success of DNN, significant progress has been made. Nevertheless, accuracy of the speech enhancement
system is not satisfactory due to insufficient consideration of varied environmental and contextual information in
complex cases. To address these problems, this research proposes an end-to-end environment-dependent attention-driven
approach. The local frequency-temporal pattern via convolutional neural network is fully employed without pooling
operation. It then integrates an attention mechanism into bidirectional long short-term memory to acquire the weighted
dynamic context between consecutive frames. Furthermore, dynamic environment estimation and phase correction further
improve the generalization ability. Extensive experimental results on REVERB challenge demonstrated that the proposed
approach outperformed existing methods, improving PESQ from 2.56 to 2.87 and SRMR from 4.95 to 5.50 compared with conventional DNN.
</div>

</td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Programming</td>
  <td>
C, C++, Java, Python
  </td>
</tr>
<tr>
  <td class='col-md-2'>Frameworks</td>
  <td>
NumPy, PyTorch, SciPy, TensorFlow
  </td>
</tr>
<tr>
  <td class='col-md-2'>Tools</td>
  <td>
Linux, vim git, tmux
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Hobbies
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Piano</td>
  <td>
Sonata
  </td>
</tr>
<tr>
  <td class='col-md-2'>Basketball</td>
  <td>
Small Forward (SF)
  </td>
</tr>
<tr>
  <td class='col-md-2'>Swimming</td>
  <td>
Breaststroke
  </td>
</tr>
<tr>
  <td class='col-md-2'>Music</td>
  <td>
Rock
  </td>
</tr>
</table>
