
## <i class="fa fa-chevron-right"></i> Publications

Representative publications that I am a primary author on are
<span style='background-color: #ffffd0'>highlighted.</span><br>
[<a href="https://scholar.google.com/citations?user=DclFbLwAAAAJ&hl">Google Scholar</a>]






<h2>2021</h2>
<table class="table table-hover">

<tr id="tr-qiang21_iconip" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/SaSD.pdf' target='_blank'>Speech Dereverberation Based on Scale-aware Mean Square Error Loss</a> </em><br>
    Luya&nbsp;Qiang, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi&nbsp;(Joint&nbsp;First&nbsp;Author)</a></strong>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, Haoran&nbsp;Yin, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICONIP 2021  <br>
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_qiang21_iconip").toggle()'>abs</a>]<br>
    
<div id="abs_qiang21_iconip" style="text-align: justify; display: none" markdown="1">
Recently, deep learning-based speech dereverberation approaches have achieved remarkable performance by directly
mapping the input spectrogram to a target spectrogram or time-frequency mask. However, these approaches are usually
optimized under distance-related objective functions: the mean square error (MSE). The traditional MSE training
criterion results in a strong inherent uniform variance statistical assumption on the target speech and noise during
training, which cannot be satisfied in real-world scenarios. To alleviate such an assumption mismatch problem, we
propose a speech dereverberation solution called Scale-aware Speech Dereverberation (SaSD) based on scaled-MSE.
Specifically, we modify the MSE with different scales for each frequency band and progressively reduce the gap
between the low- and high-frequency ranges to make the error follow the assumption of MSE assumption. Experiments
demonstrated that SaSD achieved 1.0 SRMR and 0.8 PESQ improvements over the mapping baseline system.
</div>

</td>
</tr>


<tr id="tr-yin21_iconip" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/iconip2021-yin.pdf' target='_blank'>Simultaneous Progressive Filtering-based Monaural Speech Enhancement</a> </em><br>
    Haoran&nbsp;Yin, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi&nbsp;(Joint&nbsp;First&nbsp;Author)</a></strong>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, Luya&nbsp;Qiang, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, Gaoyan&nbsp;Zhang, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICONIP 2021  <br>
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_yin21_iconip").toggle()'>abs</a>]<br>
    
<div id="abs_yin21_iconip" style="text-align: justify; display: none" markdown="1">
Speech enhancement (SE) benefits from multi-stage stacking. However, this will introduce a lot of new
parameters to the neural network. In this paper, we propose a simultaneous progressive filtering based
monaural SE model. Mapping-based and masking-based SE systems are simultaneously obtained with
multi-target learning (MTL). Different from other MTL systems, our proposed model addresses different
enhancement needs. The mapping-based SE system aims to recover speech signals from noisy features. While
the masking-based SE system serves as a post-filtering to further reduce the noise that still exists
after the mapping-based SE system. With the high signal-to-noise ratio inputs, noise reduction of the
masking-based SE system is obvious with little speech signal loss. These two stages share one neural
network which controls the parameters of the entire system with little or no increase. In addition, our approach is easy to integrate with existing methods and improve their performance significantly and
stably. The experiments on Valentini-Botinhao data set show our proposed model achieves 0.12 PESQ
improvement compared with directly mapping-based and masking-based SE systems both in single-target
and multi-target learning. Furthermore, by comparing spectrograms, we find that our proposed models are
able to recover better harmonic information.
</div>

</td>
</tr>


<tr id="tr-shi21_apsipa" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/APSIPA-2021.pdf' target='_blank'>Spectrograms Fusion-based End-to-end Robust Automatic Speech Recognition</a> </em><br>
    <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a></strong>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=QbnlF74AAAAJ' target='_blank'>Cunhang&nbsp;Fan</a>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and <a href='https://scholar.google.com/citations?user=o3AmlFYAAAAJ' target='_blank'>Tatsuya&nbsp;Kawahara</a><br>
    APSIPA 2021  <br>
    [3] 
[<a href='javascript:;'
    onclick='$("#abs_shi21_apsipa").toggle()'>abs</a>]<br>
    
<div id="abs_shi21_apsipa" style="text-align: justify; display: none" markdown="1">
To improve the robustness of automatic speech recognition (ASR), speech enhancement (SE) is often used
as a front-end noise-removal process. Although there is complementarity between the mapping-based and
the mask-based SE system, one of the SE systems has been conventionally used as the front-end of ASR.
We propose a spectrogram fusion (SF)-based end-to-end (E2E) robust ASR system, in which the mapping-based
and masking-based SE are used as the front-end simultaneously. We adopt SF to combine the advantages of
mapping-based and masking-based SE systems. SF and ASR modules are connected in an E2E manner, and joint
training is conducted to finetune the front-end and the back-end. We compared the performance of
different front-ends after joint training. From the experiments using Aishell and PNL 100 Nonspeech
Sounds datasets, we found that the fusion of two SEs are beneficial for ASR, especially under low
signal-to-noise ratio, where a relative improvement of more than 7% is achieved.
</div>

</td>
</tr>

</table>
<h2>2020</h2>
<table class="table table-hover">

<tr id="tr-shi20_interspeech" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/Wed-1-11-1.pdf' target='_blank'>Singing Voice Extraction with Attention-Based Spectrograms Fusion</a> </em><br>
    <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a></strong>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, Chenchen&nbsp;Ding, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and Hiroshi&nbsp;Seki<br>
    INTERSPEECH 2020  <br>
    [4] 
[<a href='javascript:;'
    onclick='$("#abs_shi20_interspeech").toggle()'>abs</a>]<br>
    
<div id="abs_shi20_interspeech" style="text-align: justify; display: none" markdown="1">
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
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/0007539.pdf' target='_blank'>Spectrograms Fusion with Minimum Difference Masks Estimation for Monaural Speech Dereverberation</a> </em><br>
    <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a></strong>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICASSP 2020  <br>
    [5] 
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
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/1477.pdf' target='_blank'>Environment-Dependent Attention-Driven Recurrent Convolutional Neural Network for Robust Speech Enhancement</a> </em><br>
    <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a></strong>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and Xiangang&nbsp;Li<br>
    INTERSPEECH 2019  <br>
    [6] 
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

